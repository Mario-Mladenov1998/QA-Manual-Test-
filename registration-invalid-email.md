🐞 Bug Report: "Add BUG Report" Registration accepted with invalid email
Description:
The registration form accepts an invalid email format and creates an account instead of showing an error.

Pre-conditions:

The user is on the registration page.

Steps to Reproduce:

Navigate to Amazon.com

Type donaldtrump@.com into the "Email" field

Type donaldTrump2025@ into the "Password" field

Click the "Register" button

Actual Result:

User is registered successfully, even with an invalid email format.

Expected Result:

An error message appears: “Invalid email format”

The form is not submitted.

Severity:

Major

Environment:

Google Chrome Version: 137.0.7151.56 (64-bit)

