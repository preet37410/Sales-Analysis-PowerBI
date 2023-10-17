PowerBI
# Sales Analysis Project Overview
This Power BI project provides a comprehensive analysis of sales data. It includes data extraction, transformation, and loading (ETL) processes to visualize key insights through a dynamic and interactive dashboard.

# Data Sources
The project utilizes two primary data sources: Details, Orders [Source-Rishabh Mishra(Youtube)]

# ETL (Extract, Transform, Load) Process
Data Extraction: Data is sourced from the "Details" and "Orders" files.

Transformation: In the "Orders" file, the header is promoted, and the "Order Date" column's data type is converted to a locale-specific format.

Load: The transformed data is loaded into the Power BI data model for visualization.

# Dashboard Features
Profit-Loss by Month - Clustered Column Chart: Visualizes the monthly trends of profit and loss, allowing to quickly identify seasonal patterns and analyze the financial health of the business.

Profit by Sub-Category - Stacked Bar Chart: Breaks down profits by product sub-categories, enabling to identify which product categories are driving overall profitability and which may need further attention.

Sum of Quantity by Category - Donut Chart: Shows the distribution of product quantities across different categories in an intuitive donut chart. This helps to understand which categories contribute the most to inventory movement.

Sum of Quantity by Payment Mode - Donut Chart: Analyzes how various payment modes impact the quantity of products sold, providing insights into payment trends and customer preferences.

KPI Indicators:

Displays key performance indicators to give you an at-a-glance overview of your business: Sum of Amount: The total sales amount, helping to track revenue. Sum of Profit: The overall profit generated from sales. Sum of Quantity: The total quantity of products sold. Average Order Value: Calculated by creating a new column in the data view, this metric helps to assess the average value of each customer order.

Top States based on Sum of Amount - Stacked Bar Chart: Illustrates the most lucrative states by the sum of sales amounts. This chart is essential for understanding which regions generate the highest revenue.

Top Customers based on Sum of Amount - Stacked Bar Chart: Identifies and ranks the top customers by their total purchase amounts. Recognizing the most valuable customers is crucial for targeted marketing and relationship management.

Slicers: The dashboard includes two slicers that enhance interactivity and filtering: State Selector: Allows to filter data by selecting a specific state. Ideal for regional analysis. Quarter Selector: Allows to focus on a specific section of the year by choosing a quarter (e.g., Quarter 1, Quarter 2). This is particularly useful for tracking seasonal variations in the sales data.
