# SauceDemo Functional Test Checklist

| Section        | Title | Status | Comment |
|---------------|-------|--------|---------|
| Login | Redirects the user to the Products page when valid username and password are entered |  |  |
| Login | Displays the error message "Epic sadface: Username and password do not match any user in this service" when an invalid username or password is entered |  |  |
| Login | Displays the error message "Epic sadface: Username is required" when the username field is left empty |  |  |
| Login | Displays the error message "Epic sadface: Password is required" when the password field is left empty |  |  |
| Login | Displays the error message "Epic sadface: Sorry, this user has been locked out." when logging in with a locked_out_user |  |  |
| Products Page | Displays all product names, images, descriptions, and prices correctly on the Products page |  |  |
| Products Page | Redirects the user to the product detail page when clicking on a product name or image |  |  |
| Products Page | Adds the product to the cart and increases the cart badge count when clicking the "Add to Cart" button |  |  |
| Products Page | Redirects the user to the Cart page when clicking the cart icon |  |  |
| Burger Menu | Opens the side navigation menu when clicking the burger menu icon |  |  |
| Burger Menu | Redirects the user to the Products page when selecting "All Items" |  |  |
| Burger Menu | Redirects the user to the About page when selecting "About" |  |  |
| Burger Menu | Redirects the user to the Login page when selecting "Logout" |  |  |
| Burger Menu | Resets the cart and sets the cart badge count to 0 when selecting "Reset App State" |  |  |
| Filter | Displays filter options when clicking the filter dropdown |  |  |
| Filter | Sorts products alphabetically from A to Z when selecting "Name (A to Z)" |  |  |
| Filter | Sorts products alphabetically from Z to A when selecting "Name (Z to A)" |  |  |
| Filter | Sorts products by price in ascending order when selecting "Price (low to high)" |  |  |
| Filter | Sorts products by price in descending order when selecting "Price (high to low)" |  |  |
| Cart | Displays the selected product’s name, price, and description correctly on the Cart page |  |  |
| Cart | Removes the product from the cart and decreases the cart badge count when clicking the "Remove" button |  |  |
| Cart | Redirects the user to the Products page when clicking the "Continue Shopping" button |  |  |
| Cart | Redirects the user to the Checkout Information page when clicking the "Checkout" button |  |  |
| Checkout | Displays the error message "Error: First Name is required" when the First Name field is left empty |  |  |
| Checkout | Displays the error message "Error: Last Name is required" when the Last Name field is left empty |  |  |
| Checkout | Displays the error message "Error: Postal Code is required" when the Zip/Postal Code field is left empty |  |  |
| Checkout | Redirects the user to the Checkout Overview page when valid information is entered and the "Continue" button is clicked |  |  |
| Checkout | Displays the message "Thank you for your order!" when clicking the "Finish" button |  |  |
| Checkout | Redirects the user to the Products page when clicking the "Back Home" button |  |  |
| Logout | Prevents access to the Products page when clicking the browser Back button after logging out |  |  |
