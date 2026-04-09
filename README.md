Shein E-commerce Data Cleaning Project 👗💻

Project Overview:
This project demonstrates a complete Data Cleaning and Preprocessing workflow using Python. The dataset contains appliance products from Shein, which initially had several issues like missing values, incorrect data types, and outliers.

Key Challenges Addressed:
Dirty Formatting: Prices and discounts were stored as strings with symbols ($, %).
Missing Data: Many columns had empty values (NaN) that could lead to biased analysis.
Outliers: Some products had extreme prices that skewed the statistical distribution.

Steps Performed:
Data Imputation: Filled missing text data with "Unknown" and numerical data with the Median.
Type Conversion: Used pd.to_numeric to convert currency strings into floats for calculation.
Outlier Removal: Applied the IQR (Interquartile Range) method to filter out extreme price values.
Data Integrity: Removed duplicate records and sanitized text by stripping extra whitespaces.

Tools Used:
Python
Pandas
NumPy
