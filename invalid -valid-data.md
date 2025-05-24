# ❌ Test Case 1 : Login with Invalid Password

- **Suite:** Login Tests  
- **Severity:** High  
- **Priority:** Medium  
- **Type:** Functional  
- **Layer:** E2E  
- **Is Flaky:** No  
- **Behavior:** Negative  
- **Automation Status:** Manual  

---

### ❗ Preconditions:
User is on the login page.

---

### 🧪 Test Steps

| Step | Action                        | Data              | Expected Result                                      |
|------|-------------------------------|-------------------|------------------------------------------------------|
| 1    | Enter username in the field   | Alexander         | Username is entered in the field                     |
| 2    | Enter password in the field   | WrongPassword123  | Password is entered, not visible                     |
| 3    | Click the Login button        | -                 | Error message "Invalid username or password" appears |

---

### 🔁 Postconditions:
The user stays on the login page. Login is not successful.


 # 🔁 Test Case 2 : Forgot Password with Valid Email

- **Suite:** Password Recovery  
- **Severity:** Medium  
- **Priority:** High  
- **Type:** Functional  
- **Layer:** E2E  
- **Is Flaky:** No  
- **Behavior:** Positive  
- **Automation Status:** Manual  

---

### ❗ Preconditions:
User is on the **Forgot Password** page.

### ✅ Postconditions:
User successfully initiates password reset.

---

### 🧪 Test Steps

| Step | Action                       | Data                | Expected Result                                |
|------|------------------------------|---------------------|------------------------------------------------|
| 1    | Navigate to facebook.com     | facebook.com        | The page is loaded                             |
| 2    | Click on the password field  | database123!        | Text is entered but not visible                |
| 3    | Type the user email          | Email123@mail.com   | The text appears in the email field            |
| 4    | Click "Send reset link"      | -                   | Message appears: "Password reset link sent"    |


# 🛑 Test Case 3 : Registration with Invalid Email

- **Suite:** Registration  
- **Severity:** High  
- **Priority:** Medium  
- **Type:** Functional  
- **Layer:** E2E  
- **Is Flaky:** No  
- **Behavior:** Negative  
- **Automation Status:** Manual  

---

### ❗ Preconditions:
The user is on the **registration** page.

### ✅ Postconditions:
The user remains on the registration page, form is not submitted.

---

### 🧪 Test Steps

| Step | Action                         | Data                        | Expected Result                                       |
|------|--------------------------------|-----------------------------|--------------------------------------------------------|
| 1    | Open the registration page     | -                           | The form is loaded                                    |
| 2    | Enter invalid email            | donaldtrump2025@mail.com    | Error message: "Invalid email format" is shown        |
| 3    | Enter password                 | trumptower2025!@            | Password is entered into the field                    |
| 4    | Click the register button      | -                           | Form is not submitted, error message stays visible    |



# ✅ Test Case 4 : Valid Login

| **Field**           | **Description**                                                                 |
|---------------------|----------------------------------------------------------------------------------|
| **Test Case ID**    | TC-LOGIN-001                                                                     |
| **Title**           | Valid login with registered user                                                 |
| **Priority**        | High                                                                             |
| **Severity**        | Critical                                                                         |
| **Type**            | Positive                                                                         |
| **Preconditions**   | User is already registered with a valid email and password                       |
| **Tested By**       | (your name or leave blank)                                                       |
| **Date Created**    | (e.g. 2025-05-18)                                                                 |

---

## 5. ✅ Test Case: Change password with valid data 

| Step | Action               | Test Data                | Expected Result                                   |
|------|----------------------|--------------------------|---------------------------------------------------|
| 1    | Open login page      | –                        | Login page is loaded successfully                 |
| 2    | Enter email          | example@mail.com         | Email is visible in the email input field         |
| 3    | Enter password       | strongpassword123!@#     | Password is entered (masked as bullets)           |
| 4    | Click "Login" button | –                        | User is logged in and redirected to homepage      |


| Step | Action                         | Data                 | Expected result              |
|-------|-------------------------------|----------------------|-----------------------------|
| 1     | Navigate to the "Change password" page | https://login.yahoo.com/ | Change password page is loaded |
| 2     | Enter current password         | StrongPASS123@       | Password is entered         |
| 3     | Enter new password             | DonaldTrump2025!     | Password is changed         |
| 4     | Confirm new password           | DonladTrump2025!     | Password is entered correctly |
| 5     | Click "Submit" button          |                      | Password successfully changed |




 
 | 6. ❌ **Test Case** | Forgot password with invalid email |
|---------------|------------------------------------|
| **Pre-condition** | User is on the forgot password page |
| **Post-condition** | User is not logged in |
| **Priority** | Medium |
| **Severity** | Medium |
| **Type** | Negative |
| **Module** | Authentication |
| **Tested on** | Chrome / Windows 10 |
| **Test Steps** | **Test Data** | **Expected Result** |
| 1. Navigate to "Forgot password" page | [Yahoo forgot password URL](https://login.yahoo.com/account/challenge/username?lang=bg-BG&src=ym&done=https%3A%2F%2Fmail.yahoo.com%2F%3Fguce_referrer%3DaHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8%26guce_referrer_sig%3DAQAAAB-wE_FYkW17Dz1zORmv4qeCLaMIXuloAGb_Lgo_VlYSKU1BsazEMg8kI-HEgdDeME5mL9iMuheFPlTbPGJdrAl9w8OuXewIEnTPPYfFhwSN80zIfMd4_4pf-G32B7TKPM3ytnsqekoEQmFNSnJkuljiCVVSvpC10OggkD6QLF7x&authMechanism=secondary&sessionIndex=Qw--) | Forgot password page is loaded |
| 2. Enter invalid email | `invalidmail@yahoo.com` | Error message shown: "Invalid password or email" |
| 3. Click "Submit" button | — | Error message shown: "Please, enter a valid email address" |
