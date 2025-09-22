# Data Cleaning Project

## Overview
This project demonstrates basic data cleaning techniques in Python using Pandas. The dataset used contains missing values, duplicate records, inconsistent data formats, and outliers. The goal is to prepare clean data for analysis.

## Dataset
- Filename: `sales_data_sample.csv`
- Description: Sample sales data including columns like Date, Product, Quantity, Price, etc.

## Steps Performed

1. **Handling Missing Values**
   - Identified missing values using `isnull()`.
   - Handled missing values by:
     - Removing rows with `dropna()`
     - Replacing missing values with mean, median, or custom values using `fillna()`

2. **Handling Duplicate Records**
   - Checked duplicates using `duplicated()`.
   - Removed duplicates using `drop_duplicates()`.

3. **Outlier Treatment**
   - Detected outliers using boxplots and IQR method.
   - Treated outliers by capping or removing extreme values.

4. **Standardizing Data**
   - Standardized numeric columns using z-score normalization.
   - Ensures all features are on the same scale for modeling.

5. **Inconsistent Data Formats**
   - Converted date columns to `datetime` type.
   - Ensured consistent formats for categorical variables (e.g., uppercase/lowercase).

6. **Common Challenges**
   - Missing values
   - Duplicate records
   - Inconsistent formats
   - Outliers
   - Large datasets

7. **Data Quality Check**
   - Checked for nulls, duplicates, inconsistent types, and outliers.
   - Verified data ranges and formats.

## Tools Used
- Python
- Pandas
