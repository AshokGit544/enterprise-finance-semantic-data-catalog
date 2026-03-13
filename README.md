# Enterprise Finance Semantic Data Catalog

I built this project to organize finance data in a simple and useful way.

In many finance systems, data is stored in different tables like vendors, cost centers, profit centers, GL accounts, and transaction tables.  
Sometimes the data is there, but it is hard to understand which table to use, what each column means, and how to answer a business question from that data.

This project helps solve that problem.

## What I did

In this project, I created:

- finance master data
- finance transactions
- an enriched finance model
- a monthly finance summary table
- a vendor summary table
- a business glossary
- a table catalog
- a column catalog
- search for finance data using simple questions
- dataset recommendations based on the question

## Why I did this project

I did this project because in real projects people often ask questions like:

- Which table should I use for vendor spend?
- Where can I find overdue payment data?
- Which columns are needed for cost center reporting?
- Which dataset is best for reporting?
- What does a business term mean in the data?

I wanted to build a project that makes finance data easier to understand.

## Main data used

This project uses these main finance areas:

- Vendors
- Cost Centers
- Profit Centers
- GL Accounts
- Finance Transactions
- Enriched Finance Model
- Finance Metric Mart
- Vendor Metric Summary

## What this project shows

This project shows how to:

- create finance data
- organize finance data
- explain finance terms
- explain table purpose
- explain column meaning
- search data using simple language
- suggest the right dataset for a question

## Features

- finance sample data
- business glossary
- table-level information
- column-level information
- monthly finance summary
- vendor summary
- search using user questions
- dataset recommendation

## Tools I used

- Python
- pandas
- NumPy
- matplotlib
- scikit-learn
- Google Colab / Jupyter Notebook

## Project steps

1. Create finance master data
2. Create finance transactions
3. Join the data into one model
4. Build a finance summary table
5. Build a vendor summary
6. Create glossary terms
7. Create table catalog
8. Create column catalog
9. Add search using simple questions
10. Recommend datasets and columns

## Output files

After running the notebook, it creates files like:

- `vendors.csv`
- `cost_centers.csv`
- `profit_centers.csv`
- `gl_accounts.csv`
- `finance_transactions.csv`
- `finance_enriched_model.csv`
- `finance_metric_mart.csv`
- `vendor_metric_summary.csv`
- `business_glossary.csv`
- `table_catalog.csv`
- `column_catalog.csv`
- `query_recommendations.csv`
- `dataset_usage_summary.csv`

## Example questions this project can answer

- show overdue payment percentage by vendor and month
- show total vendor spend by month
- show top vendors by total amount
- show capital spend by month
- find transaction count by cost center

## What I learned

From this project, I learned how to:

- structure finance data properly
- make data easier to understand
- connect business words with technical data
- help users find the right dataset
- support reporting in a simple way

## Why this project is useful

I made this project to show that good reporting starts with good understanding of the data.

Before building dashboards or advanced solutions, users need to know:

- what data is available
- what each table is for
- what each column means
- which dataset should be used

This project helps with that.

## How to run

1. Open the notebook in Google Colab
2. Install the required libraries
3. Run all cells
4. Check the output files
5. Upload the notebook and outputs to GitHub
