# blinkit-Dashboard
📊 Blinkit Power BI Dashboard

A Complete Sales, Outlet & Item Performance Analysis

This project presents an interactive Power BI dashboard built using Blinkit grocery data.
The report provides deep insights into sales performance, outlet distribution, item categories, customer ratings, and operational trends.

2.Dashboard Preview

🚀 Project Overview

The goal of this project is to analyze Blinkit’s business performance using interactive visualizations.
The dashboard allows stakeholders to understand:

Total sales performance

Average sales & customer ratings

Outlet segmentation (size, location, establishment year)

Item category contributions

Fat content analysis

Year-wise sales trends

Comparison among outlet types

This dashboard is designed with a clean UI/UX and business-focused insights.

🎯 Key Features
1. KPI Cards

Total Sales: $1.20M

Average Sales: $141

Number of Items: 8523

Average Rating: 3.9

2. Slicers for Dynamic Filtering

Outlet Location

Outlet Size

Item Type

3. Charts & Insights

Sales Trend Over Years

Outlet Size Sales Contribution (Donut Chart)

Outlet Location Sales (Bar Chart)

Item Type Sales Ranking (Horizontal Bars)

Fat Content Comparison (Donut + Bars)

Outlet-Wise Sales & Ratings Table

 Dataset Details

The dashboard uses the following datasets:

1. Metrics Table

Contains KPI measures such as total sales, avg sales, avg rating, etc.

2. BlinkIT Grocery Data

Includes:

Item type

Item sales

Fat content

Outlet type

Outlet establishment year

Item visibility

Outlet size & location

📐 Data Model

The data model is built with a single fact table supported by KPI measures created using DAX.

🧮 DAX Measures Used

Below are examples of key measures (you can expand this section based on your file):

Total Sales = SUM('BlinkIT Grocery Data'[Item Outlet Sales])

Average Sales = AVERAGE('BlinkIT Grocery Data'[Item Outlet Sales])

Number of Items = DISTINCTCOUNT('BlinkIT Grocery Data'[Item Identifier])

Average Rating = AVERAGE('BlinkIT Grocery Data'[Item Rating])


More DAX expressions (Yearly Sales, Outlet Segment Sales, etc.) can be added.

🖥️ Tools & Technologies

Power BI Desktop

DAX

Data Modeling

ETL (Power Query)

CSV / Excel Data Files

📦 How to Use This Project

Clone the repository

Open the .pbix file in Power BI Desktop

Load/refresh data

Explore the dashboard interactively

🎯 Key Insights Extracted

✔ Tier-3 outlets contribute the highest sales
✔ High-size outlets generate maximum revenue
✔ Fat content has minimal effect on sales
✔ Establishment year impacts revenue stability
✔ Household & Dairy items are top-performing categories

🤝 Contribution

Feel free to fork this repo, improve visuals, add DAX optimization, or redesign the UI.

📬 Contact

If you want help improving your BI portfolio or building advanced dashboards:

Sachin Kumar
sachinkumar56846@gmail.com
