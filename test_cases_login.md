# Manual Test Cases – Login Functionality

This document contains manual test cases for the login functionality on [https://automationexercise.com](https://automationexercise.com).
 
| Test Case ID | Title                       | Steps to Reproduce                                                                                                | Expected Result                                   | Status    |
|--------------|-----------------------------|-------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|-----------|
| TC001        | Valid login                 | 1. Go to homepage. <br> 2. Click 'Signup / Login'. <br> 3. Enter valid email and password. <br> 4. Click 'Login'. | User is logged in and redirected to account page. | Pass |
| TC002        | Invalid password            | 1. Go to Login page. <br> 2. Enter valid email and incorrect password. <br> 3. Click 'Login'.                     | Error message is displayed.                       | Pass|
| TC003        | Empty fields                | 1. Go to Login page. <br> 2. Leave email and password fields blank. <br> 3. Click 'Login'.                        | Error prompts user to enter credentials.          | Pass|
| TC004        | Invalid email format        | 1. Go to Login page. <br> 2. Enter 'testemail' (no '@'). <br> 3. Click 'Login'.                                   | Error prompts for valid email format.             | Pass |
