# Indian Retail EDA

Explanatory data analysis of Indian retail transaction data using Python and Pandas to understand sales, profitability, products, regions, customer segments, discounts, and operational performance.

## Project Overview

This project presents an explanatory data analysis of retail transaction data from an Indian retail business.

The analysis focuses on identifying patterns in sales, profit, product performance, regional performance, customer segments, discounts, freight operations, loss-making transactions, and order priorities.

The project was developed using a Jupyter Notebook and Python-based data analysis techniques.

##  Objectives

The main objectives of this project are:

- Explore the characteristics and quality of the retail dataset.
- Clean and preprocess the data before analysis.
- Analyse sales and profitability over time.
- Compare product types and product sub-categories.
- Examine performance across different regions.
- Analyse customer segment performance.
- Investigate the relationship between discounts and profitability.
- Examine freight modes and operational performance.
- Identify characteristics associated with loss-making transactions.
- Analyse the relationship between order priority and delivery performance.

##  Business Questions

The project addresses the following business questions:

1. How have sales and profitability changed over time?
2. Which product types and product sub-categories generate the highest sales and profit?
3. How does sales and profitability performance differ across India's regions?
4. How does purchasing and profitability performance differ between customer segments?
5. What is the relationship between discounts and sales profitability?
6. How does freight mode relate to delivery time, freight expenses, and profitability?
7. What characteristics are associated with loss-making transactions?
8. How does order priority relate to delivery time, sales, and profitability?

##  Dataset

The dataset contains retail transaction records from an Indian retail business.

### Dataset Variables

The main variables include:

| Variable | Description |
|---|---|
| Order Priority | Priority level assigned to an order |
| Discount offered | Discount applied to the transaction |
| Unit Price | Price per unit |
| Freight Expenses | Freight or shipping expense |
| Freight Mode | Method used for freight delivery |
| Segment | Customer/business segment |
| Product Type | Type of product |
| Product Sub-Category | Product sub-category |
| Product Container | Type of product container |
| State | Indian state |
| City | City of the transaction |
| Region | Geographical region |
| Country | Country |
| Order Date | Date of the order |
| Ship Date | Date the transaction was shipped |
| Profit | Profit or loss from the transaction |
| QtyOrdered | Quantity ordered |
| Sales | Sales value |

### Dataset Source

Dataset URL:

[Add the original dataset URL here]

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

##  Data Analysis Process

The project follows an explanatory data analysis pipeline consisting of the following stages:

### 1. Business Context

The business context explains the retail company, the available transaction data, and the need for data analysis to support business decision-making.

### 2. Data Exploration

The dataset was explored to understand:

- Dataset dimensions
- Variable names and data types
- Missing values
- Duplicate records
- Numerical variables
- Categorical variables
- Date ranges
- Geographical information
- Sales and profit distributions

### 3. Data Preprocessing

The preprocessing stage includes:

- Converting order and shipping dates into datetime format
- Calculating delivery days
- Calculating profit margin
- Extracting year and month information
- Creating profitability categories
- Checking for missing values
- Checking for duplicate records
- Validating the processed dataset

### 4. Explanatory Data Analysis

The analysis uses different Python and Pandas techniques to investigate the eight business questions.

Key techniques include:

- `groupby()`
- `agg()`
- `sort_values()`
- `corr()`
- `pd.cut()`
- Filtering
- Date-based analysis
- Aggregation
- Data visualisation

## Key Analysis Areas

### Sales and Profitability Over Time

Annual sales and profit are analysed to identify changes in business performance between 2010 and 2013.

### Product Performance

Product types and product sub-categories are compared using sales, profit, quantity, and transaction-level measures.

### Regional Performance

Sales and profitability are compared across different regions of India to identify geographical differences in business performance.

### Customer Segment Analysis

Customer segments are analysed based on sales, profit, quantity, and transaction activity.

### Discount Analysis

The relationship between discount levels, sales, and profit is examined using correlation analysis and discount bands.

### Freight Analysis

Different freight modes are compared using delivery time, freight expenses, sales, and profitability measures.

### Loss-Making Transactions

Loss-making and profit-making transactions are compared to identify patterns across products, segments, and discount levels.

### Order Priority

Order priority categories are analysed in relation to delivery time, sales, and profitability.

## Project Structure

```text
Indian-Retail-EDA/
│
├── README.md
│
├── INDIA_RETAIL_DATA.xlsx
│
├── Indian_Retail_EDA.ipynb
│
└── Indian_Retail_EDA.html
```


### Main Findings

The analysis provides insights into:

- Changes in sales and profitability over time.
- Differences in performance between product types and sub-categories.
- Regional variations in sales and profitability.
- Differences between customer segments.
- The relationship between discount levels and profitability.
- Differences between freight modes in delivery and financial performance.
- Patterns associated with loss-making transactions.
- The relationship between order priority and operational performance.
