# SQL Super Store Analysis

![Sales Analysis ER Diagram](Sales%20Analysis%20ER%20Diagram%20SQL.png)

## Overview

This project entails the design and data analysis of a shoe retail chain using SQL. The primary objective is to extract meaningful insights from the sales data to inform business decisions and strategies.

## Dataset

The dataset comprises the following tables:

- **customer_details.csv**: Contains information about customers, including their IDs, names, and contact details.
- **products.csv**: Lists the products available in the store, along with their categories and prices.
- **sales_representative.csv**: Details about sales representatives, including their IDs and names.
- **salesdata.csv**: Records of sales transactions, including order IDs, dates, customer IDs, product IDs, quantities, and sales amounts.
- **suppliers.csv**: Information about product suppliers, including their IDs and names.

## Analysis Questions and Solutions

Below are the key questions addressed in this analysis, along with their corresponding SQL queries and insights:

1. **Total Sales and Average Sales**

   *Query:*
   ```sql
   SELECT 
       SUM(sales_amount) AS total_sales, 
       AVG(sales_amount) AS average_sales 
   FROM salesdata;

   
