| **Field**             | **Value**                                                                 |
| --------------------- | ------------------------------------------------------------------------- |
| **Title**             | Order Accepted with Invalid Card Number                                   |
| **Description**       | The system accepted an order with only 2 digits in the Card Number field. |
| **Severity**          | Critical                                                                  |
| **Priority**          | High                                                                      |
| **Status**            | Actual                                                                    |
| **Behavior**          | Negative                                                                  |
| **Type**              | Validation                                                                |
| **Layer**             | E2E                                                                       |
| **Automation status** | Manual                                                                    |
| **Is flaky**          | No                                                                        |
| **Milestone**         | Not set                                                                   |


📌 Pre-conditions
User is on the Payment page.

Product has been added to the cart.

User is logged in.

| **Step** | **Action**                                         | **Expected Result**                              |
| -------: | -------------------------------------------------- | ------------------------------------------------ |
|        1 | Navigate to `https://automationexercise.com`       | Home page is loaded                              |
|        2 | Login with valid credentials                       | User is logged in                                |
|        3 | Add a product to the cart                          | Product is added successfully                    |
|        4 | Click “Proceed to checkout”                        | Checkout page is displayed                       |
|        5 | Enter only **2 digits** in the “Card Number” field | Input is accepted                                |
|        6 | Click “Pay and Confirm Order”                      | ❌ **Order is accepted with invalid card number** |



❗ Actual Result
The system accepts the order even though the card number only contains 2 digits.

✅ Expected Result
Error message should appear:
“Invalid card number, please enter valid Card Number.”

Attachments: ![Екранна снимка 2025-06-15 170254](https://github.com/user-attachments/assets/bc4cfb79-c271-412a-9568-9c16f4156adc)

![Екранна снимка 2025-06-15 170306](https://github.com/user-attachments/assets/174caadd-aa78-4eaa-876e-5a827ce96323)
