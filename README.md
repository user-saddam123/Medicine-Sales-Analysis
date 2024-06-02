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
![Screenshot 2024-06-01 073237](https://github.com/user-saddam123/Medicine-Sales-Analysis/assets/123800896/da7d57ff-84c2-418a-b797-bbd2a9aacc1b)


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

### Page-Two
![Screenshot 2024-06-01 073354](https://github.com/user-saddam123/Medicine-Sales-Analysis/assets/123800896/42c9ddc0-12cf-4ab5-9796-af5591932e0e)

This page provides in-depth insights into customer demographics and their contribution to sales and revenue. The layout and visualizations are designed to help stakeholders understand customer behavior and demographic trends effectively. The key elements of this page are:

#### Key Performance Indicators (KPIs):
Important KPIs are displayed at the top, offering a quick overview of customer-related metrics:

 * Total Customers: The total number of unique customers.
 * Average Revenue per Customer: The average revenue generated per customer.
 * Total Revenue: The total revenue generated.

#### Sales by Country Map Chart:
 * A map chart is provided to display sales distribution by country.
 * Users can interact with this chart to view detailed sales data for each country by using the provided bookmarks.

#### Revenue by Gender Doughnut Chart:
 * This chart shows the percentage of revenue contributed by each gender.
 * It helps in understanding gender-wise revenue distribution and identifying key customer segments.

#### Revenue by Buyer Type:
 * A visual representation of revenue generated from different types of buyers (Sellers vs. Users).
 * This helps in determining the contribution of each buyer type to the overall revenue.

#### Revenue by Age Group:
 * A visualization that displays revenue distribution across different age groups.
 * This provides insights into which age groups are the most profitable and helps in targeted marketing efforts.

#

### Page Three:
![Screenshot 2024-06-01 073421](https://github.com/user-saddam123/Medicine-Sales-Analysis/assets/123800896/7abd6c3f-3bda-4f56-b814-14b79902ead5)

The third page of the dashboard focuses on analyzing various sales and revenue trends over different time periods. This page is essential for understanding how sales performance changes over time and identifying patterns that can inform future strategies. The key components of this page are:

#### Key Performance Indicator (KPI):
 * **Total Transactions**: A KPI at the top of the page showing the total number of transactions.

#### Revenue by Year Line Chart:
 * A line chart that displays the revenue on a yearly basis.
 * This visualization helps in understanding the annual revenue trends.

#### Revenue by Quarter Line Chart:
 * Another line chart that shows the revenue broken down by quarters.
 * It provides insights into quarterly revenue performance, helping to identify seasonal trends.

#### Revenue by Month Line Chart:
 * This line chart illustrates the monthly revenue.
 * It helps in tracking the revenue performance on a month-to-month basis.

#### Monthly Growth Percentage:
 * A visual representation of the percentage growth from the previous month to the current month.
 * This metric is crucial for understanding the monthly growth rate and identifying any significant changes in revenue.

#### Weekly Trend by Medicine Sales:
 * This visualization shows the sales trends of the top 5 drugs on a weekly (day-wise) basis.
 * It helps in identifying which medicines are sold the most on specific days of the week.

For a detailed understanding and interactive experience, please visit the live dashboard.

#


**This project is the result of over 7-10 days of hard work, and I invite you to 👍 like, share, and connect with me on [LinkedIn](https://www.linkedin.com/in/saddam-ansari-dataanalyst/).**

I hope scrolling through this project provides you with insightful understanding.

Thank you for taking the time to view my project.

#

## How you can help me:

I've successfully completed over **65 Power BI projects**, all showcased in my [Novypro portfolio](https://www.novypro.com/profile_projects/saddamansari). You're all invited to visit my portfolio and explore these amazing projects!

**Additionally, I'm currently seeking internship or entry-level opportunities. If you have any opportunities available or need a freelance Power BI project completed, please connect with me on LinkedIn.**

Looking forward to connecting with you all!

#

### Created and Presented by-

Saddam Ansari @Aspiring Data Analyst [LinkedIn](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)

Location: India
