
# Superstore Analysis Dashboard
### Dashboard Link:https://github.com/thirisha3sha/superstore-dashboard/blob/main/super%20store%20sales%20dashboard.pbix
### Objective

The objective is to contribute to the success of the business by utilizing data analysis techniques, especially focusing on time series analysis, to provide valuable insights and accurate sales forecasting. The goal is to share valuable insights and actionable information that can drive strategic decision-making and support the supermarket's goals for growth, efficiency, and customer satisfaction.


### Problem Statement
The superstore is looking to optimize its sales strategies and improve operational efficiency. To achieve this, the superstore needs to:
- Understand sales performance across different regions, categories, and customer segments.
- Identify high-performing and low-performing products.
- Analyze customer purchasing patterns to enhance marketing efforts.
- Evaluate operational metrics like order processing and shipment delays to identify bottlenecks.
- Utilize time series analysis techniques to provide accurate sales forecasts.

 ### Description
 ### 1.Dashboard creation
 Identifying the KPI's and designing an intuitive and visually appealing dashboard and interactive visualizations and filtering capabilities to allow users to explore the data at various levels of granularity.
 ### 2.Data analysis
 Provide valuable insights to business entities regarding the effectiveness of their sales and strategies through visualization and charts.
 ### 3.Sales formatting
 Leverage historic data and apply time series analysis to genearte sales forecast for next 50 days.
 ### 4.Actionable Insights and recommendation
 End goal is to share valuable insights and actionable information that can drive strategic decision making and support the supermarkets goals for growth,efficiency and customers satisfaction.
 ### Dataset Description
 ### Dataset link : https://1drv.ms/x/c/b541b271e2666b97/ER7npt-yyoJJhbteNqhQFQwBdZ95BfnXt0SLo5JCKFtD-g?e=o3xA6N
 The dataset used for this analysis contains 21 columns and 5902 rows representing different aspects of sales transactions. Below are the column names and their descriptions:
