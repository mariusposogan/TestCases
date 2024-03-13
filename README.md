# Test Case Samples

Below are some Test Case samples that I wrote while working on previous projects 

*********************************

**Test case Scenario:**
Validate/Check login functionality using valid credentials 

**Test Steps:**
1. Input valid username in username field
2. Input valid password in password field
3. Press Login Button

**Expected result:**
User is redirected to account page.

**Test data**
User: alexandru  &  Pass: parola123

*********************************

**Test case Scenario:**
Verify if the login form works when rotating the screen during logging in.

**Test Steps:**
1. Go to www.onlinestore.com/login
2. Input valid username in username field
3. Input valid password in password field
4. Rotate the device screen from landscape to portrait mode and portrait to landscape
5. Press Login Button

**Expected result:**
Application should rotate normally and fields should still be filled with previously entered data.
After Login Button is pressed the user should be logged in successfully.

**Test data**
User: alexandru  &  Pass: parola123

*********************************

**Test case Scenario:**
Verify that the SHOW/HIDE button works.

**Test Steps:**
1. Go to www.onlinestore.com/login
2. Input username in username field
3. Input password in password field
4. Click on "SHOW"
5. Click on "HIDE"

**Expected result:**
The password should be shown to the user when she clicks on "SHOW" and hidden when she clicks on "HIDE".

**Test data**
User: alexandru@email.com  &  Pass: parola123

*********************************

**Test case Scenario:**
Check if Forgot Password functionality works as expected and an email with reset password link is sent.

**Test Steps:**
1. Go to www.onlinestore.com/login
2. Press "Forgot Password" Button
2. Input valid email in the email field
4. Press "Recover" button

**Expected result:**
User should receive an email with a reset password link. That link should allow the user to create a new password.

**Test data**
User: alexsmith@email.com

**Note**
Please check the login again after running this test case.

*********************************

**Test case Scenario:**
Check attempt to login with a valid email and invalid password.

**Test Steps:**
1. Go to www.onlinestore.com/login
2. Input valid username in username field
3. Input ivvalid password in password field
4. Press Login Button

**Expected result:**
An error message stating that "Email/Password is incorrect" should appear.

**Test data**
User: alexsmith@email.com  &  Password: wrong123

*********************************

**Test case Scenario:**
Check attempt to login with an unregistered email.

**Test Steps:**
1. Go to www.onlinestore.com/login
2. Input an unregistered username in username field
3. Input a password in password field
4. Press Login Button

**Expected result:**
An message stating that Email is not registered should appear with a link to invide the user to register a new account.

**Test data**
User: aaaaaaa@email.com  &  Password: abc123

*********************************

**Test case Scenario:**
Check attempt to login with all fields blank.

**Test Steps:**
1. Press Login Button

**Expected result:**
An error message should appear in the Email and Password fields stating that the Email and Password fields must not be empty

*********************************
