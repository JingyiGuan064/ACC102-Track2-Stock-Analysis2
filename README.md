# ACC102 Track 2: US Stock Monthly Return Analysis (2022)
XJTLU | IBSS | ACC102 Python Data Product

## Project Overview
This project analyses monthly stock returns for **NVDA, MSFT, AAPL** in 2022 using WRDS CRSP data.
It calculates return, risk, and performance metrics for educational and business analysis purposes.

## Analytical Purpose
- Compare return and risk patterns of three large tech stocks
- Provide clear descriptive statistics for investors/students
- Demonstrate Python data workflow with SQL and WRDS

## Target User
Finance students, investment analysts, and researchers.

## Dataset
- Source: WRDS CRSP Monthly Stock File
- Access Date: 2024-04-24
- Period: 2022-01-01 to 2022-12-31
- Tickers: NVDA, MSFT, AAPL

## Python Workflow
1. Connect to WRDS database
2. SQL query for stock data
3. Data cleaning & renaming
4. Time-series sorting & date feature extraction
5. Return ranking & group summary statistics
6. Reusable function for single stock query

## Key Insights
- NVDA/MSFT/AAPL show distinct monthly return patterns in 2022
- Risk (std) differs significantly across tickers
- The reusable function supports quick analysis for any stock

## How to Run
1. Install packages: wrds, pandas
2. Run all cells in analysis.ipynb
3. Use the function get_monthly_stock_data() for custom queries

## Author
Jingyi Guan | 2473524 | Track 2 GitHub Project