- **Row ID:** Unique identifier for each row.
- **Order ID:** Unique identifier for each order.
- **Order Date:** The date when the order was placed.
- **Ship Date:** The date when the order was shipped.
- **Ship Mode:** The mode of shipping (e.g., Standard, Express).
- **Customer ID:** Unique identifier for each customer.
- **Customer Name:** The name of the customer.
- **Segment:** The segment to which the customer belongs (e.g., Consumer, Corporate).
- **Country:** The country where the order was placed.
- **City:** The city where the order was placed.
- **State:** The state where the order was placed.
- **Region:** The region where the order was placed.
- **Product ID:** Unique identifier for each product.
- **Category:** The category of the product (e.g., Furniture, Office Supplies).
- **Sub-Category:** The sub-category of the product.
- **Product Name:** The name of the product.
- **Sales:** The sales amount for the order.
- **Quantity:** The quantity of the product ordered.
- **Profit:** The profit amount for the order.
- **Returns:** Indicates if the product was returned.
- **Payment Mode:** The mode of payment used for the order.
### Steps:
### Step 1: Load Data into Power BI Desktop
- Open Power BI Desktop.
- Click on Home > Get Data > Text/CSV.
- Select the CSV file containing the superstore sales dataset and click Load.
### Step 2: Open Power Query Editor
- Go to Home > Transform Data to open Power Query Editor.
- In the View tab under the Data Preview section, check the "Column distribution," "Column quality," and "Column profile" options.
### Step 3: Handle Missing Values
- It was observed that none of the columns except "Return","ind1","ind2" had errors or empty values 
### Step 4: Apply a Theme
In the Report View, under the View tab, select a theme for the report.
### Step 5: Add Card Visuals for KPIs
Add three card visuals for displaying key metrics like Total Sales,Total Profit and Total qunatity.
- **Description:** Displays key performance indicators (KPIs) such as Total Sales, Total Profit, and Total Quantity in a concise and easily digestible format.
- **Insights:** Offers a quick overview of the overall business performance, helping stakeholders to assess the health of the business at a glance.
### snap of KPI-Total Profit
![profit superstore](https://github.com/user-attachments/assets/58a998ca-8ae2-4379-ac31-c21c0cc8ac98)
### snap of KPI-Total Quantity
![quantity superstore](https://github.com/user-attachments/assets/68e617f4-fdd2-4241-8843-849611fabe46)
### snap of KPI-Total Sales
![sales superstor](https://github.com/user-attachments/assets/28eeafb4-8749-4ce9-8181-b77cbe1adb19)
### Step 6: Add Visuals for Detailed Analysis
### Area Chart Profit by Month and Year (2019, 2020):
- **Description:** Visualizes the profit trends over the course of two years. The x-axis represents the months, while the y-axis represents the profit amount. Different colors or shades represent the two years.
- **Insights:** Helps identify profit trends, compare year-over-year performance, detect seasonality, and provide actionable insights to improve profitability.
### Area Chart for Sales by Month and Year (2019, 2020):
- **Description:** Displays the sales revenue trends over the same two-year period. The x-axis represents the months, and the y-axis represents the sales amount. Different colors or shades distinguish the data for each year.
- **Insights:** Shows revenue trends, evaluates year-over-year sales performance, identifies peak sales periods, correlates with profit trends, and informs strategic planning.
### Donut Chart for Sales Payment Mode (Cards, COD, Online):
- **Description:** Illustrates the distribution of sales across different payment modes: Cards, Cash on Delivery (COD), and Online.
- **Insights:** Helps understand customer payment preferences, identify the most popular payment methods, and assess the potential need to improve certain payment options.
### Donut Chart for Sales by Segment (Home Office, Consumer, Corporate):
- **Description:** Shows the sales distribution across different customer segments: Home Office, Consumer, and Corporate.
- **Insights:** Provides insights into which segments are driving the most sales, helping to tailor marketing strategies and product offerings to target high-value segments effectively.
### Map for Sales and Profit by State in the US:
- **Description:** A geographic map that visualizes sales and profit data across different states in the US.
- **Insights:** Highlights regional performance, identifies high and low-performing states, and helps in regional sales strategy planning and resource allocation.
### Clustered Bar Chart for Sales by Ship Mode (Standard Class, First Class, Second Class, Same Day)
- **Description:** Compares sales across different shipping modes: Standard Class, First Class, Second Class, and Same Day.
- **Insights:** Helps understand the popularity and performance of different shipping options, which can guide shipping strategy and customer service improvements.
### Clustered Bar Chart for Sales by Category (Office Supplies, Furniture, Technology)
- **Description: **Displays sales distribution across different product categories: Office Supplies, Furniture, and Technology.
- **Insights:** Identifies which product categories are performing best, helping in inventory management and marketing focus.
### Clustered Bar Chart for Sales by Sub-Category (Phones, Chairs, Binders)
- **Description:** Shows sales distribution across specific product sub-categories such as Phones, Chairs, and Binders.
- **Insights:** Provides detailed insights into the performance of specific product lines, aiding in product development and promotional efforts.
### Clustered Bar Chart for Sales by State
- **Description:** Compares sales figures across different states.
- **Insights:** Highlights the states with the highest and lowest sales, assisting in regional sales analysis and strategy development.
### Slicer for Analyzing Sales by Region (Central, East, West, South)
- **Description:** Allows users to filter the data by region, providing a focused view of sales performance in the Central, East, West, and South regions.
- **Insights:** Facilitates regional comparisons, helps in understanding regional preferences and trends, and supports targeted regional strategies.
### Line Chart for Sales by Order Date and Forecasting Sales for Next 50 Days
- **Description:** Plots sales data over time and includes a forecast for the next 50 days.
- **Insights:** Shows historical sales trends, helps in predicting future sales, and aids in planning and inventory management.
### Superstore sales report 
  ![superstore dashboard page1](https://github.com/user-attachments/assets/303c9f0b-5f44-4438-9476-4734eecf92dc)
### Superstore sales forecasting report
  ![superstore dashboard page2](https://github.com/user-attachments/assets/a96b35bc-c238-4885-be13-0a2f48f552fb)
### Conclusion
The Superstore Sales Analysis Dashboard is an essential tool for optimizing sales and operations in a retail business. It provides comprehensive insights into sales trends, customer behavior, and operational efficiency through various visualizations.By analyzing sales data and customer feedback, the superstore can identify specific areas for improvement and take actionable steps to enhance overall customer satisfaction.this dashboard enables informed decision-making, inventory optimization, enhanced customer experience, and improved operational efficiency, ultimately driving business growth.
