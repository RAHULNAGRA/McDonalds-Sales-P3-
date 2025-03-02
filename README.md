# McDonald's Sales Analysis Project-P3-

## Project Overview:
This project focuses on analyzing McDonald’s US sales data using Excel to create an interactive, dynamic dashboard.
The goal is to explore key sales metrics, item popularity, customer preferences, and time-based trends, offering actionable insights to support business decisions and strategy optimization.

**McDonald's Sales**
Create an interactive and dynamic dashboard in Excel using the McDonald's sales dataset to analyze various aspects of sales performance, item popularity, customer preferences, and time-based trends. The dashboard should provide actionable insights and allow for easy data exploration.

## Dataset:
The dataset provides detailed information on orders, menu items, and the time of orders, enabling a comprehensive analysis of McDonald's sales performance across various dimensions.

**Dataset Link:** https://drive.google.com/drive/folders/1raeubcRpUisUUuDyY6ezvfc7VHHydpoV

Before performing analysis, check for duplicates and in case of null values, utilize forward/backward fill.

**Questions**:
1. What is the total sales revenue for each category of menu items?
2. How many orders are placed each day?
3. Which menu item is the most frequently ordered?
4. What is the total revenue generated by menu items?
5. How does the revenue of each category compare over months?
6. What is the average number of items per order?
7. How do order volumes vary by time of day?
8. How do sales trends differ across weekdays and weekends?
9. How does the sales performance vary by category over different months?
10. Compare the sales of top 5 menu items.

## Data Cleaning:
- Removed duplicate records.
- Handled missing values using forward and backward fill methods to maintain data consistency.
- Corrected data types for all columns, especially date and time formats, aligning with the English US locale.

## Data Transformation:
- Created new columns such as `Exact Hours`, `Meal of the Day`, and `Time of Day` based on order time.
- Merged menu item prices with order details using common keys like `item_id` and `menu_item_id`.
- Added features like `Day Name`, `Month Name`, `Day of Week`, and flagged orders as `Weekend` or `Weekday`.

## Data Analysis & Dashboard:
Using Power Pivot in Excel, relationships between tables were established, and the data model was used to create pivot tables and measures. This led to the development of a dynamic dashboard that provides visual insights into McDonald’s sales performance.

### Key Insights:
- **Sales by Time of Day**: Peak sales occur during lunch (12 PM - 2 PM) and dinner (6 PM - 8 PM).
- **Top 5 Menu Items**: The `Meatball Marinara` is the top-selling item, generating the highest revenue.
- **Revenue by Category**: The `Burger` category contributes the most to total revenue, followed by `Chicken` and `Fries`.
- **Sales Trends**: Weekend sales are higher, with Saturday showing the highest sales volume.
- **Order and Revenue Correlation**: Higher order volumes correspond with higher revenue generation.

### Key Questions Answered:
1. What is the total sales revenue for each category of menu items?
2. How many orders are placed each day?
3. Which menu item is the most frequently ordered?
4. How does the revenue compare over months for each category?
5. What is the average number of items per order?
6. How do sales volumes vary by time of day and day of the week?
7. How does sales performance differ across weekdays and weekends?
8. What are the sales and revenue trends for the top 5 menu items?

## Strategic Recommendations:
- **Optimize Pricing Strategy**: Review the pricing of top-selling and low-revenue items to improve profit margins.
- **Promote Low-Performing Categories**: Target promotions for categories like `Shakes` and `Sides` to drive sales growth.
- **Midweek Promotions**: Introduce special offers to boost sales during midweek, especially on Wednesdays when sales typically dip.

## Conclusion:
This project demonstrates the power of data-driven insights for improving operational efficiency and revenue strategies at McDonald's. The dashboard serves as a powerful tool for decision-makers to monitor performance, identify areas for improvement, and develop targeted marketing campaigns.

