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
