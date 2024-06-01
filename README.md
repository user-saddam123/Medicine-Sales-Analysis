# Medicine Sales Analysis

## Created & Analyzed by Saddam Ansari @Aspiring Data Analyst [Linkedin](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)
### Live Dashboard at Novypro [Live_link_Novypro](https://project.novypro.com/KnF4wU)

#

## Project Objective

The primary objective of this project is to develop a comprehensive and visually appealing Power BI dashboard that analyzes the medicine sales data for the entire year of 2023. 

This initiative has been undertaken in response to stakeholders' requests to gain a clear understanding of sales performance. By transforming raw data into actionable insights, the dashboard aims to assist stakeholders in making informed strategic decisions for future planning.

#

## Dataset Overview
This project involves analyzing medicine sales data using **three provided CSV files**. Each file represents a different aspect of the dataset: **customers**, **drugs**, and **sales transactions**. 


Below is a detailed description of each table, including the data types and brief descriptions of each column.

### 1. Customer Table
The Customer Table contains information about the customers who purchase medicines.

|Column	| Data Type	|Description|
|--|--|--|
|CustomerID|	Integer	|Unique identifier for each customer|
|FirstName|	String|	First name of the customer|
|LastName	|String	|Last name of the customer|
|Age	|Integer	|Age of the customer|
|Gender|	String|	Gender of the customer|
|Country|	String|	Country where the customer resides|
|OtherCustomerInfo|	String	|Additional information about the customer (e.g., Frequent Buyer, New Customer)|

### 2. Drugs Lookup Table
The Drugs Lookup Table contains information about the medicines available for sale.

|Column	|Data Type|	Description|
|--|--|--|
|DrugID	|Integer	|Unique identifier for each drug|
|RegulatoryComplianceID	|Integer	|Identifier for regulatory compliance category|
|DrugName	|String|	Name of the drug|
|UnitSalesPrice	|Float|	Sales price per unit of the drug|
|CostOfProduction	|Float	|Production cost per unit of the drug|
|Treats	|String	|Description of what the drug treats|

### 3. Sales Transactions Table
The Sales Transactions Table records each sale made, including details of the drug sold and the customer who bought it.

|Column|	Data Type	|Description|
|--|--|--|
|SaleID	|Integer|	Unique identifier for each sale|
|DrugID|	Integer	|Identifier for the drug sold|
|CustomerID|	Integer	|Identifier for the customer who bought the drug|
|UnitsSold	|Integer	|Number of units sold in the transaction|
|SaleDate|	Date	|Date of the sale|
|BuyerType	|String	|Type of buyer (e.g., Seller, User)|

### Summary
 * **Customer Table**: Provides demographic and additional information about each customer.
 * **Drugs Lookup Table**: Contains details about each drug, including pricing and regulatory information.
 * ***Sales Transactions Table**: Records details of each sale, including the drug sold, the customer, and the transaction specifics.

#

## Dashboard Overview
Based on the project objective, I have developed a comprehensive Power BI dashboard report consisting of three pages, each serving a distinct purpose to provide valuable insights from the medicine sales data.

#### 1. Overview Page:
This page offers a high-level view of overall sales, showcasing various aspects such as total sales, revenue, and key performance indicators. It includes visualizations like bar charts and summary cards to present an intuitive and informative snapshot of the sales performance.

#### 2. Customers and Demographics Page:
The second page focuses on customer-related insights and demographic analysis. It displays detailed information about customer segments and demographic distribution. 

#### 3. Trend Analysis Page:
The final page is dedicated to trend analysis, highlighting different trends in sales and revenue over time. It includes line charts, trend lines, and time-series analyses to illustrate sales performance and revenue growth patterns. This page helps stakeholders identify seasonal variations, growth trends, and other temporal insights.

#

## Detailed Insights Explanation:

### Page-One:
![Uploading Screenshot 2024-06-01 073237.jpg…]()

This page provides a comprehensive overview of the overall sales performance, designed to give stakeholders a clear and detailed understanding of key metrics and trends. The page is structured as follows:

#### Top KPIs Section:
At the top of the page, five key performance indicators (KPIs) are displayed. These KPIs are dynamically filtered based on the selected month, providing a quick snapshot of the following metrics:

 * **Quantity Sold**: Comparison between the current month and the previous month, along with the growth percentage.
 * **Cost of Goods Sold (COGS)**: Monthly comparison and growth percentage.
 * **Revenue:** Monthly comparison and growth percentage.
 * **Profit:** Monthly comparison and growth percentage.

These KPIs help in monitoring monthly performance and identifying trends at a glance.

#### Top and Bottom Drugs Bar Chart:
Below the KPIs, a bar chart is presented to display the top and bottom performing drugs. The drugs can be viewed based on various metrics, such as:
 * Transactions: Number of transactions for each drug.
 * Profit: Profit generated by each drug.
 * Revenue: Revenue generated by each drug.
 * Units Sold: Number of units sold for each drug.

This chart helps in identifying which drugs are performing well and which ones need attention.

#### Top and Bottom Customers Bar Chart:
Similar to the drugs chart, there is a bar chart for customers, showing the top and bottom customers based on:
 * Transactions: Number of transactions made by each customer.
 * Profit: Profit generated from each customer.
 * Revenue: Revenue generated from each customer.
 * Units Sold: Number of units sold to each customer.

This analysis helps in understanding customer behavior and identifying key customer segments.

**For a detailed understanding and interactive experience, visit the live dashboard.**

#


