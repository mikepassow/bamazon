<h1>Bamazon</h1>

<h2>Description</h2>
<p>This application implements a simple command line based storefront using the npm inquirer package and the MySQL database backend together with the npm mysql package. The application presents two interfaces: customer and manager.</p>

<h2>MySQL Database Setup</h2>
<p>In order to run this application, you should have the MySQL database already set up on your machine. If you don't, visit the MySQL installation page to install the version you need for your operating system. Once you have MySQL isntalled, you will be able to create the Bamazon database and the products table with the SQL code found in Bamazon.sql. Run this code inside your MySQL client like Sequel Pro to populate the database, then you will be ready to proceed with running the Bamazon customer and manager interfaces.<p>

<h2>bamazonCustomer</h2>
<p>
The customer interface allows the user to view the current inventory of store items: item IDs, descriptions, department in which the item is located and price. The user is then able to purchase one of the existing items by entering the item ID and the desired quantity. If the selected quantity is currently in stock, the user's order is fulfilled, displaying the total purchase price and updating the store database. If the desired quantity is not available, the user is prompted to modify their order.
</p>

<h2>bamazonManager</h2>
<hr>
<ul><li>The View Products for Sale option allows the user to view the current inventory of store items: item IDs, descriptions, department in which the item is located, price, and the quantity available in stock.</li>

<li>The View Low Inventory option shows the user the items which currently have fewer than 100 units available.</li>

<li>The Add to Inventory option allows the user to select a given item ID and add additional inventory to the target item.</li>

<li>The Add New Product option allows the user to enter details about a new product which will be entered into the database upon completion of the form.</li>

<h2>Screenshot of How it Works</h2>
<div>
    <img src="screenshots/bamazon.png" width="400px"> 
</div>