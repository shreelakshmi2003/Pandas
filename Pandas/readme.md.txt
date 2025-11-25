📦 E-Commerce Data Analysis Project
Python • Pandas • NumPy • Data Cleaning • Exploratory Data Analysis

A complete end-to-end data analysis project performed on the Online Retail Dataset, covering data cleaning, preprocessing, feature engineering, grouping, advanced analysis, and report generation.
This project demonstrates how Python and Pandas can be used to transform raw e-commerce data into meaningful business insights.

🎯 Project Overview

The goal of this project is to explore, clean, and analyze the Online Retail dataset, discovering trends in customer purchasing behavior, product performance, revenue patterns, and country-wise sales insights.

The project is divided into multiple structured parts, each focusing on a key analytical skill:

Data exploration

Data cleaning

Feature extraction

Text processing

Filtering and selection

Aggregation and grouping

Country, customer, product, and time-series analysis

External data integration

NumPy operations

Exporting summaries and documentation

This project provides a hands-on understanding of real-world data preprocessing and analytical workflows.

✨ Key Features
🧹 Data Cleaning Pipeline

Removed missing IDs, duplicates, and invalid rows

Standardized product names and countries

Normalized price and quantity columns

Converted date fields for time-series analysis

🏷 Feature Engineering

Created several derived columns such as:

TotalPrice

Year, Month, Day, Hour

DayOfWeek & Quarter

RevenueCategory & OrderSize

Product name length

Monthly revenue percentage

Customer revenue rank

Cumulative revenue

🔍 Exploratory Data Analysis

Performed detailed analysis including:

Country-wise revenue

Monthly and quarterly trends

Top customers & top products

Order patterns by quantity, hour, and day

Popular categories per country

Category revenue distribution

📚 Text-Based Insights

Generated a separate insights text file summarizing findings from the dataset.

🔗 External Data Integration

Created synthetic Customer Information dataset

Created Product Category dataset

Merged with sales data for enhanced analysis

🧮 NumPy Operations

Implemented array-based:

Mathematical operations

Statistical computations

Matrix creation

Filtering and normalization

Percentile, correlation, and splitting tasks

🚀 Getting Started
✅ Prerequisites

Python 3.8+

Jupyter Notebook or VS Code

Required Libraries:

pip install pandas numpy openpyxl

📂 Running the Project

Load the dataset

Run the notebook section-by-section

Follow Parts A to S

View outputs and summaries

Export final results to CSV, Excel, and TXT

📁 Project Structure
ecommerce-analysis/
│
├── data/                         # Original and cleaned datasets
├── analysis_notebook.ipynb       # Main project notebook
├── customer_info.csv             # Synthetic customer data
├── product_categories.csv        # Synthetic product categories
├── sales_insights.txt            # Insights summary
└── README.md                     # Project documentation

📖 Learning Objectives

By completing this project, you will learn how to:

Clean and preprocess large datasets

Perform exploratory analysis using Pandas

Engineer meaningful features

Aggregate, group, and summarize business data

Build country-wise, monthly, and customer-level reports

Combine multiple datasets using merge and join

Use NumPy for mathematical and statistical tasks

Export files in CSV, Excel, and TXT formats

Document insights professionally

🔧 Key Pandas & NumPy Functions Demonstrated
Category	Functions Used
Data Cleaning	dropna(), drop_duplicates(), replace(), astype(), rename()
Feature Creation	dt.year, dt.month, cut(), where(), assign()
Aggregation	groupby(), agg(), nunique(), size(), idxmax()
Sorting	sort_values(), nlargest(), nsmallest()
Text Processing	str.upper(), str.strip(), str.contains(), str.startswith()
NumPy	array(), linspace(), sqrt(), percentile(), reshape(), random.choice()
📊 Sample Insights

The UK generates the highest revenue among all countries

Some product categories dominate sales across multiple regions

A few customers contribute significantly to overall revenue

Seasonal patterns and monthly variations impact sales volume

High-revenue transactions are rare but impactful

🎓 Use Cases

This project is ideal for:

Data analytics learning

E-commerce business intelligence

Interview preparation

Pandas & NumPy skill-building

Portfolio projects

🤝 Contributing

You can contribute by:

Adding new visualizations

Improving customer/product analytics

Expanding NumPy practice modules

Enhancing dashboards or summaries

👩‍💻 Author

P P Shree Lakshmi
📧 Email: shreelakshmipp@gmail.com

🌐 LinkedIn: www.linkedin.com/in/shree-lakshmi-b9a769239

💻 GitHub: https://github.com/shreelakshmi2003

⭐ If you found this project useful, give it a star on GitHub!

Happy Analyzing! 📊