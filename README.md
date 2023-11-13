# SQL and Python Data Analysis for Classic Models Database
Description:
This project focuses on leveraging the power of SQL and Python to conduct a comprehensive analysis of the "classicmodels" database in PostgreSQL. The primary objectives include establishing a connection to the database, 
creating independent dataframes for specific tables, merging and consolidating data, performing calculations, and generating insightful reports. 
The project showcases the seamless integration of SQL and Python for efficient data manipulation, analysis, and reporting. 
From connecting to the database to creating consolidated dataframes and generating reports, this project demonstrates a step-by-step approach to extracting meaningful insights from the classicmodels database.

Instructions
1. Database Connection Credentials
To connect to the PostgreSQL database, use the following credentials:

HOST = 'localhost'
USERNAME = 'postgres'
with open('final_test/credenciales.txt', 'r') as password_file: # In this step you should to create a file on your PC with your password and replace "credenciales.txt" with your file.
    PASSWORD = password_file.read().strip()
DATABASE = 'postgres'

2. Imported Libraries
Import the necessary libraries for the project. Brief descriptions of each library are provided below:

os: Operating system dependent functionality.
psycopg2: A Python library for working with PostgreSQL databases.
csv: Module for reading and writing CSV files.
pandas: Data manipulation and analysis library.
numpy: Library for numerical operations.
warnings: Module to handle warnings in the script.

3. Create Independent Dataframes
Create independent data frames for the following tables: Orders, Orderdetails, Customers, Products, Employees.

4. Merge Tables and Create a Consolidated DataFrame
Perform a merge of the created data frames to create a consolidated data frame.

5. Add Calculated Columns
Add calculated columns to the consolidated dataframe, such as sales (revenue), cost, and profit.

6. Create Pivot Table
Create a pivot table to display total sales for each product line.

7. Count Unique Customers
Count unique customers who have purchased in the current year and count customers who have not yet purchased.

8. Create Reports
Create two reports:

Report 1: The list of top 10 customers (for sales).
Report 2: Top 10 products sold.

9. External File with Functions
Create an external file with functions and import these functions into the Jupyter notebook for execution. You can use the example file funciones.py

Execution
Execute the Jupyter notebook with the provided instructions and functions for a comprehensive analysis of the classicmodels PostgreSQL database.

Feel free to reach out for any questions or clarifications.

Happy coding!
