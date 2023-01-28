# TestCases Samples

Below are some TestCases samples that I wrote during Udemy course

---------------

**Title:**
Test login with correct credentials

**Description:**
Test the login by using correct credentials.

**Steps to reproduce:**
1. Go to emag.ro/login
2. Add correct user/pass
3. Observe if user can login

**Expected Result:**
User shouldn't be able to login

**Test Data:**
User: test & Pass: 123

--------------------

**Title:**
Test login without correct credentials

**Description:**
Test the login by not using credentials.

**Steps to reproduce:**
1. Go to emag.ro/login
2. Add incorrect user/pass
3. Observe if user can not login

**Expected Result:**
User should be able to login

**Test Data:**
User: $$$$ & Pass: ££££

-------------------

**Title:**
Test login without credentials

**Description:**
Test the login by using incorrect credentials.

**Steps to reproduce:**
1. Go to emag.ro/login
2. Add no user/pass
3. Observe if user can not login

**Expected Result:**
User should be able to login

**Test Data:**


--------------------------------

**Title:**
Test forgot password functionality

**Description:**
Check if forgot password functionality works as expected and an email with reset password link is send

**Steps to reproduce:**
1. Go to emag.ro/login
2. Press ''forgot password'' button
3. Add an email address
4. Press "recover" button

**Expected Result:**
User should recive am email with a reset passwor link. That link should allow user to create new password.

**Test Data:**
user: diana.donca95@gmail.com

**Note**
please check the login again after running this test
