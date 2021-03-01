# Ty Jenkins's Cornerstone Task
![tests](https://github.com/bigcommerce/cornerstone/workflows/Theme%20Bundling%20Test/badge.svg?branch=master)

This task demonstrates custom features added to the Cornerstone template by me, Ty Jenkins.

Two new buttons have been added to the "Category" page.
    -- An "Add All Items" button to add all of the items in a category to the cart once. *Note: DOES NOT WORK    WITH ITEMS THAT REQUIRE CHOOSING OPTIONS(VARIANTS) BEFORE ADDING TO CART.

    -- A "Remove All Items" button that removes all items currently in the cart and scraps the cart in case the user wants to add other items afterwards. (Avoids a conflict in creating two carts which BigCommerce won't let happen)