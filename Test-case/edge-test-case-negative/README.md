1. # Test Case: Registration with special characters in the name

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






2. # Test Case: Login with password of two digits

| **Field**          | **Value**                                                                 |
|---------------------|---------------------------------------------------------------------------|
| **Title**           | Login with password of two digits                                         |
| **Description**     | The user tries to login with a valid email and a 2-digit password.        |
| **Suite**           | Edge test cases                                                           |
| **Severity**        | Critical                                                                  |
| **Priority**        | High                                                                      |
| **Type**            | Functional                                                               |
| **Layer**           | E2E                                                                       |
| **Behavior**        | Negative                                                                  |
| **Automation status** | Manual (To be automated)                                                 |
| **Pre-conditions**  | The user is on the login page.                                            |
| **Post-conditions** | Error message is shown: *Your email or password is incorrect!*            |

---

## Test Steps

| **Step** | **Action**                                      | **Expected Result**                                |
|----------|-------------------------------------------------|---------------------------------------------------|
| 1        | Navigate to [https://automationexercise.com/](https://automationexercise.com/) | Home page is loaded.                              |
| 2        | Click **"Signup/Login"** in the top menu        | Login page is displayed.                          |
| 3        | Enter a valid email address                     | Email is entered correctly.                       |
| 4        | Enter invalid 2-digit password                  | Password is entered (hidden).                     |
| 5        | Click **"Login"** button                        | Error message: *Your email or password is incorrect!* |






3.# Test Case: Login with invalid email (missing "@")

| **Field**          | **Value**                                                                 |
|---------------------|---------------------------------------------------------------------------|
| **Title**           | Login with invalid email (missing "@")                                    |
| **Description**     | The user tries to login with an invalid email address (missing "@").      |
| **Suite**           | Edge test cases                                                           |
| **Severity**        | Critical                                                                  |
| **Priority**        | High                                                                      |
| **Type**            | Functional                                                               |
| **Layer**           | E2E                                                                       |
| **Behavior**        | Negative                                                                  |
| **Automation status** | Manual (To be automated)                                                 |
| **Pre-conditions**  | The user is on the login page.                                            |
| **Post-conditions** | User is not logged in. Error message is shown: *Your email or password is incorrect!* |

---

## Test Steps

| **Step** | **Action**                                   | **Input Data**         | **Expected Result**                                |
|----------|-----------------------------------------------|------------------------|---------------------------------------------------|
| 1        | Navigate to [https://automationexercise.com/login](https://automationexercise.com/login) | –                      | Home page is loaded.                              |
| 2        | Click **"Signup/Login"** in the top menu     | –                      | Login page is displayed.                          |
| 3        | Enter invalid email address                  | `donaldtrump2025.gmail` | Email is entered in the field.                    |
| 4        | Enter valid password                         | valid_password123      | Password is entered correctly (hidden).           |
| 5        | Click **"Login"** button                     | –                      | Error message is shown: *Your email or password is incorrect!* |


