# TEST SUMMARY REPORT

**Project Name:** Swag Labs
**Application / Website:** https://www.saucedemo.com
**Tested By:** Günel Babayeva
**Test Period:** 25 Jan 2026 – 30 Jan 2026

## Test Environment

* **Browser:** Google Chrome
* **OS:** Windows 10
* **Device:** Desktop

**Report Date:** 30 Jan 2026

---

# 1. Test Objectives

The objective of this testing is to verify the main functionality and usability of the application. This includes validating login with different user types, checking product information accuracy, and verifying Add to Cart, Remove from Cart, and checkout functionalities. Additionally, user interface elements such as icons, buttons, and menu navigation are checked to ensure proper display and functionality.

---

# 2. Scope

## Project Scope

* **Login:** Verification of valid and invalid credentials
* **Main Page:** Verification of product images, prices, and product information
* **Filtering:** Verification of filtering products by name and price
* **Burger Menu:** Verification of menu items including About, Logout, and Reset App State

### Cart Functionality

* Adding products to the cart

* Removing products from the cart

* Proceeding to checkout

* Returning to the main page

* **Footer / Social Media Links:** Verification of social media links (LinkedIn, Facebook, Twitter)

---

# 3. Out of Scope

* Payment processing
* Backend and database testing
* Security testing

---

# 4. Test Summary

The test run achieved a **100% completion rate**. A total of **24 test cases** were executed during this test cycle.

* **15 test cases passed successfully**
* **9 test cases failed**

No test cases were left **untested, blocked, skipped, retested, or marked as invalid**.

---

# 5. Defect Summary

| ID | Title                                                                         | Severity |
| -- | ----------------------------------------------------------------------------- | -------- |
| 1  | Product filter by name and price not working on main page                     | Minor    |
| 2  | Filter function does not update product list on main page                     | Minor    |
| 3  | Default defect name displayed instead of correct error message                | Major    |
| 4  | Filter function does not work correctly for problem_user on main page         | Major    |
| 5  | Product images and prices do not match for problem_user                       | Critical |
| 6  | About menu does not open correct page                                         | Critical |
| 7  | Reset App State option does not reset application state                       | Critical |
| 8  | All Items option does not display all products                                | Critical |
| 9  | Multiple products cannot be added to cart for error_user and problem_user     | Critical |
| 10 | Remove button does not remove product from cart on main page                  | Critical |
| 11 | Product cannot be removed from cart from main page                            | Critical |
| 12 | Checkout process fails after entering required information for problem_user   | Critical |
| 13 | Required checkout information cannot be entered successfully for problem_user | Critical |
| 14 | Icons and buttons layout not displayed correctly for error_user on main page  | Critical |

---

# 6. Report Comments and Conclusion

The testing activities for the Swag Labs website were completed successfully within the planned testing period. A total of **24 test cases were executed**, with **15 passing and 9 failing**.

Overall, the main functionalities of the application such as **login, product display, cart operations, and navigation** were tested. Most core features worked as expected; however, several issues were identified that may affect user experience and should be addressed.

### QA Recommendations

* Fix the reported defects and perform **retesting** to verify the fixes
* Conduct **regression testing** after bug fixes to ensure no existing functionality is affected
* Improve **input validation** for user data during the checkout process
* Verify **UI consistency and error message clarity** to improve user experience

Implementing these improvements will help enhance the **stability, usability, and overall quality** of the application.
