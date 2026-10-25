# Homework 4 — PostgreSQL Data Manipulation and Analytics

## Overview

This project demonstrates PostgreSQL data manipulation and analytical queries using a small synthetic e-commerce dataset inspired by the Olist Brazilian E-Commerce Dataset.

The notebook covers raw and typed data layers, data integrity constraints, DML operations, customer segmentation, JOINs, aggregate functions, set operations, and window functions.

## Data Source and Limitations

**The CSV files included in this repository contain synthetic data created for this homework. They are not the original Olist dataset and must not be interpreted as real-world Olist business data.**

The data is designed to provide sample customers, orders, order items, products, sellers, and reviews for demonstrating the required SQL operations.

All reported metrics and query results refer exclusively to this synthetic dataset.

## Repository Structure

- `README.md` — project overview, data information, and execution instructions.
- `homework_4.ipynb` — Google Colab notebook containing explanations, SQL queries, and execution results.
- `data/` — six CSV files used to populate the raw PostgreSQL tables.

The CSV files are:

- `olist_customers_dataset.csv`
- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_products_dataset.csv`
- `olist_sellers_dataset.csv`
- `olist_order_reviews_dataset.csv`

## Requirements

- Google Colab
- Python
- PostgreSQL
- Python packages: `pandas`, `SQLAlchemy`, and `psycopg2-binary`

The notebook includes the setup and data-loading steps required to create the PostgreSQL tables.

## How to Run

1. Open `homework_4.ipynb` in Google Colab.
2. Make the CSV files in the `data/` directory available to the notebook.
3. Run the notebook cells in order, starting with the PostgreSQL setup.
4. Verify the data-loading and validation results.
5. Continue through the DML, customer segmentation, JOIN, aggregation, set operation, and window function sections.

The typed tables are populated from the raw tables. When rerunning the notebook, the typed data-loading step clears and reloads the derived tables from the raw data.

## Notes

This is an educational SQL project. Segmentation thresholds and business rules are simplified for demonstration purposes. The results should not be used to draw conclusions about the actual Olist marketplace.
