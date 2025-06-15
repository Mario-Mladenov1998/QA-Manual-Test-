| Field           | Value                                                        |
| --------------- | ------------------------------------------------------------ |
| **Title**       | Order is accepted with invalid card on name (only 2 letters) |
| **Severity**    | Critical                                                     |
| **Status**      | Actual                                                       |
| **Type**        | Regression                                                   |
| **Behavior**    | Negative                                                     |
| **Layer**       | E2E                                                          |
| **Environment** | Google Chrome Version: 137.0.7151.56 (64-bit)                |

📝 Description
The system accepted payment method with an invalid value in the "Card on Name" field – only 2 letters.


| Step | Action                                                                       |
| ---- | ---------------------------------------------------------------------------- |
| 1    | Navigate to [https://automationexercise.com](https://automationexercise.com) |
| 2    | Login with valid credentials                                                 |
| 3    | Add product to the cart                                                      |
| 4    | Click on **"Proceed to Checkout"**                                           |
| 5    | Enter **only 2 letters** in the **"Card on Name"** field                     |
| 6    | Click **"Pay and Confirm Order"**                                            |

❌ Actual Result
The order was accepted even though the name on card was invalid (only 2 letters).

✅ Expected Result
An error message should be shown:
"Invalid card name, please enter valid data"

📸 Attachments: 
![Екранна снимка 2025-06-15 210244](https://github.com/user-attachments/assets/a26b2581-02d3-4c33-a4c3-57c239787a90)

![Екранна снимка 2025-06-15 210318](https://github.com/user-attachments/assets/daa9fe65-46f2-4fef-b4dc-1a2cde5238cb)
