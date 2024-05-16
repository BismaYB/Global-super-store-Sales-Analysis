# Global-super-store-Sales-Analysis

# Overview
This project analyzes sales data from a global superstore to provide stakeholders with detailed insights into sales transactions. The analysis includes data cleaning, segmentation of visuals by country, region, and market, shipping analysis, and comprehensive sales reports by geography. The final output is an interactive sales report created using Power BI.

## Check out the presentation of the Global Superstore Sales Analysis Dashboard here⤵:


## Key Performance Indicators

The dashboard prominently displays essential metrics such as total sales, total profit, total units sold, total number of products, total number of customers, and total orders. These KPIs provide a snapshot of the company's sales performance.

Total Sales: $12.64M
Total Profit: $1.47M
Total Units Sold: 178K
Total Number of Products: 10K
Total Number of Customers: 1,590
Total Orders: 51K

## Data Cleaning
To ensure data accuracy and consistency, the following data cleaning tasks were performed using Power BI’s Power Query Editor:

Replace null values
Removing duplicates
Correcting data types
change heading

## Data Modeling
Orders Table
The Orders table contains detailed transaction data, including order IDs, product IDs, customer IDs, sales, profit, quantity, discount, ship mode, and order and ship dates.

People Table
The People table includes information about the salespeople names, and regions.

Returns Table
The Returns table lists the returned orders, including order IDs and Market.

Relationships
The Orders table is linked to the People table via the Salesperson name
The Orders table is linked to the Returns table via the Order ID.

## New Measures
Several new measures were created to enhance analysis:
total sales, total profit, total units sold, total number of products, total number of customers, and total orders.
