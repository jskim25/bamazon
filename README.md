# Bamazon
Week 12 homework

Bamazon is an Amazon-like storefront where the app takes in orders and changes the data in a SQL database to reflect the commands selected.

There are two main parts to this app: the customer side and manager side. On the customer side, the user is able to select an item that he/she wishes to purchase and then specifies the quantity. Once those two parameters are fulfilled, the terminal will let the user know that the transaction was successful.

On the manager side, the user is able to do one of four things: view all the products for sale, view low inventory, add inventory, or add a new product.

## Getting Started
Open the command line and type in "node bamazonCustomer.js" or "node bamazonManager.js" depending on whether you want customer access or manager access. An inquirer prompt will give you directions each step of the way. There is a cancel command for both in case you'd like to exit the program. Screenshots have been added below.

When running bamazonCustomer.js, you will be prompted to enter the item ID number from a table that will auto-generate when the app initializes. If you select a valid item ID number, you will then be asked how many of the item you would like to purchase.
!(/Users/jameskim/Desktop/coding_projects/Bamazon/assets/images/customer-purchase.png)

If you'd like to quit at any time, you just need to enter 'C' and cancel.
!(/Users/jameskim/Desktop/coding_projects/Bamazon/assets/images/customer-cancel.png)

When running bamazonManager.js, you will be given a list of valid commands.

View Products for Sale - this allows you to see all the data in the products table from the SQL database:
!(/Users/jameskim/Desktop/coding_projects/Bamazon/assets/images/manager-view-products.png)

View Low Inventory - this will show you all the items that have a quantity of 10 or lessonly items with quantity of 10 or less:
!(/Users/jameskim/Desktop/coding_projects/Bamazon/assets/images/manager-view-low-inventory.png)

Add to Inventory - this allows you to increase the stock of a specified item:
!(/Users/jameskim/Desktop/coding_projects/Bamazon/assets/images/manager-add-inventory.png)

Add a Product - you can create a new item that will post to the bamazon database and allow the customer to purchase:
!(/Users/jameskim/Desktop/coding_projects/Bamazon/assets/images/manager-add-product.png)

## Prerequisites
For this application to work, you will need to have installed the inquirer, mysql, and console.table npm packages.

## Installing
To install an NPM package, type "npm install" followed by the NPM package name.
