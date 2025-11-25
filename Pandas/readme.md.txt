📦 E-Commerce Data Analysis Project
Python • Pandas • NumPy • Data Cleaning • Exploratory Data Analysis

This project performs a complete end-to-end analysis of the Online Retail Dataset, transforming raw e-commerce transaction data into clean, structured insights.
It demonstrates key skills in data cleaning, feature engineering, aggregation, visualization planning, and business-focused analysis using Python.

📊 Overview

The Online Retail dataset contains invoice-level transaction data with customer purchases, product details, timestamps, and pricing information.
Using Python and Pandas, this project cleans the data, enriches it with new features, and analyzes it from multiple perspectives—customer behavior, product performance, and country-level trends.

Key steps in the workflow include:

Cleaning missing, invalid, and duplicate data

Handling cancelled transactions

Creating new analytical features

Filtering and summarizing sales

Customer, product, and time-based insights

Integrating synthetic customer and product category data

Generating documented insights

✨ Features Implemented
🧹 Data Cleaning

Removed missing CustomerIDs

Dropped duplicate rows

Removed cancelled invoices (InvoiceNo starting with “C”)

Removed invalid Quantity and UnitPrice values

Standardized product names and country values

Converted InvoiceDate to proper datetime format

🏷 Feature Engineering

Added several useful analytical columns:

TotalPrice (Quantity × UnitPrice)

Year, Month, Day, Hour (from InvoiceDate)

DayOfWeek and Quarter

RevenueCategory (Low / Medium / High based on TotalPrice)

OrderSize (Small / Medium / Large based on Quantity)

Length of Product Name

Percentage of Monthly Revenue

Customer Spending Rank

Cumulative Revenue

🔍 Exploratory Insights

Analysis covers:

Country-wise and monthly revenue trends

Top customers by spending

Most purchased and highest-revenue products

Popular categories in each country

High-value transactions and outliers

Daily and hourly sales patterns

Year-over-year comparison

🔗 External Data Integration

Synthetic datasets were created to enrich analysis:

Customer Information Dataset

CustomerID

CustomerName

MembershipLevel

JoinDate

Product Categories Dataset

StockCode

Category

Both datasets were merged with the main sales data to derive deeper insights such as revenue by membership level and category popularity across countries.

🧮 NumPy Operations

Implemented practical NumPy tasks including:

Array creation and mathematical operations

Statistical analysis (percentiles, correlation, summary statistics)

Normalization & filtering

Generating random arrays and matrices

📁 Export & Reporting

Cleaned dataset exported to CSV and Excel

Multi-sheet Excel report created (country summary, monthly revenue, top customers)

Generated a text-based insight report summarizing findings

🔧 Technologies Used

Python

Pandas

NumPy

OpenPyXL (Excel export)

Jupyter Notebook / VS Code

📖 Key Pandas & NumPy Functions Demonstrated
Category	Functions
Data Cleaning	dropna(), drop_duplicates(), replace(), astype()
Date Handling	.dt.year, .dt.month, .dt.day, .dt.weekday, .dt.hour
Feature Creation	cut(), where(), string operations
Grouping	groupby(), agg(), nunique(), size()
Sorting	sort_values(), nlargest(), nsmallest()
Text	str.contains(), str.startswith(), str.upper(), str.strip()
NumPy	array(), linspace(), percentile(), sqrt(), random.choice()
📈 Sample Insights

UK is the highest-revenue country by a large margin.

A small number of customers contribute significantly to total revenue.

Certain product categories (Home, Kitchen, Gift, Stationery, etc.) dominate sales.

Sales peak during specific months with visible seasonal patterns.

Weekday vs weekend sales show clear behavioral differences.

High-value transactions are rare but heavily influence revenue trends.

📂 Project Structure
ecommerce-analysis/
│
├── cleaned_data/                # Final cleaned dataset
├── customer_info.csv            # Synthetic customer dataset
├── product_categories.csv       # Synthetic category dataset
├── sales_insights.txt           # Insight summary
├── analysis_notebook.ipynb      # Full Jupyter Notebook
└── README.md                    # Project documentation

👩‍💻 Author

P P Shree Lakshmi
📧 Email: shreelakshmipp@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/shree-lakshmi-b9a769239

💻 GitHub: https://github.com/shreelakshmi2003

⭐ If you found this project helpful, consider starring the repository!

Happy Analyzing! 📊✨
