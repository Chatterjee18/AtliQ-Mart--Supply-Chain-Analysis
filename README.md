  # AtliQ Mart Supply Chain Analysis 



Live Dashboard - [PowerBI](https://app.powerbi.com/groups/me/reports/949c5632-04ad-4a52-861d-fa123e3a4002/eb422f36245a3cc37a5b?experience=power-bi)

This Power BI project comprehensively analyzes AtliQ Mart's supply chain performance. The dashboard offers key insights into metrics like on-Time Deliveries (OT), in-Full Orders (IF), on-Time in Full (OTIF), and Volume Fill Rate (VOFR). The focus is on optimizing delivery performance, order fulfillment, and understanding the delays in the supply chain.

🔑 Key Metrics
OT (On Time Deliveries)
Measures how efficiently orders meet the delivery timeline.
Current Performance: 59.03%
Target: 86.09%

IF (In Full Orders)
Represents the percentage of orders fulfilled completely without shortages.
Current Performance: 52.78%
Target: 76.51%

OTIF (On Time In Full)
Combines OT and IF to provide a measure of perfect order deliveries.
Current Performance: 29.02%
Target: 65.91%

TQS (Total Quantity of Sales)
Total number of units sold across all customers.
Sales Volume: 12.97M units

TQO (Total Quantity of Orders)
Total number of units ordered by customers.
Order Volume: 13.43M units

VOFR (Volume Fill Rate)
Percentage of total demand that was fulfilled.
Current Performance: 96.59%

ADD (Average Delay Day)
The average delay in days for deliveries beyond the expected date.
Current Delay: 1.71 days

📈 Visualizations
1. OT, IF, and OTIF Performance vs Target
Comparative visual representation of actual performance against target goals for On-Time Deliveries, In Full Orders, and On Time In Full metrics, broken down by city (Surat, Ahmedabad, Vadodara).

2. Customer Analysis
Analysis of delivery performance for key customers like Acclaimed Stores, Atlas Stores, and Coolblue, focusing on OT, IF, OTIF, and Average Delay Day (ADD).

3. Product Analysis
Performance of various products, including AM Biscuits, AM Butter, and AM Ghee, highlighting OT, IF, OTIF percentages, and delay trends.

4. Order vs Sales by Delay Day
A scatter plot comparing sales volume and order volume, categorized by the delay days to identify patterns of underperformance.

⚙️ Project Features
Conditional Formatting: Color-coded KPIs based on the gap between actual performance and targets.
Dynamic Filters: Ability to filter data by week, city, product, and customer to focus on specific areas of interest.
Interactive Dashboard: Drill down into specific metrics to explore further details, like city-wise or customer-wise performance.
🚀 How to Run This Project
Open the Power BI file (.pbix) on the Power BI Desktop.
Explore the dashboards and filters to interact with the data.
Use slicers to customize views and focus on specific cities, products, or customers.
The visuals are updated dynamically based on the selected filters.
📄 Insights
Delivery Performance: Overall delivery performance is significantly below the target, with a large gap in OTIF scores.
Product and Customer Trends: Certain products and customers consistently perform better in OT and IF metrics, providing potential areas for optimization.
Delay Analysis: Average delay days of 1.71 are relatively low, but they have a considerable impact on OTIF performance.
🛠️ Tools & Technologies
Power BI Desktop
SQL Databases (for data source)
DAX Calculations (for advanced metrics)

# Data Model

![Screenshot 2025-01-12 191156](https://github.com/user-attachments/assets/c12f8666-7b06-490e-8668-fc7d8523f739)

# Dashboard
![AtliQ Mart Analysis_page-0001](https://github.com/user-attachments/assets/4c94c4b0-6dcb-4cb2-8fd4-cc303820ce5f)

# Some Major Insights

All the Key Metrics (OT%, IF%, OTIF%) are far behind the target

On average, orders are delayed 0.42 days from the agreed date of delivery

Lotus Mart, and Coolblue, Acclaimed stores have the highest orders as well as delayed the most to deliver the products on time

Is it because we are not estimating the right delivery date?

Is it because we are receiving more orders than expected?

Ghee, curd, and butter products are most delayed in delivery.

There are no noticeable improvements in any of the key metrics in the last few months

There is a huge gap in IF% for most of the customers. Is it because of less production?
