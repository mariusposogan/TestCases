# Test Case Samples

Below are some Test Case samples that I wrote while working on previous projects 

*********************************

**Description:**
Check if the Login works when a person uses correct credentials

**Steps to Reproduce:**
1. Go to www.onlinestore.com/login
2. Add correct user & password
3. Press Login Button

**Expected result:**
User should be able to login and is taken to her profile page.

**Test data**
User: alexandru  &  Pass: parola123

*********************************

**Description:**
Verify if the login form works when rotating the screen during logging in.

**Steps to Reproduce:**
1. Go to www.onlinestore.com/login
2. Add correct user & password
3. Rotate the device screen from landscape to portrait mode and portrait to landscape
4. Press Login Button

**Expected result:**
Application should rotates normally and fields should still be filled with previously entered data.
After Login Button is pressed the user should be logged in successfully.

**Test data**
User: alexandru  &  Pass: parola123

*********************************

**Description:**
Verify that the SHOW/HIDE button works.

**Steps to Reproduce:**
1. Go to www.onlinestore.com/login
2. Enter an email address
3. Enter a password
4. Click on "SHOW"
5. Click on "HIDE"

**Expected result:**
The password should be shown to the user when she clicks on "SHOW" and hidden when she clicks on "HIDE".

**Test data**
User: alexandru@email.com  &  Pass: parola123

*********************************

**Description:**
Check if Forgot Password functionality works as expected and an email with reset password link is sent.

**Steps to Reproduce:**
1. Go to www.onlinestore.com/login
2. Press "Forgot Password" Button
3. Add an email address
4. Press "Recover" button

**Expected result:**
User should receive an email with a reset password link. That link should allow the user to create a new password.

**Test data**
User: alexsmith@email.com

**Note**
Please check the login again after running this test case.

*********************************

**Description:**
Check attempt to login with a valid email and invalid password.

**Steps to Reproduce:**
1. Go to www.onlinestore.com/login
2. Enter a valid email
3. Enter an invalid password
4. Press Login Button

**Expected result:**
An error message stating that "Email/Password is incorrect" should appear.

**Test data**
User: alexsmith@email.com  &  Password: wrong123

*********************************

**Description:**
Check attempt to login with an unregistered email.

**Steps to Reproduce:**
1. Go to www.onlinestore.com/login
2. Enter an unregistered email
3. Enter a password
4. Press Login Button

**Expected result:**
An message stating that Email is not registered should appear with a link to invide the user to register a new account.

**Test data**
User: aaaaaaa@email.com  &  Password: abc123

*********************************

**Description:**
Check attempt to login with all fields blank.

**Steps to Reproduce:**
1. Press Login Button

**Expected result:**
An error message should appear in the Email and Password fields stating that the Email and Password fields must not be empty

*********************************
