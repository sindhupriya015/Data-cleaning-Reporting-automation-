# Data Cleaning & Reporting Automation

## Project Overview
This project automates the process of cleaning sales data, handling missing values, removing duplicate records, and generating reports and visualizations using Python.

## Objective
To automate data preprocessing and reporting workflows to improve data quality, reduce manual effort, and generate useful business insights.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Excel

## Dataset Description
The project uses a sample sales dataset containing the following columns:
- Order ID
- Customer
- City
- Category
- Quantity
- Sales
- Order Date

The dataset contains intentional missing values, duplicate records, and inconsistent text formatting to demonstrate data cleaning techniques.

**Note:** The dataset contains simulated data for educational purposes.

## Project Workflow

### 1. Data Loading
Loaded the sales dataset using Pandas.

### 2. Data Inspection
Identified missing values, duplicate records, column data types, and basic statistics.

### 3. Data Cleaning
- Removed duplicate records.
- Handled missing values.
- Standardized text formatting.
- Converted sales and quantity columns to numeric types.
- Converted order dates to datetime format.
- Created a month column for reporting.

### 4. Automated Reporting
Generated summary reports containing:
- Total sales
- Total quantity sold
- Number of order rows
- Average sales per row
- Category-wise sales
- City-wise sales
- Monthly sales trends

### 5. Data Visualization
Created charts to display:
- Sales by category
- Sales by city
- Monthly sales trends

### 6. Report Export
Exported the cleaned data, summary tables, charts, and automated text report.

## Project Deliverables
- `raw_sales_data.csv` — Original dataset
- `cleaned_sales_data.csv` — Cleaned dataset
- `Automated_Sales_Report.xlsx` — Excel workbook containing data and summary reports
- `Automated_Report.txt` — Automatically generated text report
- `sales_by_category.png` — Category-wise sales chart
- `sales_by_city.png` — City-wise sales chart
- `monthly_sales_trend.png` — Monthly sales chart
- `Data_Cleaning_Reporting_Submission.zip` — Packaged project outputs
- `Data_Cleaning_Reporting_Automation.ipynb` — Python notebook

## How to Run the Project
1. Open the notebook in Google Colab.
2. Run each code cell in order.
3. Review the cleaned dataset and summary reports.
4. View the generated charts.
5. Download the exported files for submission.

## Expected Outcomes
- Improved data quality
- Removal of duplicate records
- Consistent data formatting
- Automated report generation
- Visual summaries for easier analysis
- Reduced manual reporting effort

## Conclusion
This project demonstrates how Python can automate data cleaning, preprocessing, reporting, and visualization. The workflow helps improve data consistency and makes it easier to generate reports for data-driven decision-making.

## Author
Created as a Data Cleaning and Reporting Automation project using Python and Google Colab.
