1. # Test Case: Login with valid credentials

| Field            | Value |
|------------------|-------|
| **Title**        | Login with valid credentials |
| **Suite**        | Edge test cases |
| **Severity**     | Critical |
| **Priority**     | High |
| **Type**         | Functional |
| **Layer**        | E2E |
| **Behavior**     | Positive |
| **Automation**   | Manual (To be automated) |
| **Pre-condition**| User is on the home page |
| **Post-condition** | User is successfully redirected to the dashboard |

### Steps

| Step | Action | Data | Expected Result |
|------|--------|------|-----------------|
| 1 | Navigate to [https://automationexercise.com/login](https://automationexercise.com/login) | – | Home page is loaded |
| 2 | Click "Signup/Login" in the top menu | – | Login page is displayed |
| 3 | Enter valid email address | Valid email | Email is correctly entered |
| 4 | Enter valid password | Valid password | Password is hidden (****) |
| 5 | Click "Login" button | – | User successfully logged in |




2. # Test Case: Add products in the cart to 100 articles

| Field            | Value |
|------------------|-------|
| **Title**        | Add products in the cart to 100 articles |
| **Suite**        | Edge test cases |
| **Severity**     | Critical |
| **Priority**     | High |
| **Type**         | Functional |
| **Layer**        | E2E |
| **Behavior**     | Positive |
| **Automation**   | Manual (To be automated) |
| **Pre-condition**| User is on the home page |
| **Post-condition** | User sees 100 products in the cart, with quantity and total price |

### Steps

| Step | Action | Data | Expected Result |
|------|--------|------|-----------------|
| 1 | Navigate to [https://automationexercise.com](https://automationexercise.com) | – | Home page is loaded |
| 2 | Enter valid email address | Valid email | Email is correctly entered |
| 3 | Enter valid password | Valid password | Password is entered (hidden) |
| 4 | Click "Products" in the top menu | – | "Products" page is displayed |
| 5 | Click "Add to cart" repeatedly until total quantity = 100 | – | 100 products are added in the cart |
| 6 | Click "View cart" | – | User sees 100 products in the cart with correct total price |



3. # Test Case: Order with empty product cart

| Field | Value |
|-------|-------|
| Title | Order with empty the product cart |
| Status | Actual 0 |
| Description | The user places an order with an empty product cart |
| Suite | Edge test cases |
| Severity | Critical |
| Priority | High |
| Type | Regression |
| Layer | E2E |
| Is flaky | No |
| Behavior | Negative |
| Automation status | Manual |
| Pre-conditions | The user is on the home page |
| Post-conditions | User sees: Empty cart! Click here to buy products |

## Test Case Steps

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Navigate to https://automationexercise.com | Home page is loaded | Home page is loaded |
| 2 | Enter valid credentials | Credentials are entered correctly | User is logged in |
| 3 | Click "Cart" in the top menu | – | Cart page is displayed |
| 4 | Verify that the cart is empty | – | Cart is empty! Click [here](https://automationexercise.com/products) to buy products |
| 5 | Click "Proceed to checkout" | – | User cannot continue to checkout |
| 6 | Verify no order is placed | – | No order confirmation is displayed |
