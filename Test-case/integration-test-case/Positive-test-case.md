1. ✅ Test Case: Registration with valid credentials

| Field              | Value                                           |
|--------------------|--------------------------------------------------|
| **Title**          | Registration with valid credentials.            |
| **Status**         | Actual                                           |
| **Description**    | 🎯 Successful registration with valid credentials. |
| **Suite**          | Integration-Test-Case                           |
| **Severity**       | Major 🟠                                         |
| **Priority**       | Medium 🟡                                        |
| **Type**           | Integration 🔗                                  |
| **Layer**          | E2E 🌐                                           |
| **Is flaky**       | No                                               |
| **Behavior**       | Positive ✅                                      |
| **Automation**     | Manual                                           |
| **Pre-conditions** | The user is on the register form.               |
| **Post-conditions**| The user is registered in the system with valid credentials. |
| **Milestone**      | Not set                                          |

---

## 📝 Steps to Reproduce

| Step | Action                                  | Data / Expected Result                         |
|------|-----------------------------------------|------------------------------------------------|
| 1️⃣  | Navigate to [https://automationexercise.com/signup](https://automationexercise.com/signup) | Home page is loaded                            |
| 2️⃣  | Open registration page                  | Registration page is displayed                 |
| 3️⃣  | Enter a name in the field               | `Daniel Batkov` appears in the name field      |
| 4️⃣  | Enter email address                     | `mariomladenov19023@abv.bg` appears in the field |
| 5️⃣  | Click "Signup" button                   | ✅ The user registered successfully             |

2. ✅ Test Case
   
| **Title**             | Login with valid credentials                       |
|-----------------------|----------------------------------------------------|
| **Description**       | The user is successfully logged in with valid credentials |
| **Type**              | Integration                                        |
| **Layer**             | E2E                                                |
| **Severity**          | Major                                              |
| **Priority**          | Medium                                             |
| **Automation status** | Manual                                             |
| **Behavior**          | Positive                                           |
| **Status**            | Actual                                             |
| **Pre-condition**     | The user is on the login page                      |
| **Post-condition**    | The user is logged in and redirected to homepage   |

### Test Steps

| **Step** | **Action**                             | **Expected Result**                                 |
|--------:|------------------------------------------|-----------------------------------------------------|
| 1       | Navigate to https://automationexercise.com/login | Login page is displayed                             |
| 2       | Enter valid email in the field           | Email is entered correctly                          |
| 3       | Enter valid password in the field        | Password is hidden (******)                         |
| 4       | Click the "Login" button                 | User is logged in and sees "Logged in as [User]"    |




| 🧾 **Title**             | ✅ Order with valid credit card                                  |
|--------------------------|------------------------------------------------------------------|
| 📝 **Description**       | Successful order with valid credit card                          |
| 📁 **Suite**             | Integration Test Case                                            |
| 🚨 **Severity**          | Major                                                            |
| ⏫ **Priority**          | High                                                             |
| 🔄 **Type**              | Integration                                                      |
| 🧩 **Layer**             | E2E                                                              |
| 🧪 **Automation status** | Manual                                                           |
| 🔍 **Status**            | Actual                                                           |
| ✔️ **Behavior**          | Positive                                                         |
| 📌 **Pre-condition**     | The user is on the order page                                    |
| ✅ **Post-condition**    | The order is placed successfully                                 |

---

### 🧪 Test Steps

| 🔢 **Step** | 🧭 **Action**                                           | 🎯 **Expected Result**                            |
|------------|---------------------------------------------------------|--------------------------------------------------|
| 1️⃣         | Navigate to [https://automationexercise.com](https://automationexercise.com) | Home page is loaded                              |
| 2️⃣         | Enter valid credentials                                | User is logged in                                |
| 3️⃣         | Add product to the cart                                | Product is added to the cart                     |
| 4️⃣         | Click "Proceed to Checkout"                            | Checkout page is displayed                       |
| 5️⃣         | Enter valid credit card data                           | Valid data is entered and accepted               |
| 6️⃣         | Click "Pay and Confirm order"                          | ✅ The order has been placed successfully         |


| 🧾 **Title**             | 🛒 Add product to the cart                            |
|--------------------------|--------------------------------------------------------|
| 📝 **Description**       | The user successfully added product to the cart       |
| 📁 **Suite**             | Integration Test Case                                 |
| 🚨 **Severity**          | Normal                                                 |
| ⏫ **Priority**          | Medium                                                 |
| 🔄 **Type**              | Integration                                            |
| 🧩 **Layer**             | E2E                                                    |
| 🧪 **Automation status** | Manual                                                 |
| 🔍 **Status**            | Actual                                                 |
| ✅ **Behavior**          | Positive                                               |
| 📌 **Pre-condition**     | The user is on the product page                        |
| 🏁 **Post-condition**    | The product is successfully added to the cart          |

---

### 🧪 Test Steps

| 🔢 **Step** | 🧭 **Action**                                       | 🎯 **Expected Result**                       |
|------------|-----------------------------------------------------|---------------------------------------------|
| 1️⃣         | Navigate to [https://automationexercise.com](https://automationexercise.com) | Home page is loaded                         |
| 2️⃣         | Log in with valid credentials                      | User is logged in                           |
| 3️⃣         | Add product to the cart                            | Product is added to the cart                |
| 4️⃣         | Click "Cart" from the top menu                     | User sees product listed in the cart        |





## ✅ Integration Test – Login, Add Product & Checkout with Valid Credit Card

| **Field**             | **Value**                                                |
|----------------------|-----------------------------------------------------------|
| **Title**             | Login with valid credentials, Add product to the cart, Checkout with valid credit card data. |
| **Status**            | Actual                                                    |
| **Description**       | The user is logged in, adds product to the cart successfully and completes payment with valid credit card. |
| **Suite**             | Integration-Test-Case                                     |
| **Severity**          | Critical                                                  |
| **Priority**          | High                                                      |
| **Type**              | Integration                                               |
| **Layer**             | E2E                                                       |
| **Automation status** | Manual                                                    |
| **Behavior**          | Positive 😊                                               |
| **Is flaky**          | No                                                        |
| **Pre-condition**     | The user is on the home page.                             |
| **Post-condition**    | All steps are accepted successfully.                      |

---

### 🧪 Test Steps

| **Step** | **Action**                                      | **Expected Result**                          |
|--------:|--------------------------------------------------|----------------------------------------------|
| 1       | Navigate to [https://automationexercise.com](https://automationexercise.com) | Home page is loaded                          |
| 2       | Enter valid email address: `mariomladenov1212@gmail.bg` | Text appears in the field                    |
| 3       | Enter valid password: `Mariomladenov123`         | Password is hidden (`******`)                |
| 4       | Click "Login"                                    | Redirected to the dashboard                  |
| 5       | Add product to the cart                          | Product is added to the cart                 |
| 6       | Click "Cart" in the top menu                     | The user sees the product in the cart        |
| 7       | Click "Proceed to Checkout"                      | Checkout page is displayed                   |
| 8       | Enter valid credit card data in the fields       | The data appears in the fields               |
| 9       | Click "Checkout and Confirm Order"               | Message is shown: _"Order has been placed successfully!"_ |

---



