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


 🔁 Test Case 2 : Forgot Password with Valid Email

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
