Project Overview

This project focuses on cleaning and analyzing a retail transactions dataset containing 12,576 records. The dataset included missing values in key transactional fields such as price per unit, quantity purchased, and total sales.

The goal of this project was to assess data quality, handle missing values using business rules, and prepare a reliable dataset for analysis and reporting.

Data Cleaning & Preparation Process:

Conducted data quality assessment on 12,576 retail transaction records
Identified approximately 5% incomplete records with missing values in price, quantity, and total sales fields
Verified data consistency using the business rule: Price per Unit × Quantity = Total Sales
Reconstructed missing values where possible using derived calculations
Classified records into:
Complete records
Recoverable records (partially missing but calculable values)
Incomplete records (insufficient data for reconstruction)
Standardized dataset for further analysis and reporting

Key Business Rule Used:

Total Sales = Price per Unit × Quantity Purchased
This relationship was validated across the dataset and used to recover missing values where applicable.

 Tools Used:

Microsoft Excel
Data cleaning functions 
Data filtering and validation tools
Key Findings:
Approximately 5% of records contained incomplete transactional data
Most missing values were recoverable using business-rule validation
Dataset was successfully standardized for further analysis and dashboard development

 Project Structure:
 
Retail-Data-Project

> raw_data.xlsx
>  cleaned_data.xlsx
> data_audit.xlsx
> screenshots
raw_data.png
 cleaned_data.png

 README.md
 Outcome

This project demonstrates practical skills in:

Data cleaning and validation
Handling missing values
Applying business logic to real-world datasets
Preparing structured datasets for analysis and visualization
