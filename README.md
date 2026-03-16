# Retail Sales Performance Dashboard

## Project Overview
This project analyzes retail sales data to understand business performance across products, customers, cities, and time. The goal of the project was to transform raw transactional data into meaningful business insights using data analysis and visualization.

The project was completed using Excel for initial data exploration and Microsoft Power BI for building an interactive dashboard.

---

## Tools Used
- Microsoft Excel – Data preparation and pivot table analysis
- Microsoft Power BI – Interactive dashboard creation
- DAX – Creating calculated metrics

---

## Dataset Description
The dataset contains retail transaction records with the following fields:

- City
- Customer Name
- Month
- Order Date
- Order ID
- Payment Method
- Product Category
- Product Name
- Quantity
- Unit Price
- Total Revenue

Total records: 41

---

## Key Metrics
- Total Revenue: ₹908,000
- Total Orders: 41
- Total Customers: 32
- Average Order Value: ₹22,150

Average Order Value was calculated using DAX:

```
Average Order Value =
DIVIDE(SUM('Dataset'[Total Revenue]), COUNT('Dataset'[Order ID]))
```

---

## Dashboard Features
The Power BI dashboard provides insights into:

- Revenue by Product Category
- Revenue by City
- Monthly Revenue Trends
- Top Products by Revenue
- Top Customers by Revenue
- Interactive filters for City and Product Category

These visualizations help identify high-performing products, valuable customers, and geographic sales patterns.

---

## Business Insights
Some key observations from the analysis:

- The Electronics category generated the highest revenue.
- A small group of customers contributed a significant portion of the total revenue.
- Sales varied across cities, indicating geographic performance differences.
- Average Order Value was relatively high, indicating larger purchase sizes.

---

## Files in This Repository
- Retail-Sales-PowerBI-Dashboard.xlsx Excel File containing Dataset, Pivot Tables
- dashboard.pbix – Power BI dashboard file
- dashboard_screenshot.png – Dashboard preview
- README.md – Project documentation

---


## Learning Outcomes
Through this project I gained practical experience in:

- Data analysis
- Data visualization
- Business insight generation
- Power BI dashboard design
- Creating calculated metrics using DAX

---

## Future Improvements
Potential future improvements include:

- Profit analysis
- Time intelligence (month-over-month growth)
- Forecasting future sales trends
- Integrating SQL-based datasets

---

## Author
Bhavana Reddymachu

Aspiring Data Analyst | Learning Data Analytics and Business Intelligence
