# Manual Test Cases – Add to Cart Functionality

This document contains manual test cases for adding items to the shopping cart on [https://automationexercise.com](https://automationexercise.com).

| Test Case ID | Title                            | Steps to Reproduce                                                                                     | Expected Result                                            | Status     |
|--------------|----------------------------------|---------------------------------------------------------------------------------------------------------|------------------------------------------------------------|------------|
| TC009        | Add single item to cart          | 1. Navigate to homepage. <br> 2. Hover over an item. <br> 3. Click 'Add to Cart'. <br> 4. Click 'View Cart'. | Item is visible in the cart with correct name and quantity. | Pass |
| TC010        | Add multiple different items     | 1. Add one item to cart. <br> 2. Return to homepage. <br> 3. Add another different item. <br> 4. View cart. | Both items appear in the cart.                            | Pass |
| TC011        | Add same item multiple times     | 1. Add the same item to cart twice. <br> 2. View cart.                                                   | Quantity increases; not duplicated as separate items.       | Pass |
| TC012        | Remove item from cart            | 1. Add an item to cart. <br> 2. View cart. <br> 3. Click delete/remove icon.                             | Item is removed from the cart.                             | Pass |
| TC013        | Cart persists after page refresh | 1. Add item to cart. <br> 2. Refresh the cart or homepage.                                               | Cart retains added items.                                  | Pass |
