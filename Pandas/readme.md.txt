📦 E-Commerce Data Analysis – Online Retail Dataset

Python • Pandas • NumPy • Jupyter Notebook

A complete data analysis project demonstrating how Python and Pandas can be used to clean, transform, and analyze large-scale e-commerce transaction data.
This project walks through real-world retail data and extracts meaningful insights through structured data preparation, feature engineering, and exploratory analysis.

🎯 Project Overview

The E-Commerce Data Analysis project explores transactional retail data to understand sales trends, customer behavior, and product performance. It provides a practical walkthrough of:

Cleaning messy datasets

Adding meaningful analytical features

Performing country-wise and time-based analysis

Evaluating customer and product patterns

Integrating custom customer and product category datasets

Exporting summaries and documentation

This notebook simulates real-world analytics workflows commonly used in data science teams.

✨ Features
Module 1: Data Cleaning

Handle missing CustomerID values

Remove duplicate and invalid rows

Remove cancelled invoices

Fix negative or zero Quantity and UnitPrice

Standardize ProductName and Country fields

Convert InvoiceDate to proper datetime format

-----------------------------------------------------------------------------------------------------------------

Module 2: Feature Engineering

Compute TotalPrice

Extract Year, Month, Day, Hour

Generate DayOfWeek and Quarter

Create RevenueCategory (Low, Medium, High)

Create OrderSize (Small, Medium, Large)

Calculate length of product names

Generate monthly revenue percentage

Rank customers by spending

Compute cumulative revenue

-----------------------------------------------------------------------------------------------------------------

Module 3: Exploratory Analysis

Revenue by Country

Monthly and quarterly sales patterns

Top customers by spending

Top products by quantity and revenue

High-value transactions

Weekend vs weekday analysis

Hourly purchasing patterns

Popular product categories across countries

-----------------------------------------------------------------------------------------------------------------

Module 4: External Data Integration

Synthetic Customer Information dataset

Synthetic Product Categories dataset

Combine both with original transactions

Analyze membership-level revenue

Identify most popular category per country

-----------------------------------------------------------------------------------------------------------------

Module 5: NumPy Practice

Array creation and filtering

Element-wise operations

Percentiles and correlation

Normalization

Random ID generation

Splitting arrays

Matrix creation

-----------------------------------------------------------------------------------------------------------------

🚀 Getting Started
Prerequisites

Python 3.8+
NumPy
Pandas
Jupyter Notebook or any Python IDE

Installation

Clone the repository:

git clone your-repository-link
cd ecommerce-analysis


Install dependencies:

pip install pandas numpy openpyxl

💻 Running the Notebook

Option 1: Jupyter Notebook

jupyter notebook


Open the analysis notebook and run all cells.

Option 2: Google Colab

Upload the notebook

Run all cells online

Option 3: VS Code

Install Python and Jupyter extensions

Open the .ipynb file

Run cells directly

📊 Sample Insights
Top spending country: United Kingdom
Highest revenue month: November 2011
Most purchased category: Gift Items
Top customer spending: £15,000+
Peak sales hour: 12:00–13:00


Examples of analysis:

Popular categories differ across countries

High-value transactions represent a small portion but contribute heavily to revenue

Seasonal trends show increased activity towards year-end

Many customers purchase only once, while a few contribute a large share of revenue

📖 Learning Objectives

After completing this analysis, you will understand how to:

Clean and structure large datasets

Create analytical features from timestamps

Analyze country and customer patterns

Build category-level and product-level summaries

Use NumPy for quantitative operations

Merge external datasets effectively

Export insights and create structured documentation

🔧 Key Functions Demonstrated
Category	Functions
Cleaning	dropna, drop_duplicates, replace, astype
Date Handling	dt.year, dt.month, dt.day, dt.hour
Aggregation	groupby, agg, nunique, size, idxmax
Sorting	sort_values, nlargest, nsmallest
Text Processing	str.contains, str.upper, str.strip
NumPy	array, linspace, percentile, sqrt, random.choice
📁 Project Structure
ecommerce-analysis/
│
├── ecommerce_analysis.ipynb     # Main notebook
├── cleaned_data.csv             # Cleaned dataset
├── customer_info.csv            # Synthetic customer dataset
├── product_categories.csv       # Synthetic product categories
├── sales_insights.txt           # Insight summary
└── README.md                    # Project documentation

💡 Use Cases

This project can be adapted for:

Retail and e-commerce analytics

Customer segmentation

Product performance dashboards

Sales forecasting preparation

Academic and learning use

Interview portfolio demonstrations

🎓 How to Use

Run the notebook step by step

Explore the outputs after each section

Modify analysis for your own use case

Add new features or metrics

Export updated results

🤝 Contributing

You can contribute by:

Adding visualizations

Adding advanced analytics

Improving documentation

Extending category or customer datasets

Enhancing performance

To contribute:

git fork your-repository-link
git checkout -b feature/Improvement
git commit -m "Added improved analysis"
git push origin feature/Improvement

📝 License

This analysis project is released under the MIT License.

👩‍💻 Author

P P Shree Lakshmi
Email: shreelakshmipp@gmail.com

GitHub: github.com/shreelakshmi2003
LinkedIn: add-your-link

🙏 Acknowledgments

Pandas documentation

NumPy documentation

Jupyter Notebook

Online Retail dataset

📚 Additional Resources

Python Data Science Handbook

Pandas Official Guide

NumPy Beginner Tutorials

Data Analysis with Python articles

⭐ If you found this project useful, consider giving it a star!
Happy Analyzing! 📊✨