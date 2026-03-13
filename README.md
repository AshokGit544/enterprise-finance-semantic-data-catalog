# Enterprise Finance Semantic Data Catalog

SAP FICO-style finance semantic data catalog project using Python for business glossary creation, table and column metadata modeling, natural language query matching, dataset recommendation, and finance metric explanation.

## Project Overview

This project shows how enterprise finance data can be organized into a semantic data catalog so business users, analysts, and reporting teams can understand what data exists, what it means, and which dataset should be used for a specific finance question.

In many companies, finance data is stored across multiple tables such as vendors, cost centers, profit centers, GL accounts, and transaction tables. Even when the data exists, users often struggle to know which table to use, which columns are important, and how business terms map to technical fields.

This project solves that problem by creating a finance data catalog with:

- business glossary
- table metadata
- column metadata
- finance metric mart
- natural language search
- dataset recommendation

## Business Problem

Enterprise finance teams work with many datasets, but it is often difficult to answer questions like:

- Which table should I use for vendor spend?
- Which columns are needed for overdue payment analysis?
- Where can I find cost center reporting fields?
- Which dataset is best for Power BI reporting?
- How can business terms be mapped to technical columns?
- How can users search finance data using natural language?

This project helps answer those questions by building a semantic layer on top of SAP FICO-style finance data.

## What This Project Does

This project includes:

- finance master data generation
- finance transaction generation
- enriched finance model creation
- monthly metric mart creation
- vendor metric summary creation
- business glossary creation
- table catalog creation
- column catalog creation
- natural language search across metadata
- dataset recommendation for user questions
- finance metric explanation support

## Main Finance Entities

The project uses these core finance entities:

- Vendors
- Cost Centers
- Profit Centers
- GL Accounts
- Finance Transactions
- Enriched Finance Model
- Finance Metric Mart
- Vendor Metric Summary

## Key Features

- Synthetic SAP FICO-style finance data
- Business glossary for finance terms
- Table-level metadata catalog
- Column-level metadata catalog
- Metric mart for finance reporting
- Vendor-level metric summary
- Natural language table search
- Natural language column search
- Glossary search
- Dataset recommendation based on user query
- Finance metric explanation support

## Tech Stack

- Python
- pandas
- NumPy
- matplotlib
- scikit-learn
- Jupyter Notebook / Google Colab

## Project Flow

1. Create finance master data
2. Generate finance transactions
3. Build enriched finance model
4. Create reporting-ready metric mart
5. Build vendor metric summary
6. Create business glossary
7. Create table catalog
8. Create column catalog
9. Add natural language metadata search
10. Recommend datasets and fields for finance questions

## Data Catalog Layers

### Business Glossary
Contains business terms such as:

- Vendor Spend
- Cost Center Spend
- Overdue Payment
- GL Spend
- Profit Center Allocation
- Posting Month
- Vendor Risk Rating
- Capital Spend

### Table Catalog
Describes:

- table purpose
- business domain
- grain
- primary key

### Column Catalog
Describes:

- column definition
- column role
- data type
- source table

## Output Files

After running the notebook, the project generates files such as:

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

## Example Business Questions

This project can help answer questions like:

- show overdue payment percentage by vendor and posting month
- show total vendor spend by month
- show top vendors by total amount
- show capital spend by posting month
- find transaction count by cost center

## Why This Project Is Strong

This project is useful because it shows an important enterprise need that exists before advanced AI or analytics can work well.

A company may already have finance data, but users still need help understanding:

- what the data means
- which dataset to use
- how business terms connect to technical fields
- which columns are needed for reporting
- how to search datasets in business language

This project demonstrates that semantic layer.

## Skills Demonstrated

- Python
- pandas
- NumPy
- finance data modeling
- business glossary design
- metadata modeling
- semantic search
- dataset recommendation
- finance reporting support
- enterprise data catalog design

## How to Run

1. Open the notebook in Google Colab
2. Install dependencies
3. Run all cells from top to bottom
4. Review the generated output files
5. Upload the notebook and outputs to GitHub

## Suggested Repository Name

`enterprise-finance-semantic-data-catalog`

## Suggested Repository Description

SAP FICO-style finance semantic data catalog project using Python for business glossary creation, table and column metadata modeling, natural language query matching, dataset recommendation, and finance metric explanation.
