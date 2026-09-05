# online-retail-python-analysis
End-to-end Online Retail Sales Analysis using Python, Pandas, NumPy, Matplotlib and Seaborn.

## 📌 Project Overview

This project performs an end-to-end analysis of an Online Retail transactional dataset using Python.

The project focuses on data cleaning, exploratory data analysis, sales performance, customer behavior, product performance, country-wise analysis, and time-based sales trends.

## 🎯 Business Objectives

- Analyze overall retail sales performance
- Identify top-performing products
- Identify high-value customers
- Analyze country-wise revenue and orders
- Understand monthly sales trends
- Analyze returned transactions
- Identify unusual transactions and outliers
- Generate actionable business recommendations

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset

The dataset contains online retail transaction records with information such as:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## 🔍 Analysis Performed

### Data Cleaning
- Checked missing values
- Removed duplicate records
- Converted date columns into datetime format
- Identified negative quantities and return transactions
- Removed invalid transactions where required

### Exploratory Data Analysis
- Revenue analysis
- Product performance analysis
- Country-wise revenue analysis
- Country-wise order analysis
- Customer analysis
- Monthly sales trend analysis
- Revenue distribution analysis
- Outlier analysis

### Feature Engineering

Revenue was calculated using:

`Revenue = Quantity × UnitPrice`

## 💡 Key Insights

The analysis identifies the major revenue-generating countries, high-performing products, valuable customers, sales trends, and patterns in returned transactions.

## 📈 Visualizations

The project uses Matplotlib and Seaborn to visualize:

- Revenue distribution
- Country-wise revenue
- Product performance
- Customer performance
- Monthly sales trends
- Other key business metrics

## 💼 Business Recommendations

- Focus marketing efforts on high-value customers.
- Strengthen sales strategies in high-revenue countries.
- Promote consistently high-performing products.
- Investigate unusually large transactions and return patterns.
- Use monthly sales trends for inventory and demand planning.

## 📁 Project Structure

```text
online-retail-python-analysis/
│
├── Online_Retail_Analysis.ipynb
└── README.md
