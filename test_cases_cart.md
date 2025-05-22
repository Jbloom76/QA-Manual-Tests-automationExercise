# Test Cases – Login Functionality

| Test Case ID | Title                       | Steps to Reproduce                                                                 | Expected Result                  | Status  |
|--------------|-----------------------------|-------------------------------------------------------------------------------------|----------------------------------|---------|
| TC001        | Valid login                 | 1. Go to the homepage. <br> 2. Click Login. <br> 3. Enter valid email/password. <br> 4. Click Login. | User is logged in successfully. | Pass/Fail |
| TC002        | Invalid password            | Enter valid email and invalid password                                             | Error message is shown.          |         |
| TC003        | Empty email and password    | Submit the form with no credentials                                                | Error message prompts for input. |         |
