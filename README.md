# Global-super-store-Sales-Analysis

# Overview
This project analyzes sales data from a global superstore to provide stakeholders with detailed insights into sales transactions. The analysis includes data cleaning, segmentation of visuals by country, region, and market, shipping analysis, and comprehensive sales reports by geography. The final output is an interactive sales report created using Power BI.

## Check out the presentation of the Global Superstore Sales Analysis Dashboard here⤵:
https://drive.google.com/file/d/1o1tdB20XjXPHk6O1_VALwQdIqyRiCn9D/view?usp=sharing


## Key Performance Indicators

The dashboard prominently displays essential metrics such as total sales, total profit, total units sold, total number of products, total number of customers, and total orders. These KPIs provide a snapshot of the company's sales performance.

Total Sales: $12.64M

Total Profit: $1.47M

Total Units Sold: 178K

Total Number of Products: 10K

Total Number of Customers: 1,590

Total Orders: 51K

# Data Cleaning

To ensure data accuracy and consistency, the following data cleaning tasks were performed using Power BI’s Power Query Editor:

Replace null values

Removing duplicates

Correcting data types

change heading

# Data Modeling

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


# Visualizations

Segmenting Visuals
Country Representation: Sales data visualized on a map to show distribution across different countries.us and australia and france have most no:of sales 

Region Representation: Bar chart comparing sales across various regions. central, north,south have most no: of sale by region

Market Representation: Treemap illustrating sales distribution across different markets.APAC,EU have most no:of sales in market


## Shipping Analysis

A pie chart was created to visualize the percentage of shipping based on different ship modes:

Standard Class: Highest sales,
Second Class,
First Class,
Same Day respectively

## Sales Report

An interactive sales report was created using slicers for city, state, region, and market to allow stakeholders to drill down into specific areas for detailed sales information.

 ## Tables for Visualizations

 These tables provide detailed numerical data supporting the insights derived from the visuals. This includes tables for

Sales by City,
Sales by State,
Sales by Region,
Sales by Market and
Shipping Modes

# Conclusion

This comprehensive sales analysis provides valuable insights into sales transactions across different geographies and shipping modes. The interactive dashboard allows stakeholders to explore data in depth, facilitating informed decision-making.
