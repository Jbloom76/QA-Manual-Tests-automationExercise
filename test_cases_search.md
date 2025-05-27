# Manual Test Cases – Product Search Functionality

This document contains manual test cases for product search functionality on [https://automationexercise.com](https://automationexercise.com).

| Test Case ID | Title                        | Steps to Reproduce                                                                 | Expected Result                                  | Status     |
|--------------|------------------------------|-------------------------------------------------------------------------------------|--------------------------------------------------|------------|
| TC005        | Search for existing product  | 1. Go to homepage. <br> 2. Enter 'T-shirt' in the search bar. <br> 3. Click 'Search'. | Results show products with 'T-shirt' in the title or description. | Pass |
| TC006        | Search for non-existent product | 1. Enter 'XYZ123' in the search bar. <br> 2. Click 'Search'. | Message or empty results displayed indicating no products found. | Pass |
| TC007        | Search with blank input      | 1. Leave the search bar empty. <br> 2. Click 'Search'. | Application shows error or no action is taken. | Fail |
| TC008        | Search with special characters | 1. Enter '@@@###' in the search bar. <br> 2. Click 'Search'. | Application handles it gracefully; no crash or unexpected behavior. | Pass |
