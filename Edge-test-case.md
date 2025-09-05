# Test Case: Registration with special characters in the name

**Suite:** Edge test cases  
**Severity:** Critical  
**Priority:** High  
**Type:** Regression  
**Layer:** E2E  
**Behavior:** Negative  
**Automation status:** Manual  

---

## Description
User unsuccessfully tries to register with special characters in the name field.  

---

## Preconditions
- The user is on the registration page.  

## Postconditions
- Error message is shown: `Name is invalid, please remove special characters.`  

---

## Test Steps

1. **Navigate** to [https://automationexercise.com/signup](https://automationexercise.com/signup)  
   - *Expected Result:* Home page is loaded.  

2. **Click** "Signup/Login" in the top menu  
   - *Expected Result:* "Signup/Login" page is displayed.  

3. **Enter** invalid name with `@#!%^&`  
   - *Expected Result:* Name appears in the field.  

4. **Enter** valid email address  
   - *Expected Result:* Email address is correctly entered.  

5. **Enter** valid password  
   - *Expected Result:* Password is accepted.  

6. **Click** "Signup" button  
   - *Expected Result:* Error message is shown:  
     ```
     Name is invalid, please remove special characters.
     ```  

---
