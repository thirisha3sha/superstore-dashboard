
# Superstore Analysis Dashboard

## Objective

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
 Identify the KPI's design an intuitive and visually appelaing dashboard and interactive visualizations and filtering capabilities to allow users to explore the data at various levels of granularity.
 ### 2.Data analysis
 Provide valuable insights to business entities regarding the effectiveness of their sales and strategies through visualization and charts.
 ### 3.Sales formatting
 Leverage historic data and apply time series analysis to genearte sales forecast for next 50 days.
 ### 4Actionable Insights and recommendation
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
-Go to Home > Transform Data to open Power Query Editor.
- In the View tab under the Data Preview section, check the "Column distribution," "Column quality," and "Column profile" options.
### Step 3: Handle Missing Values
- It was observed that none of the columns except "Return","ind1","ind2" had errors or empty values.
### Step 4: Apply a Theme
In the Report View, under the View tab, select a theme for your report.
### Step 5: Add Card Visuals for KPIs
Add three card visuals for displaying key metrics like Total Sales,Total Profit and Total qunatity.
### Step 6: Add Visuals for Detailed Analysis
- **Area Chart Profit by Month and Year (2019, 2020):** Visualizes profit trends over time.
- **Area Chart for Sales by Month and Year (2019, 2020):** Displays sales revenue trends.
- **Donut Chart for Sales Payment Mode (Cards, COD, Online): **Shows distribution of sales by payment modes.
- **Donut Chart for Sales by Segment (Home Office, Consumer, Corporate):** Illustrates sales distribution across customer segments.
- **Map for Sales and Profit by State in the US:** Visualizes geographic distribution of sales and profit.
- **Clustered Bar Chart for Sales by Ship Mode:** Compares sales across different shipping modes.
- **Clustered Bar Chart for Sales by Category:** Shows sales distribution across product categories.
- **Clustered Bar Chart for Sales by Sub-Category:** Displays sales distribution across product sub-categories.
- **Clustered Bar Chart for Sales by State:** Compares sales figures across different states.
- **Slicer for Analyzing Sales by Region:** Allows filtering sales data by regions (Central, East, West, South).
- **Line Chart for Sales by Order Date and Forecasting Sales for Next 50 Days:** Plots sales data over time and forecasts future sales.
  
 ![Snap_1](https://user-images.githubusercontent.com/102996550/174089602-ab834a6b-62ce-4b62-8922-a1d241ec240e.jpg)
