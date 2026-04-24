# Retail Sales Analytics (Python)

## Overview
This project analyses a global retail sales dataset to understand sales performance, customer behaviour, and financial trends. It also includes a data audit to assess data quality and reliability before analysis.

---

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

## Dataset
Global Retail Sales Analytics Dataset (Kaggle)  
https://www.kaggle.com/datasets/faheem113141/global-retail-sales-analytics-dataset

---

## Project Structure
- Data cleaning and validation  
- Exploratory data analysis (EDA)  
- Financial performance analysis  
- Time series forecasting  
- Customer segmentation (RFM)  
- Data quality audit  

---

## Data Audit
A structured audit was performed to evaluate data quality and consistency.

Checks included:
- Missing values and completeness  
- Duplicate transactions  
- Invalid values (negative quantities, incorrect pricing)  
- Price validation (Unit Price × Quantity vs Total Price)  

Key findings:
- Identified inconsistencies in pricing and transaction records  
- Detected duplicate and missing data affecting analysis  
- Highlighted data quality issues impacting reporting accuracy  

---

## Key Insights
- Revenue is concentrated in a few key product categories (Pareto principle observed)  
- Sales show clear seasonal patterns and weekend performance differences  
- Customer spending is uneven, with a small group contributing most revenue  
- Discounts impact revenue but require balance to maintain profitability  
- Delivery and operational timing influence overall performance  

---

## Sample Visuals

### Financial Analysis
![Financial Analysis](images/retail_financial_analysis.png)

### Sales Forecast
![Sales Forecast](images/sales_forecast.png)

### Customer Segmentation
![Customer Segmentation](images/customer_segmentation.png)

---

## Outputs
- Cleaned dataset: `retail_sales_processed.csv`  
- Customer segments: `customer_segments.csv`  

---

## How to Run
1. Clone the repository  
2. Install dependencies  
3. Open the notebook in Jupyter  

---

## Conclusion
This project demonstrates end-to-end data analysis, from data cleaning and auditing to insight generation and forecasting, with a focus on real business application.
