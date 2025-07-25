# Automated tests 

A collection of Cypress-based automated tests designed to verify key functionalities of the SauceDemo website.

## Overview

This project contains automated end-to-end tests for the SauceDemo website, built using Cypress. The tests are designed to verify key functionalities of the application, including authentication and cart operations.

## Technologies Used

- Cypress – for writing and executing end-to-end tests
- JavaScript – programming language for test implementation
- Mocha + Chai – built-in test runner and assertion library used by Cypress

## Tests Included

1. **Login with invalid credentials**

      - Tests the login functionality using invalid credentials.
      - Verifies that the system displays an error message in response to invalid login attempts.

3. **Login with valid credentials**
   
      - Tests the login functionality using valid credentials (standard_user).
      - Verifies that the user is redirected to the inventory page and that key page elements are visible, confirming a successful login.
   
4. **Logout Functionality Test**

      - Verifies that a logged-in user can successfully log out.
      - Confirms that the user is redirected to the login page and the login form is visible after logout.

6. **Add product to the cart**
   
      - Verifies that a product can be successfully added to the shopping cart.
      - Confirms that the cart badge updates accordingly and that the selected product appears correctly in the cart page.
   
7. **Remove product from the cart**
   
      - Verifies that a product previously added to the shopping cart can be successfully removed.
      - Confirms that the cart is empty afterward and the cart badge is no longer displayed.



