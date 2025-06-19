### 🐞 Bug Report

| Field             | Value                                                                 |
|------------------|-----------------------------------------------------------------------|
| **Summary**       | The order was accepted with invalid credit card data *(Integration level)* |
| **Description**   | The order was successful with fake credit card data, the issue was found in integration level. |
| **Severity**      | Critical                                                              |
| **Environment**   | https://automationexercise.com, Browser: Chrome 137.0.7151.56 (64-bit) |

---

### ✅ Steps to Reproduce

1. Navigate to https://automationexercise.com/  
2. Enter valid credentials  
3. Add product to cart  
4. Click "Proceed to Checkout"  
5. Enter **invalid** credit card data in the fields  
6. Click "Pay and Confirm order"  

---

### ❗ Actual Result

The order is successful.

---

### ✅ Expected Result

Error message is displayed:  
> `"Invalid credit card, please enter valid credit card"`

