# RetailManagementDBScripts
These scripts collectively contribute to the management and analysis of retail-related data in a database system.

This repository contains SQL and PL/SQL scripts for a retail management system database. The scripts cover various functionalities such as calculating total spending for shoppers, updating order status, inserting new products, managing projects and pledges, and more.

1. Total Spending Function:

Description: This PL/SQL script defines a function 'totalspending' to calculate the total spending of a shopper in the 'bb_basket' table. It takes a shopper ID as input and returns the total spending amount. The script also includes a testing block that retrieves and displays the total spending for each distinct shopper.

2. Update Order Status Procedure:

Description: The script creates a procedure 'update_order_status' to update the status of an order in the 'bb_basketstatus' table. It takes parameters such as status ID, stage ID, notes, shipper name, and shipping number. The testing block demonstrates how to use this procedure to update the order status.

3. New Product Function:

Description: This PL/SQL script defines a function 'new_prod' to insert new products into the 'bb_basketitem' table. It takes parameters like product ID and quantity, calculates the total price, and inserts the new product. The testing block demonstrates how to call this function and handles success or failure messages.

4. Covid Project and Pledge Insertion and Total Pledge Function:

Description: The script inserts records into the 'dd_project' and 'dd_pledge' tables representing a Covid-19 relief fund project and associated pledges. Additionally, it defines a function 'total_pledge' to calculate the total pledge amount for a given project. The testing block retrieves and displays project details along with their total pledges.

5. Product Addition Procedure:

Description: The script defines a procedure 'PROD_ADD' to add new products to the 'BB_PRODUCT' table. It takes various parameters like product name, description, price, and stock details. The testing block demonstrates how to call this procedure to add a new product.


