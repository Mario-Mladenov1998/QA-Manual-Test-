| **Title**                           | Regression test - Login with valid credentials                        |
|------------------------------------|------------------------------------------------------------------------|
| **Status**                         | Actual                                                                 |
| **Description**                    | This test verifies that a registered user can successfully log in with valid credentials at https://automationexercise.com. |
| **Suite**                          | Regression Test Case                                                   |
| **Severity**                       | Minor                                                                  |
| **Priority**                       | High                                                                   |
| **Type**                           | Regression                                                             |
| **Layer**                          | E2E                                                                    |
| **Is flaky**                       | No                                                                     |
| **Milestone**                      | Not set                                                                |
| **Behavior**                       | Positive                                                               |
| **Automation status**              | Manual                                                                 |
| **To be automated**                | Yes (planned)                                                          |
| **Pre-conditions**                 | Created user in the system                                             |
| **Post-conditions**                | User is successfully logged in and redirected to the home page.       |

### Test Steps

| **Step**                           | **Action**                                                | **Expected Result**                                  |
|------------------------------------|------------------------------------------------------------|------------------------------------------------------|
| 1                                  | Navigate to https://automationexercise.com                 | Login page is loaded                                |
| 2                                  | Click on "Signup/Login"                                   | User is redirected to the login form                |
| 3                                  | Enter valid email: `mariomladenov199@abv.bg`              | Email appears in the field                          |
| 4                                  | Enter valid password: `something1234`                     | Password appears hidden (*******)                   |
| 5                                  | Click "Submit" button                                     | User is logged in and sees "Logged in as Mario"     |
