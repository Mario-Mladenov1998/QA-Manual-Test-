| **Field**       | **Details**                                                                |
| --------------- | -------------------------------------------------------------------------- |
| **Title**       | Order is accepted with 3-digit card number                                 |
| **Description** | The system allows placing an order using a card number with only 3 digits. |
| **Severity**    | Critical                                                                   |
| **Environment** | Google Chrome Version: 137.0.7151.56 (64-bit)                              |


| **Step** | **Action**                                                                   |
| -------: | ---------------------------------------------------------------------------- |
|        1 | Navigate to [https://automationexercise.com](https://automationexercise.com) |
|        2 | Log in with valid credentials                                                |
|        3 | Add a product to the cart                                                    |
|        4 | Click on “Proceed to checkout”                                               |
|        5 | Enter only **3 digits** in the “Card Number” field                           |
|        6 | Click **“Pay and Confirm Order”**                                            |



❌ Actual Result
Order was successfully placed with invalid (3-digit) card number.

✅ Expected Result
System should display an error message:
"Invalid card number, please enter a valid card number."

Attachments:
![Екранна снимка 2025-06-16 211012](https://github.com/user-attachments/assets/60cf8ba4-397c-4e80-816c-240c9daab47d)

![Екранна снимка 2025-06-16 211021](https://github.com/user-attachments/assets/64100d1f-6135-4a8e-8479-9375e387fc24)

