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




