# Test Case 1 : Successfully submit message via Contact Us

- **Suite:** Contact Us Form  
- **Severity:** Normal  
- **Priority:** Medium  
- **Type:** Functional  
- **Layer:** E2E  
- **Is Flaky:** No  
- **Behavior:** Positive  
- **Automation Status:** Manual  
- **Description:** Verify that user can successfully submit a message through the Contact Us form  
- **Preconditions:** The user is on the homepage  
- **Postconditions:** Message is successfully sent and confirmation is displayed  

| Step | Action                    | Data                    | Expected Result                            |
|-------|--------------------------|-------------------------|--------------------------------------------|
| 1     | Open "Contact us" page    | -                       | The form is loaded correctly               |
| 2     | Enter username            | Ivan Petkov             | Text is successfully entered in the field |
| 3     | Enter E-mail              | ivanpetkov2025@mail.com | E-mail is accepted                         |
| 4     | Enter message             | "I want to contact you" | Text appears in the message field          |
| 5     | Click on "Submit" button  | -                       | The system sends a request                 |
| 6     | Confirm success message   | -                       | "Message sent successfully" is displayed   |




# Test Case 2 : Search functionality in the product list

- **Suite:** Product Search  
- **Severity:** Normal  
- **Priority:** Medium  
- **Type:** Functional  
- **Layer:** E2E  
- **Is Flaky:** No  
- **Behavior:** Positive  
- **Automation Status:** Manual  
- **Description:** Verify that the search field on the product page works correctly  
- **Preconditions:** The user is on the product page  
- **Postconditions:** Search results or full product list are displayed accordingly  

| Step | Action                       | Data            | Expected Result                           |
|-------|-----------------------------|-----------------|-------------------------------------------|
| 1     | Make sure that "Search" field is visible | -               | The search field is active and visible    |
| 2     | Enter product for search     | PlayStation 5   | The product is visible and loaded         |
| 3     | Click the Enter button       | -               | The list of products matching the search is visible |
| 4     | Clear the search field       | -               | All products are visible and loaded again |


# ✅ Test Case 3 : Add Product to Cart

- **Suite:** Product Tests  
- **Severity:** Medium  
- **Priority:** High  
- **Type:** Functional  
- **Layer:** E2E  
- **Is Flaky:** No  
- **Behavior:** Positive  
- **Automation Status:** Manual  

---

### ✅ Preconditions:
The user is logged in and on the product page.

---

### 🧪 Steps:

**1.**  
**Action:** Choose a product from the list  
**Data:** Amazon.com  
**Expected Result:** Product page is loaded

---

**2.**  
**Action:** Click the "Add to cart" button  
**Expected Result:** Message "Product added" is shown

---

**3.**  
**Action:** Click the cart icon  
**Expected Result:** Product is visible in the cart

---

**4.**  
**Action:** Check the quantity  
**Expected Result:** Default quantity is "1"

---

### 🟩 Postconditions:
Product is successfully added and visible in the cart.
