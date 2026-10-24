
# Retail Sales Analysis

An individual Data Analyst portfolio project using Python to explore retail sales, profitability, and discount patterns.

## Project Overview

This project analyzes the Sample Superstore dataset to understand sales performance and profitability across product categories and sub-categories.

The analysis focuses on identifying top-performing products, loss-making product groups, and the relationship between discounts and profit.

## Tools & Technologies

- Python 3.13
- Pandas
- Matplotlib
- Jupyter Notebook
- VS Code

## Dataset

- Source: Tableau Public Sample Data
- Records: 10,194 rows
- Attributes: 21 columns
- Main variables: Sales, Profit, Quantity, Discount, Category, Sub-Category, and Region.

## Analysis Performed

1. Dataset exploration and data quality checks.
2. Descriptive statistical analysis.
3. Sales analysis by product category.
4. Profit analysis by category and sub-category.
5. Discount and profitability analysis.
6. Data visualization using Matplotlib.

## Key Findings

- Technology recorded the highest total sales at approximately 839,893.28.
- Technology also recorded the highest category profit at approximately 146,543.38.
- Copiers had the highest sub-category profit at approximately 56,093.94.
- Tables recorded the largest sub-category loss at approximately 17,753.21.
- For Tables, transactions with discounts of 20% to 50% collectively recorded negative profit.

These findings show an observed relationship between discount levels and profitability. They do not establish that discounts alone caused the losses.

## Business Recommendations

- Review discount policies for the Tables sub-category.
- Evaluate product pricing and costs for loss-making products.
- Monitor profitability alongside sales performance.
- Prioritize products and categories with stronger profit contributions.

## Project Structure

```text
retail-sales-analysis/
├── data/
│   └── sample_-_superstore.xls
├── notebooks/
│   └── retail-sales-analysis.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Install Python.
2. Install the required libraries using:

```bash
pip install -r requirements.txt
```

3. Open the project folder in VS Code.
4. Open `notebooks/retail-sales-analysis.ipynb`.
5. Select a Python kernel and run the notebook cells.

## Author

Pasha Adjie Pratama

Individual Portfolio Project — Retail Sales Analysis

## Hasil Analisis

### 1. Analisis Penjualan Berdasarkan Kategori
![Sales by Category](sales%20by%20category.png)

### 2. Analisis Profit Berdasarkan Sub-Category
![Profit by Sub-Category](profit%20by%20sub-category.png)

### 3. Analisis Dampak Diskon terhadap Profit
![Profit by Discount](profit%20by%20discount.png)
