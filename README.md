E-commerce Sales Analysis with Pandas
This project performs an in-depth Exploratory Data Analysis (EDA) on the "Sample Superstore" dataset. The primary goal is to leverage the Pandas library in Python to clean the data, ask key business questions, and generate insightful summary reports. This repository showcases a complete workflow from raw data to actionable business intelligence, performed entirely within Pandas.

Dataset
The data used is the "Sample - Superstore" dataset, which contains transactional data for a fictional e-commerce store. It includes detailed information on orders, products, customers, and sales figures. The dataset was sourced from Kaggle.

Tools and Libraries
Python

Pandas

Jupyter Notebook

Project Workflow
The project was divided into two main phases:

1. Data Cleaning and Preparation:

Loaded the raw .xls file, requiring the xlrd library.

Conducted an initial inspection to check for missing values and incorrect data types using .info() and .isnull().sum().

Converted the 'Order Date' column to a proper datetime format to enable time-series analysis.

2. Exploratory Data Analysis (EDA) and Reporting:

Feature Engineering: Created new 'Year' and 'Month' columns from the 'Order Date' to facilitate monthly analysis.

Answering Business Questions: The core of the project was to answer key business questions by manipulating and aggregating the data, such as:

What are the overall sales and profit trends on a monthly basis?

Which are the top 10 most profitable products for the store?

How does sales performance differ across various regions and product categories?

Generating Reports: Based on the analysis, three distinct summary reports were generated.

Reports Generated
The final deliverables of this analysis are three CSV files, each providing a specific business insight:

monthly_sales_report.csv: A summary of total sales and profit for each month and year.

top_10_profitable_products.csv: A list of the top 10 products ranked by total profit.

sales_by_region_category.csv: A pivot table showing the breakdown of sales by region and product category.

Repository Structure
├── E-commerce-Analysis.ipynb         # The main Jupyter Notebook with all the cleaning and analysis steps.
├── US Superstore data.xls            # The raw, original dataset.
├── monthly_sales_report.csv          # Report 1: Monthly sales and profit.
├── top_10_profitable_products.csv    # Report 2: Top 10 profitable products.
└── sales_by_region_category.csv      # Report 3: Sales broken down by region and category.
How to Run
To replicate the analysis:

Clone this repository to your local machine.

Ensure you have Python, Pandas, and xlrd installed (pip install pandas xlrd).

Open and run the E-commerce-Analysis.ipynb notebook in a compatible environment like Jupyter Lab or Visual Studio Code.
