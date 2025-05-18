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
