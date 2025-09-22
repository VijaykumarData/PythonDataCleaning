# PythonDataCleaning
Cleaning of data using pandas 
Project Title: **Bike Sales Data Cleaning and Transformation**
Project Description:

This project focuses on data cleaning and preprocessing of a bike sales dataset to make it analysis-ready. The dataset initially contained inconsistencies such as duplicate records, unstructured age data, numeric conversion issues, and improperly formatted column names.

Key Steps and Techniques Applied:

**Data Loading:** Imported the dataset from Excel using pandas.

**Data Type Conversion:** Corrected column data types, e.g., converting the Day column to integer for proper date handling.

**String Extraction & Transformation:**

Extracted age categories from the Age_Group column into separate columns: AgeGroupType (e.g., Adults, Children) and AgeRange (e.g., 35-64).

**Column Renaming:** Standardized column names for clarity and consistency (e.g., Sales_Order # → sales_order).

**Duplicate Handling:** Identified and removed duplicate records to ensure data integrity.

Data Cleaning: Removed unnecessary columns and ensured the dataset is in a clean, analysis-ready format.

Outcome:
A clean, well-structured dataset suitable for further data analysis, visualization, and business insights generation.

Technologies Used:
Python
Pandas
