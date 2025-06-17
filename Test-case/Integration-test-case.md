🧪 Test Case: Order with invalid credit card data
Status: Actual
Suite: Integration Test Case
Severity: Major
Priority: Medium
Type: Integration
Layer: E2E
Behavior: Negative
Automation Status: Manual

Pre-condition:
The user is on the checkout page.

Post-condition:
The order is blocked.


| **Step** | **Action**                                                                   | **Expected Result**                            |
| -------: | ---------------------------------------------------------------------------- | ---------------------------------------------- |
|        1 | Navigate to [https://automationexercise.com](https://automationexercise.com) | Home page is loaded                            |
|        2 | Enter valid credentials                                                      | User is logged in                              |
|        3 | Add product in the cart                                                      | The product is shown in the cart               |
|        4 | Click "Proceed to Checkout"                                                  | Checkout page is displayed                     |
|        5 | Enter invalid credit card data in the fields                                 | Three errors appear: "Please enter valid data" |
|        6 | Click "Pay and Confirm Order"                                                | Nothing happens                                |
