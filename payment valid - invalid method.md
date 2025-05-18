### Test Case ID: TC-PAYMENT-001
| Field             | Description                                      |
|------------------|--------------------------------------------------|
| Title            | Successful payment with valid credit card        |
| Priority         | High                                             |
| Severity         | Critical                                         |
| Type             | Positive                                         |
| Preconditions    | User is logged in and has items in the cart      |

### 🔹 Test Steps

| Step | Action                            | Test Data                        | Expected Result                                      |
|------|-----------------------------------|----------------------------------|------------------------------------------------------|
| 1    | Go to checkout page               | –                                | Checkout page is loaded                             |
| 2    | Enter valid card number           | 12 734 789 982                   | Number is entered successfully                      |
| 3    | Enter expiration date             | 10/29                            | Date is accepted                                    |
| 4    | Enter CVV                         | 898                              | CVV is accepted                                     |
| 5    | Click “Pay” button                | –                                | Payment is successful, user sees confirmation page  |
