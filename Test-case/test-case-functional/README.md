# Test Case - Search product by name

| Field              | Value                                                                 |
|--------------------|-----------------------------------------------------------------------|
| **Title**          | Search product by name.                                               |
| **Status**         | Actual                                                               |
| **Description**    | The user searches products with keywords in the search field.         |
| **Suite**          | Search test cases (14)                                               |
| **Severity**       | Critical (2)                                                         |
| **Priority**       | High (1)                                                             |
| **Type**           | Functional (8)                                                       |
| **Layer**          | E2E (1)                                                              |
| **Is flaky**       | No (0)                                                               |
| **Milestone**      | Not set                                                              |
| **Behavior**       | Positive (2)                                                         |
| **Automation**     | Manual (0) - To be automated                                         |
| **Muted case**     | No                                                                   |
| **Pre-conditions** | User is on the home page.                                            |
| **Post-conditions**| User sees all matching products in the product page.                 |

---

## Test Steps

| Step | Action                                                                 | Test Data | Expected Result                                  |
|------|------------------------------------------------------------------------|------------|------------------------------------------------|
| 1    | Navigate to [https://automationexercise.com](https://automationexercise.com) | N/A        | Home page is loaded.                           |
| 2    | Enter valid credentials                                                | N/A        | The user is logged in.                         |
| 3    | Click "Products"                                                       | N/A        | Products page is displayed.                    |
| 4    | Enter product name in search field                                     | Example: *T-shirt* | All matching products are shown on product page. |





# 🧪 QA Test Case & Bug Report (NDA Compliant)

> ⚠️ All names, URLs, and build identifiers are removed in compliance with NDA.  
> Example based on a uTest Academy practice cycle.

---

## ✅ Test Case – Verify Language Switch to French

| **Test Case ID** | TC_FUNC_001 |
|------------------|-------------|
| **Title** | Verify that switching the language to French updates all UI elements |
| **Preconditions** | App or site is open; user is logged in if required |
| **Test Steps** | 1. Open the app/site and go to the "Collections" page.<br>2. Open the language selector in the top navigation.<br>3. Select "French".<br>4. Check all menu items, buttons, and labels on the page. |
| **Expected Result** | All UI elements, including the top navigation, are displayed in French. |
| **Actual Result** | The top navigation remains in English while the rest of the interface changes to French. |
| **Severity** | Medium |
| **Priority** | High |
| **Type** | Functional |
| **Status** | Failed |
| **Device / OS** | Samsung Galaxy A52 / Android 13 |
| **Notes** | Functional issue in the language switch logic. Anonymized; no client data shared (NDA). |

---

## 🐞 Bug Report – Language Switch Does Not Fully Apply

| **Bug ID** | BUG_FUNC_001 |
|-------------|---------------|
| **Title** | Collections Page – Language switch does not update lower navigation menu |
| **Severity** | Low |
| **Priority** | Medium |
| **Type** | Functional |
| **Environment** | Device: Xiaomi Poco X4 Pro<br>OS: Android 13<br>Browser: Chrome |
| **Steps to Reproduce** | 1. Open the tested site.<br>2. Navigate to "Collections".<br>3. Scroll until "Translate this page (EN, FR)" is visible.<br>4. Tap "FR" to switch the language.<br>5. Observe the lower navigation bar. |
| **Expected Result** | After switching to French, all navigation elements should display in French. |
| **Actual Result** | The lower navigation remains in English while other page sections are translated correctly. |
| **Attachments** | Screenshot (highlighted issue)<br>Screen recording (.mp4, no sound)<br>Console log (.txt) – omitted due to NDA |
| **Bug Status** | Approved (Won’t Fix – low user impact) |
| **TTL Comment** | "Good observation. Clear steps and proper title format." |
| **NDA Note** | Sensitive data (URLs, client, build) removed to comply with NDA policy. |
