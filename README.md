# Bamazon
An amazon-like virtual store-front

CUSTOMER PORTAL

The customer portal on Bamazon has two functions:

View all available products
Buy a product selected by ID.
After selecting an item from the list, the user is displyed the item they selected and prompted for a quantity to purchase.

Once the user has selected their item and the quantity they would like to purchase, the database is checked for product availibility. If the user has selected a quantity larger than what is in the DB, they will be notified to choose another option.

However, if the user quantity is less than what is in the DB, they will be notified that their item has been shipped and the DB quantity is updated.


  MANAGER PORTAL
The mangager portal currently has four working functions:

view-inven - display all current products in the database
low-inven - displays all inventory itemswith a stock below 5
add-inven - function that allows the manager to add products to inventory
help - displays all available commands to the user and re-runs the program