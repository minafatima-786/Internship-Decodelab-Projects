# Project 1 — Data Cleaning & Preparation

## Project Overview

This project focuses on cleaning and preparing an e-commerce order dataset for downstream data analytics.

The objective was to identify and resolve data-quality issues involving missing values, duplicate records, and inconsistent data types while preserving the integrity of the original dataset.

## Dataset

The dataset contains 1,200 order records and 14 variables, including:

- Order information
- Customer information
- Product details
- Quantity and pricing
- Shipping information
- Payment method
- Order status
- Tracking information
- Coupon and referral information

## Data Quality Issues Identified

The initial dataset was assessed for:

- Missing values
- Duplicate records
- Duplicate Order IDs
- Incorrect data types
- Invalid dates
- Non-numeric values in numeric fields
- Invalid business values
- Total price inconsistencies

## Data Cleaning Performed

The following steps were applied:

1. Inspected the structure and data types of the dataset.
2. Identified missing values.
3. Treated missing `CouponCode` values as `No Coupon`.
4. Checked and removed duplicate rows.
5. Checked for duplicate `OrderID` values.
6. Standardized the `Date` column as a datetime field.
7. Validated numeric columns including `Quantity`, `UnitPrice`, `ItemsInCart`, and `TotalPrice`.
8. Validated text and categorical fields.
9. Performed business-rule validation.
10. Conducted a final data-quality check.
11. Exported the cleaned dataset to Excel.

## Final Data Quality

After cleaning and validation:

- **Rows:** 1,200
- **Columns:** 14
- **Duplicate rows:** 0
- **Missing values:** 0
- **Invalid dates:** 0
- **Non-numeric values in numeric fields:** 0

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- Excel

## Project Files

- `Dataset for Data Analytics.xlsx` — Original raw dataset
- `Project_1_Data_Cleaning.ipynb` — Complete Python data-cleaning workflow
- `Project_1_Cleaned_Dataset.xlsx` — Final cleaned dataset

## Outcome

The project produced a validated and standardized dataset suitable for downstream data analytics and reporting.

The workflow demonstrates a practical approach to data cleaning and quality assurance using Python and Pandas.
