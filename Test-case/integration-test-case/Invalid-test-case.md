
| **Field**             | **Value**                                         |
| --------------------- | ------------------------------------------------- |
| **Title**             | Order with invalid credit card data.              |
| **Status**            | Actual                                            |
| **Description**       | The order is not successful in the checkout page. |
| **Suite**             | Integration-Test-Case                             |
| **Severity**          | Major                                             |
| **Priority**          | Medium                                            |
| **Type**              | Integration                                       |
| **Layer**             | E2E                                               |
| **Behavior**          | Negative                                          |
| **Automation Status** | Manual                                            |
| **Is Flaky**          | No                                                |
| **Pre-condition**     | The user is on the checkout page.                 |
| **Post-condition**    | The order is blocked.                             |


| **Step** | **Action**                                                                   | **Expected Result**                                    |
| -------: | ---------------------------------------------------------------------------- | ------------------------------------------------------ |
|        1 | Navigate to [https://automationexercise.com](https://automationexercise.com) | Home page is loaded                                    |
|        2 | Enter valid credentials                                                      | User is logged in                                      |
|        3 | Add product to the cart                                                      | The product is shown in the cart                       |
|        4 | Click "Proceed to Checkout"                                                  | Checkout page is displayed                             |
|        5 | Enter **invalid credit card data** in the fields                             | Errors appear in the fields: "Please enter valid data" |
|        6 | Click "Pay and Confirm Order"                                                | Nothing happens; order is not processed                |


| **Title**             | Registration with Already Existing Email             |
|-----------------------|------------------------------------------------------|
| **Description**       | Unsuccessful registration using an already registered email address |
| **Type**              | Integration                                          |
| **Layer**             | E2E                                                  |
| **Severity**          | Normal                                               |
| **Priority**          | Medium                                               |
| **Automation status** | Manual                                               |
| **Behavior**          | Negative                                             |
| **Status**            | Actual                                               |
| **Pre-condition**     | The user is on the registration form                 |
| **Post-condition**    | Registration is unsuccessful due to already existing email |

### Test Steps

| **Step** | **Action**                                      | **Expected Result**                                      |
|---------:|--------------------------------------------------|----------------------------------------------------------|
| 1        | Navigate to https://automationexercise.com       | Home page is loaded                                      |
| 2        | Open registration page                           | Registration page is displayed                           |
| 3        | Enter a name in the field (e.g., "Mario")        | Text appears in the name field                           |
| 4        | Enter an already registered email address        | Text appears in the email field                          |
| 5        | Click the "Signup" button                        | Error message is shown: "Email Address already exists!"  |



| 🔹 **Title**             | ❌ Login with invalid credentials                                |
|-------------------------|------------------------------------------------------------------|
| 📝 **Description**       | Unsuccessful login with invalid email and password               |
| 📁 **Suite**             | Integration Test Case                                            |
| 🚨 **Severity**          | Major                                                            |
| ⏫ **Priority**          | High                                                             |
| 🔄 **Type**              | Regression                                                       |
| 🧩 **Layer**             | E2E                                                              |
| 🧪 **Automation status** | Manual                                                           |
| 🔍 **Status**            | Actual                                                           |
| ⚠️ **Behavior**          | Negative                                                         |
| 📌 **Pre-condition**     | The user is on the login page                                    |
| ✅ **Post-condition**    | The user sees error message: _"Your email or password is incorrect!"_ |

---

### 🧪 Test Steps

| 🔢 **Step** | 🧭 **Action**                                           | 🎯 **Expected Result**                                               |
|------------|---------------------------------------------------------|----------------------------------------------------------------------|
| 1️⃣         | Navigate to [https://automationexercise.com/login](https://automationexercise.com/login) | Login page is displayed                                              |
| 2️⃣         | Enter invalid email: `mario123@gmail.bg`               | Email appears in the field                                           |
| 3️⃣         | Enter invalid password: `abc`                          | Password is hidden (*****)                                           |
| 4️⃣         | Click the "Login" button                               | ❗ Error message is shown: _"Your email or password is incorrect!"_  |



| 🧾 **Title**             | ❌ Order with invalid credit card                             |
|--------------------------|--------------------------------------------------------------|
| 📝 **Description**       | Order is not accepted with invalid credit card               |
| 📁 **Suite**             | Integration Test Case                                        |
| 🚨 **Severity**          | Major                                                        |
| ⏫ **Priority**          | High                                                         |
| 🔄 **Type**              | Integration                                                  |
| 🧩 **Layer**             | E2E                                                          |
| 🧪 **Automation status** | Manual                                                       |
| 🔍 **Status**            | Actual                                                       |
| ⚠️ **Behavior**          | Negative                                                     |
| 📌 **Pre-condition**     | The user is on the order page                                |
| ✅ **Post-condition**    | The user sees error message: "Order is unsuccessful"         |

---

### 🧪 Test Steps

| 🔢 **Step** | 🧭 **Action**                                      | 🎯 **Expected Result**                      |
|------------|----------------------------------------------------|--------------------------------------------|
| 1️⃣         | Navigate to [https://automationexercise.com](https://automationexercise.com) | Home page is loaded                        |
| 2️⃣         | Log in with valid credentials                      | User is logged in                          |
| 3️⃣         | Add product to the cart                            | Product is added to the cart               |
| 4️⃣         | Click "Proceed to Checkout"                        | Checkout page is displayed                 |
| 5️⃣         | Enter invalid credit card data in the fields       | Invalid data is entered                    |
| 6️⃣         | Click "Pay and Confirm Order"                      | ❌ Error message is shown: "Order is unsuccessful" |



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

