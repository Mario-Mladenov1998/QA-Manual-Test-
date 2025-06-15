| **Title**       | Order is completed with expired credit card                      |
| --------------- | ---------------------------------------------------------------- |
| **Environment** | [https://automationexercise.com](https://automationexercise.com) |
| **Severity**    | Critical                                                         |
| **Priority**    | High                                                             |
| **Status**      | Open                                                             |
| **Reported by** | *\[Your Name]*                                                   |
| **Date**        | *\[Insert Date]*                                                 |


📝 Description
The system allows the user to successfully place an order using an expired credit card, which is a serious validation issue.

✅ Preconditions
User is logged in

User is on the Payment page

Website is accessible

🔁 Steps to Reproduce
Navigate to https://automationexercise.com

Login with valid credentials

Add any product to the cart

Click on Cart and proceed to Checkout

Fill in all required fields

In the "Expiration" field, enter an expired date

Click Pay and Confirm Order

❗️Actual Result
✅ Order is completed successfully with invalid (expired) card data.

✔️Expected Result
❌ Error message should be shown:
"Invalid expiration date. Please use a valid card."
The order must not be processed.

📎 Attachments: ![Екранна снимка 2025-06-15 152156](https://github.com/user-attachments/assets/bceb7a38![Екранна снимка 2025-06-15 152220](https://github.com/user-attachments/assets/47b3026b-ba14-48ea-ac65-701225935522)
-7239-456a-9c86-96da2b22dd6e)
