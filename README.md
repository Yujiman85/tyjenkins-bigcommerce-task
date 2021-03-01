# Ty Jenkins's Cornerstone Task

<b>Storefront Preview Code:</b> y2yq4aoogv <br>
<b>Storefront URL:</b> https://jenkinscommerce.mybigcommerce.com/

This task demonstrates custom features added to the Cornerstone template by me, Ty Jenkins.
All feature were implemented using Javascript and CSS, as well as some Handlebars syntax due to the nature of the existing code being used for the storefront.

Two new buttons have been added to the "Category" page.
1) An "Add All Items" button to add all of the items in a category to the cart once. *Note: DOES NOT WORK WITH ITEMS THAT REQUIRE CHOOSING OPTIONS(VARIANTS) BEFORE ADDING TO CART.

2) A "Remove All Items" button that removes all items currently in the cart and scraps the cart in case the user wants to add other items afterwards. (Avoids a conflict in creating two carts which BigCommerce won't let happen)

A small block above the new buttons has also been added to display <b>User Info</b> for the user currently logged in. *Will not show if user is not logged in.

All new features have been styled to make them distinct for this particular task.
