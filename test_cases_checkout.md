# Manual Test Cases – Checkout Functionality

This document contains manual test cases for the checkout process on [https://automationexercise.com](https://automationexercise.com).

| Test Case ID | Title                             | Steps to Reproduce                                                                                       | Expected Result                                            | Status     |
|--------------|-----------------------------------|-----------------------------------------------------------------------------------------------------------|------------------------------------------------------------|------------|
| TC014        | Successful checkout               | 1. Add item to cart. <br> 2. View cart. <br> 3. Click 'Proceed to Checkout'. <br> 4. Enter valid details and place order. | Confirmation page is shown with order summary.            | Pass |
| TC015        | Checkout with empty cart          | 1. Navigate to checkout page without adding items.                                                        | User is notified cart is empty or cannot proceed.          | Pass|
| TC016        | Checkout without logging in       | 1. Add item to cart. <br> 2. Try to checkout without being logged in.                                     | User is redirected to login or signup page.               | Pass |
| TC017        | Invalid payment details           | 1. Add item to card. <br> 2. Try to check out using invalid payment details.                              | User is notified that the payment details are invalid and prompted to re-enter. | Fail |
