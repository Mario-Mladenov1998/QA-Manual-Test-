# Test Case: Registration with special characters in the name

| Field            | Value                                                                 |
|------------------|-----------------------------------------------------------------------|
| **Suite**        | Edge test cases                                                       |
| **Severity**     | Critical                                                              |
| **Priority**     | High                                                                  |
| **Type**         | Regression                                                            |
| **Layer**        | E2E                                                                   |
| **Behavior**     | Negative                                                              |
| **Automation**   | Manual                                                                |
| **Description**  | User unsuccessfully tries to register with special characters in the name field. |
| **Preconditions**| The user is on the registration page.                                 |
| **Postconditions** | Error message: `Name is invalid, please remove special characters.` |

---

## Test Steps

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Navigate to [https://automationexercise.com/signup](https://automationexercise.com/signup) | Home page is loaded. |
| 2 | Click "Signup/Login" in the top menu | "Signup/Login" page is displayed. |
| 3 | Enter invalid name with `@#!%^&` | Name appears in the field. |
| 4 | Enter valid email address | Email address is correctly entered. |
| 5 | Enter valid password | Password is accepted. |
| 6 | Click "Signup" button | Error message is shown: `Name is invalid, please remove special characters.` |

