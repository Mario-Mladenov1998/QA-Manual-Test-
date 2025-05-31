### Bug Title: Check login with valid data - Error message shown 

### Description:
Login with valid credentials is unsuccessful. The system incorrectly returns an error message.

### Pre-conditions:
- The user is already registered with the following data.

### Steps to Reproduce:
1. Navigate to the login page
2. Type `JonJhones@gmail.com` into the "Email" field
3. Type `StrongPassword5132@` into the "Password" field
4. Click the "Login" button

### Actual Result:
- An error message appears: **"Wrong password or email address"**

### Expected Result:
- The user is logged in successfully.

### Severity:
Critical

### Environment:
Google Chrome Version: 137.0.7151.56 (64-bit)
