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


