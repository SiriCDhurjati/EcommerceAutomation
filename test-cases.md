# Functional Test Cases

| ID | Scenario | Steps | Expected Result |
|---|---|---|---|
| TC01 | Valid login | Enter valid username/password and submit | User is logged in successfully |
| TC02 | Invalid login | Enter invalid credentials and submit | Clear error message is displayed |
| TC03 | Product search | Search for an available product | Relevant products are returned |
| TC04 | Add to basket | Open a product and add it to basket | Basket count and item details update |
| TC05 | Basket quantity | Change item quantity | Quantity and total price recalculate |
| TC06 | Remove item | Remove product from basket | Product disappears and total updates |
| TC07 | Empty checkout | Attempt checkout with empty basket | Checkout is prevented with guidance |
| TC08 | Required fields | Leave mandatory checkout fields blank | Validation messages are displayed |

## Suggested regression scope
Login, search, basket, checkout validation and key navigation should be included in every regression cycle.