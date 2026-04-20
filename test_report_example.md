# ⭐ Product Rating System

---

## 📌 Scenario 1: Give Minimum Rating (1 Star)

**User Story:**  
As a user of GroceryMate, I am able to give a product a rating of **1 star**.

---

### Test Steps

| Step # | Action | Expected Outcome | Status | URL | Issue |
|--------|--------|-----------------|--------|------|--------|
| 1 | Go to the login page of GroceryMate | Login page appears | OK | https://grocerymate.masterschool.com/ | |
| 2a | Enter username: `asdf@example.com` | Username accepted | OK | | |
| 2b | Enter password: `AsDfGh` | Password accepted | OK | | |
| 3 | Click **Sign In** | User is successfully logged in and redirected to homepage | OK | | |
| 4 | Click **Shop** button | Navigated to store page | OK | `/store` | |
| 5 | Select **Pears** → Click **Add to Cart** | Message displayed: *Item added to cart* | OK | | |
| 6 | Click cart icon | Navigated to checkout page | OK | `/checkout` | |
| 7a | Enter street: `ABC` | Field accepted | OK | | |
| 7b | Enter city: `Berlin` | Field accepted | OK | | |
| 7c | Enter postal code: `12345` | Field accepted | OK | | |
| 7d | Enter card number: `12345` | Field accepted | OK | | |
| 7e | Enter name on card: `Abc` | Field accepted | OK | | |
| 7f | Enter expiration date: `12/2032` | Field accepted | OK | | |
| 7g | Enter CVV: `123` | Field accepted | OK | | |
| 8 | Click **Buy Now** | Redirected to homepage | OK | | |
| 9 | Click **Shop** button | Redirected to store page | OK | `/store` | |
| 10 | Click **Pears** | Redirected to product page | OK | https://grocerymate.masterschool.com/product/66b3a57b3fd5048eacb47990 | |
| 11 | Select **1 Star rating** | 1 star is highlighted | OK | | |
| 12 | Click **Send** button | Rating visible & message displayed: *You already reviewed this product* | OK | `/store` | |

---

### 📷 Evidence Screenshot

![Product rated to 1](https://github.com/user-attachments/assets/c94bf50c-5b01-4c2a-9d5a-aa7223c9cdcd)

---

---
