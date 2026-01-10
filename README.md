# E-commerce Sales Analytics + Customer Segmentation (RFM)

## What this project does
This beginner Python + Pandas project:
1) Cleans e-commerce transaction data
2) Creates a KPI report (revenue, orders, customers, average order value)
3) Segments customers using **RFM** (Recency, Frequency, Monetary)

## Tools used
- Python
- Pandas, NumPy
- Jupyter Notebook (VS Code)

## How to run


### 1) Create and activate a virtual environment

```md
```bash
python -m venv .venv
source .venv/bin/activate


2) Install packages

```bash
python -m pip install pandas numpy openpyxl matplotlib jupyter


3) Put the dataset here

data/raw/online_retail.xlsx


4) Run notebooks in order

notebooks/01_cleaning.ipynb → creates data/processed/online_retail_clean.csv

notebooks/02_kpis_rfm.ipynb → creates outputs/kpis.csv and outputs/rfm_segments.csv


Outputs

data/processed/online_retail_clean.csv (cleaned transactions + revenue column)

outputs/kpis.csv (KPI summary)

outputs/rfm_segments.csv (customer segments)


What I learned

Loading Excel datasets and handling missing values

Cleaning real-world data (cancellations, invalid rows)

Pandas operations: groupby, aggregation, feature engineering

Customer segmentation using RFM scoring

