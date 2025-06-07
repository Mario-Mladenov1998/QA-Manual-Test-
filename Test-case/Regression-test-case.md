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








# 2. ✅ Regression Test - Add product to cart and verify

## 📌 Description
The product must be added successfully: [View Cart](https://automationexercise.com/view_cart)

## 🧩 Metadata

| Field              | Value                       |
|--------------------|-----------------------------|
| Suite              | Regression Test Case        |
| Severity           | Critical                    |
| Priority           | High                        |
| Type               | Regression                  |
| Layer              | E2E                         |
| Automation status  | Manual                      |
| Behavior           | Positive                    |
| Status             | Actual                      |
| Milestone          | Not set                     |
| Is flaky           | No                          |
| Pre-condition      | User is logged in           |
| Post-condition     | Product appears in the cart |

## 🧪 Test Steps

| Step | Action                                                            | Expected Result                                |
|------|-------------------------------------------------------------------|------------------------------------------------|
| 1    | Navigate to [automationexercise.com](https://automationexercise.com) | Home page is loaded                            |
| 2    | Enter valid email: `mariomladenov1920@abv.bg`                    | Text appears in the field                      |
| 3    | Enter valid password: `Mariomladenov1234`                        | Password is hidden (********)                 |
| 4    | Click "Signup/Login" and log in                                  | User is redirected to homepage and logged in   |
| 5    | Go to "Products" page                                             | Products page is displayed                     |
| 6    | Click "Add to cart" on any product                               | Product is added to cart                       |
| 7    | Click "Cart" in the top navigation bar                           | Cart page shows the product and correct price  |




# 3.✅ Regression Test – Search for a product and verify results

## 📌 Description
Verify that the search functionality returns relevant products based on the entered keyword.

## 🧩 Metadata

| Field              | Value                       |
|--------------------|-----------------------------|
| Suite              | Regression Test Case        |
| Severity           | Medium                      |
| Priority           | High                        |
| Type               | Regression                  |
| Layer              | E2E                         |
| Automation status  | Manual                      |
| Behavior           | Positive                    |
| Status             | Actual                      |
| Milestone          | Not set                     |
| Is flaky           | No                          |
| Pre-condition      | User is on the homepage     |
| Post-condition     | Search results are displayed properly |

## 🧪 Test Steps

| Step | Action                                                    | Expected Result                                |
|------|-----------------------------------------------------------|------------------------------------------------|
| 1    | Navigate to [automationexercise.com](https://automationexercise.com) | Home page is loaded                            |
| 2    | Click on “Products” in the top menu                       | Products page is displayed                     |
| 3    | Type `Tshirt` into the search field                       | Text appears in the search input               |
| 4    | Click the search button                                   | Search results are shown                       |
| 5    | Verify that products related to `Tshirt` are displayed    | Relevant products are shown in a grid/list     |





4.✅ Regression E2E Test – Register, Add Product & Complete Order
🧩 Metadata
Field	Value
Suite	Regression Test Case
Severity	Critical
Priority	High
Type	Regression
Layer	E2E
Automation status	Manual
Behavior	Positive
Status	Actual
Milestone	Not set
Is flaky	No
Pre-condition	-
Post-condition	The order is complete


| Step | Action                                    | Expected Result                     |
|-------|-------------------------------------------|------------------------------------|
| 1     | Navigate to https://automationexercise.com | Home page is loaded                 |
| 2     | Click on "Signup/Login"                    | Redirected to Signup/Login form     |
| 3     | Enter name and valid email address         | Fields accept data                  |
| 4     | Click "Signup"                             | Redirected to signup details form  |
| 5     | Fill in all required information and submit | Account is created, redirected to home |
| 6     | Go to "Products"                           | Products page is displayed          |
| 7     | Click "Add to cart" on a product           | Product is added to cart            |
| 8     | Click "Cart"                              | Cart page shows product             |
| 9     | Click "Proceed to checkout"                | Checkout page is shown              |
| 10    | Fill in delivery details and click "Place Order" | Payment page is shown              |
| 11    | Enter credit card details and submit       | Order confirmation message is shown|
