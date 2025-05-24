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




### Test Case ID: TC-PAYMENT-002
| Field             | Description                                      |
|------------------|--------------------------------------------------|
| Title            | Unsuccessful payment with invalid credit card    |
| Priority         | High                                             |
| Severity         | Major                                            |
| Type             | Negative                                         |
| Preconditions    | User is logged in and has items in the cart      |

### 🔹 Test Steps

| Step | Action                            | Test Data                        | Expected Result                                            |
|------|-----------------------------------|----------------------------------|------------------------------------------------------------|
| 1    | Go to checkout page               | –                                | Checkout page is loaded                                   |
| 2    | Enter invalid card number         | 1234 5678 9101 1121              | Error shown: “Invalid card number”                        |
| 3    | Enter invalid expiration date     | 01/20                            | Error shown: “Card expired”                               |
| 4    | Enter invalid CVV                 | 1                                | Error shown: “Invalid CVV”                                |
| 5    | Click “Pay” button                | –                                | Payment fails, message shown: “Payment could not be completed” |





### Test Case ID: TC-CART-002
| Field          | Description                             |
|---------------|-----------------------------------------|
| Title          | Attempt to add out-of-stock product     |
| Priority       | Medium                                  |
| Severity       | Minor                                   |
| Type           | Negative                                |
| Preconditions  | Product is out of stock                 |

### 🔹 Test Steps

| Step | Action                         | Test Data     | Expected Result                |
|------|--------------------------------|---------------|--------------------------------|
| 1    | Go to product page             | –             | Product page is loaded         |
| 2    | Click “Add to Cart” button     | –             | Error shown: Out of stock      |
