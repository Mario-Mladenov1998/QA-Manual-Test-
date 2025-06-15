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


3.❌ Regression Test – Submit contact form with empty required fields

| **Title**             | Submit Contact Form Without Data                      |
|----------------------|--------------------------------------------------------|
| **Description**       | Unsuccessful Contact form with empty required fields  |
| **Type**              | Regression                                             |
| **Layer**             | E2E                                                    |
| **Severity**          | Minor                                                  |
| **Priority**          | Medium                                                 |
| **Automation status** | Manual                                                 |
| **Behavior**          | Negative                                               |
| **Status**            | Actual                                                 |
| **Pre-condition**     | User is on the "Contact Us" page                       |
| **Post-condition**    | Form is not submitted, error message is shown          |

### Test Steps

| **Step** | **Action**                                | **Expected Result**                             |
|---------:|--------------------------------------------|-------------------------------------------------|
| 1        | Navigate to https://automationexercise.com | Home page is loaded                             |
| 2        | Click on "Contact Us"                      | "Contact Us" page is displayed                   |
| 3        | Click on "Submit" button without data      | Error message appears: required fields missing  |



4. ❌ Regression Test with existing email

   
| **Title**             | Unsuccessful Signup With Existing Email              |
|----------------------|-------------------------------------------------------|
| **Description**       | User cannot sign up using an email that is already registered |
| **Type**              | Regression                                            |
| **Layer**             | E2E                                                   |
| **Severity**          | Major                                                 |
| **Priority**          | High                                                  |
| **Automation status** | Manual                                                |
| **Behavior**          | Negative                                              |
| **Status**            | Actual                                                |
| **Pre-condition**     | Email already registered in the system                |
| **Post-condition**    | User is not signed up and sees an error message       |

### Test Steps

| **Step** | **Action**                                         | **Expected Result**                                      |
|---------:|-----------------------------------------------------|----------------------------------------------------------|
| 1        | Navigate to https://automationexercise.com          | Home page is loaded                                      |
| 2        | Click on "Signup/Login"                             | Signup/Login page is displayed                           |
| 3        | Enter a name and an email that is already registered | Input is accepted                                        |
| 4        | Click "Signup"                                      | Error message shown: "Email Address already exists!"     |



 | **Title**             | Unsuccessful Order With Expired Credit Card             |
| --------------------- | ------------------------------------------------------- |
| **Description**       | User is able to complete order using expired card (BUG) |
| **Type**              | Regression                                              |
| **Layer**             | E2E                                                     |
| **Severity**          | Critical                                                |
| **Priority**          | High                                                    |
| **Automation status** | Manual                                                  |
| **Behavior**          | Negative                                                |
| **Status**            | Actual                                                  |
| **Pre-condition**     | User is on the payment page                             |
| **Post-condition**    | Order is wrongly marked as successful                   |



| **Step** | **Action**                                                                   | **Expected Result**                               |
| -------: | ---------------------------------------------------------------------------- | ------------------------------------------------- |
|        1 | Navigate to [https://automationexercise.com](https://automationexercise.com) | Home page is loaded                               |
|        2 | Login with valid credentials                                                 | User is logged in                                 |
|        3 | Add any product to the cart                                                  | Product is added                                  |
|        4 | Click on "Cart" and proceed to checkout                                      | Checkout page is displayed                        |
|        5 | Enter expired date in the "Expiration" field                                 | Expired date is accepted                          |
|        6 | Click "Pay and Confirm Order"                                                | ❌ Order goes through, but should show error (BUG) |

