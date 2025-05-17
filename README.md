##  Test Case: Login Happy Path (facebook.com)

- **Suite:** Test case without suite  
- **Severity:** Critical  
- **Priority:** High  
- **Type:** Functional  
- **Layer:** E2E  
- **Is Flaky:** Yes  
- **Behavior:** Positive  
- **Automation status:** Manual  
- **Description:** Login functionality on facebook.com/login  
- **Preconditions:** User is already registered  

---

###  Test Steps:

| Step | Action | Data | Expected Result |
|------|--------|------|-----------------|
| 1.1 | Navigate to facebook.com | - | facebook.com homepage is loaded |
| 1.2 | Click on the field "Email or Phone number" | - | The text cursor appears in the field |
| 1.3 | Enter valid email | marioqa@mail.com | The email appears in the field |
| 1.4 | Click on the field "Password" | - | The text cursor appears in the field |
| 1.5 | Type the password | `strongpassword@123!` | The password appears in the field but is not visible (masked) |
| 1.6 | Click the "Login" button | - | The user is redirected to the home page |


Test Case: 2 Registration wtih already used email

- **Suite:** - Test case without suite  
- **Severity:** - Normal
- **Priority:** - Low
- **Type:** - Functional 
- **Layer:** E2E
- **Is Flaky:** - Yes
- **Behavior:** Negative
- **Automation status:** Manual
- **Description:** 
- **Preconditions:** User is on the registration page

- 
- | Step | Action | Data | Expected Result |
- |------|--------|------|-----------------
  
| 1.1  Navigate to instagram.com | - | instagram.com | - | instagram.com is loade | 

| 1.2  Click on the field E-mail or Password | - | The text appears is on the field |

| 1.3 |  Type the user E-mail |  | testcase@mail.com |  | The text appears is on the field |

| 1.4 |  Type the usear Password | | testcase123 |  | The Password is on the field but not is visibe |

| 1.5 |  Click the register button | - | Email is already in use | 
