# Manual Test Cases – Contact Form Functionality

This document contains manual test cases for the contact form on [https://automationexercise.com](https://automationexercise.com).

| Test Case ID | Title                           | Steps to Reproduce                                                                                      | Expected Result                                                | Status     |
|--------------|----------------------------------|----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|------------|
| TC019        | Submit with valid details        | 1. Go to 'Contact Us' page. <br> 2. Enter valid name, email, subject, and message. <br> 3. Submit the form. | Confirmation message is displayed.                            | Pass |
| TC020        | Submit with missing fields       | 1. Leave one or more fields blank. <br> 2. Click 'Submit'.                                                | Error message prompts user to fill all required fields.       | Pass |
| TC021        | Invalid email format             | 1. Enter an invalid email (e.g., no '@'). <br> 2. Submit the form.                                        | Validation error appears for email field.                     | Pass |
| TC022        | File upload (optional)           | 1. Attach a valid file (e.g., `.txt`, `.png`). <br> 2. Submit the form.                                   | Form accepts file and submits successfully.                   | Pass |
| TC023        | File upload with invalid format  | 1. Try to attach unsupported file type (e.g., `.exe`). <br> 2. Submit the form.                           | File is rejected or an error message is shown.                | Fail |
