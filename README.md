# Inventory Management Website

Inventory management system using node js and mysql. 

## Functionalities

**User**
1. Register and Login.
2. Browse through all the available products.
3. Place order.
4. Notify when the order has been delivered.

**Admin**
1. See all active and completed orders.
2. Edit details of existing products.
3. Add new products.

**General**
1. Updates the quantity of products after each order and after each update in product details by admin.
2. Authenticates users and admins.
3. Adds a new user to the database.

## Connect to mysql

Visit `localhost/phpmyadmin` and create a new database named `inventorydb`. Import the **inventorydb.sql** query located in the database folder. Visit privileges and create a new user having access to the database and add it's details to app.js.

## Install and Run

First install all dependencies

~~~~
npm install
~~~~

Then run the app

~~~~
node app.js
~~~~

## Creating New Admin User Manually

Visit `localhost:3000/secretadminreg`. This will create a new admin user with **username:** 'admin' and **password:** 'password' & store it in the database. You can now access the admin dashboard using the created account.
