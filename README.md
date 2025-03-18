# Retail Orders Analysis

This repository contains a series of SQL queries and Python scripts used to analyze retail orders data. The analysis includes extracting, cleaning, transforming, and performing advanced analytics on retail sales data. This project utilizes Kaggle datasets and SQL queries to generate insights about sales trends, product performance, regional sales, and year-over-year growth.

## Project Overview

This project aims to analyze retail orders data, calculate key metrics, and derive insights that can drive business decision-making. The analysis includes:

- **Top 10 Highest Revenue Generating Products**: Identifying the products with the highest total sales.
- **Top 5 Highest Selling Products in Each Region**: Ranking products within regions based on sales.
- **Month Over Month Growth Comparison for 2022 and 2023**: Comparing sales performance for each month across two years.
- **Highest Sales Month for Each Category**: Finding the month with the highest sales per category.
- **Sub-Category Growth in Profit from 2022 to 2023**: Identifying which sub-categories experienced the most growth in terms of profit.

## Dataset

The data used in this analysis is sourced from Kaggle's `retail-orders` dataset by [ankitbansal06](https://www.kaggle.com/datasets/ankitbansal06/retail-orders).

### Data Fields:
- `product_id`: Unique identifier for the product.
- `sale_price`: The sale price of the product.
- `order_date`: The date the order was placed.
- `category`: Product category.
- `sub_category`: Specific product sub-category.
- `region`: The region in which the order was placed.

## Setup

### Requirements

1. **Python 3.x** (preferably 3.6 or higher)
2. **SQL Server** for data insertion.
3. Install the required Python libraries:
   ```bash
   pip install pandas sqlalchemy kaggle
