# Task 1: Data Cleaning and Preprocessing

Level 1 (Basic)

## Project Objective
The goal of this task was to take a raw dataset and prepare it for analysis by handling missing values, removing duplicates, and standardizing data formats. This ensures the data is accurate and reliable for future modeling.

## Tools Used

Language: Python

Library: pandas

## Key Steps Taken

### Data Loading: 
Imported the raw CSV dataset using pd.read_csv().

### Handling Missing Values: 
Identified null values and handled them through removal,median imputation, and calculations.

### Removing Duplicates:
Detected and dropped duplicate rows to ensure each entry was unique.

### Standardization:
Corrected inconsistent data formats, such as converting Quantity, Price_per_unit and Total_spent to numeric format and converting Transaction_date to date time formart

## Files in this Folder
### level1_task1_data_cleaning.ipynb:
The Jupyter Notebook containing the Python code.

### dirty_cafe_sales.csv:
The original dataset before cleaning.

### cleaned_cafe_sales.csv:
The final, processed dataset.











