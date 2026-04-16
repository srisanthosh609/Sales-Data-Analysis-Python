# Sales-Data-Analysis-Python
A comprehensive data analysis project using Python to clean, process, and analyze global sales records. Features data preprocessing, missing value handling, and sales metric calculations using Pandas and NumPy.

# Global Sales Data Analysis & Cleaning

## Project Overview
This project focuses on the end-to-end data cleaning and exploratory analysis of a global sales dataset. The goal was to transform raw sales data into a structured format suitable for business intelligence and reporting.

## Key Features
* **Data Cleaning:** Handled missing values (NaN) across multiple columns like `ADDRESSLINE2`, `STATE`, and `TERRITORY`.
* **Deduplication:** Identified and removed duplicate records to ensure data integrity.
* **Feature Engineering:** * Converted `ORDERDATE` into proper datetime objects for time-series analysis.
    * Created a new `TOTALSALES` metric by calculating the product of quantity ordered and price each.
* **Data Profiling:** Performed statistical summaries and structure checks using Pandas `info()` and `head()` methods.

## Tools & Libraries Used
* **Python**: Core programming language.
* **Pandas**: Used for data manipulation, cleaning, and transformation.
* **NumPy**: Used for numerical operations.

## Dataset
The analysis is based on the `sales_data_sample.csv` dataset, which includes 2,823 records of sales orders, featuring details such as order numbers, quantities, prices, status, and customer demographics.

## How to Run
1. Clone this repository.
2. Ensure you have Jupyter Notebook or JupyterLab installed.
3. Install dependencies: `pip install pandas numpy`
4. Open `project1.ipynb` and run the cells.
