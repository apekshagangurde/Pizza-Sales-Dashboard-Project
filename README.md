# Pizza Sales Dashboard Project README

## Overview:
This project aims to create an interactive dashboard using Power BI to analyze pizza sales data. The final output is an intuitive dashboard featuring various charts and key performance indicators (KPIs) to assist business owners in making data-driven decisions.

## Tools and Versions:
- MS Office Excel 2021
- MS SQL Server 19.0
- Power BI June 2023

  ## Charts Requirement:

### 1. Daily Trend for Total Orders:
   - Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help us identify any patterns or fluctuations in order volumes on a daily basis.

### 2. Monthly Trend for Total Orders:
   - Create a line chart that illustrates the hourly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high order activity.

### 3. Percentage of Sales by Pizza Category:
   - Create a pie chart that shows the distribution of sales across different pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales.

### 4. Percentage of Sales by Pizza Size:
   - Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.

### 5. Total Pizzas Sold by Pizza Category:
   - Create a funnel chart that presents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.

### 6. Top 5 Best Sellers by Revenue, Total Quantity, and Total Orders:
   - Create a bar chart highlighting the top 5 best-selling pizzas based on Revenue, Total Quantity, and Total Orders. This chart will help us identify the most popular pizza options.

### 7. Bottom 5 Best Sellers by Revenue, Total Quantity, and Total Orders:
   - Create a bar chart showcasing the bottom 5 worst-selling pizzas based on Revenue, Total Quantity, and Total Orders. This chart will enable us to identify underperforming or less popular pizza options.

## Project Steps:

1. **Setting up SQL Server:**
   - Open SQL Server Management Studio and connect to the server.
   - Create a new database for Pizza sales.
   - Import the provided CSV file into the database.
   - Modify data types of columns if necessary.

2. **SQL Queries:**
   - Query 1: Find total revenue.
   - Query 2: Determine average order value.
   - Query 3: Calculate total quantity of pizzas sold.
     - Total orders placed are determined by taking the distinct count of the order ID column.
     - Average pizzas per order are calculated by dividing the total number of pizzas sold by the total number of orders.

3. **Power BI Dashboard Development:**
   - Connect Power BI to the MS SQL Server as the data source.
   - Import data and apply necessary transformations using Power Query.
   - Create measures for total revenue, average order value, and total orders.
   - Generate visuals including card visuals for KPIs, charts for sales analysis, and filters for easy exploration.
   - Apply filters for specific pizza categories.
   - Implement interactive features for easy data exploration.
   - [Dashboard Snapshot 1]![home](https://github.com/apekshagangurde/Pizza-Sales-Dashboard-Project/assets/100061307/dbded41d-613e-4f69-9367-3877472b41f6)
   - [Dashboard Snapshot 2]![dashboard](https://github.com/apekshagangurde/Pizza-Sales-Dashboard-Project/assets/100061307/f57976d5-64bb-4de7-a7d6-fa45310d3a82)


4. **Analysis and Visualization:**
   - Identify top five best-selling pizzas to offer discounts and attract more customers.
   - Identify bottom five worst-selling pizzas to consider removing from the menu.
   - Analyze sales trends by day of the week and month.
   - Visualize sales data by pizza category and analyze percentage of sales.
   - Validate results against SQL query outputs.

5. **Document Preparation:**
   - Include SQL queries with snapshots of outputs for result validation.
   - Document can be shared with users, colleagues, and clients for reference and validation.

## Usage:
- Users can interact with the Power BI dashboard to explore sales data.
- Colleagues and clients can refer to the documented SQL queries and analysis for result validation.

## Additional Notes:
- Ensure the versions of MS Excel, MS SQL Server, and Power BI match the specified requirements for accurate analysis.
- Follow formatting guidelines for visuals in the Power BI dashboard as described above for consistency and clarity.

## Contributors:
## Contributors:
- Apeksha Gangurde ([GitHub](https://github.com/apekshagangurde))
- Mansi Joshi ([GitHub](https://github.com/mansijosh))


