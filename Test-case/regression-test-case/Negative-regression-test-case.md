# 1.❌ Regression Test – Login with Invalid Credentials

| Field              | Value                                 |
|--------------------|-------------------------------------|
| Suite              | Regression Test Case                 |
| Severity           | Major                               |
| Priority           | High                                |
| Type               | Regression                         |
| Layer              | E2E                                |
| Automation status   | Manual                             |
| Behavior           | Negative                           |
| Status             | Actual                             |
| Milestone          | Not set                           |
| Is flaky           | No                                |
| Pre-condition      | User is registered                  |
| Post-condition     | User stays on login page            |
| **Description**    | Verify error message on invalid login |

## Test Steps

| Step | Action                                            | Expected Result                               |
|-------|-------------------------------------------------|-----------------------------------------------|
| 1     | Navigate to https://automationexercise.com       | Login page is loaded                          |
| 2     | Click on "Signup/Login"                           | Redirected to login form                      |
| 3     | Enter invalid email: `wronguser@example.com`     | Email appears in the field                    |
| 4     | Enter invalid password: `wrongpass123`            | Password is hidden (*******)                  |
| 5     | Click "Submit" button                             | Error message "Invalid email or password" shown |




2. ❌ Negative Test – Checkout without product in cart

| Field             | Value                           |
|------------------|----------------------------------|
| Suite            | Negative Test Case              |
| Severity         | Medium                          |
| Priority         | Medium                          |
| Type             | Negative                        |
| Layer            | E2E                             |
| Automation status| Manual                          |
| Behavior         | Negative                        |
| Status           | Actual                          |
| Pre-condition    | User is logged in               |
| Post-condition   | Checkout is not allowed         |

## 🧪 Test Steps

| Step | Action                                              | Expected Result                               |
|------|-----------------------------------------------------|-----------------------------------------------|
| 1    | Go to https://automationexercise.com                | Home page loads                               |
| 2    | Click on "Signup/Login" and log in                  | User is logged in                             |
| 3    | Click on "Cart"                                     | Cart page is shown (empty)                    |
| 4    | Click "Proceed to Checkout"                         | Error or message: "Cart is empty"             |
