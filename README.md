# Sales Data Cleaning Project

## Overview
This project focuses on cleaning and preparing raw sales data for further analysis.  
The dataset initially contained missing values, duplicate records, inconsistent formatting, and mixed data types.  
Using Python and Pandas, I built a step-by-step cleaning pipeline to make the dataset structured, consistent, and ready to use.

## What I Did
1. **Loaded the raw dataset** (`sales_data.csv`) into Pandas.  
2. **Explored the data** – checked the shape, first few rows, column info, and missing values.  
3. **Handled missing values** – replaced blanks in categorical columns with the most frequent value, and filled numeric columns with the median.  
4. **Removed duplicate rows** to avoid redundant records.  
5. **Standardized text columns** by converting all text to lowercase and trimming extra spaces.  
6. **Converted date columns** (any column with “date” in its name) into proper datetime format.  
7. **Fixed numeric types** by converting float-like integers into integers.  
8. **Saved the cleaned dataset** as `sales_data_cleaned.csv`.  

## Cleaning Report
- Initial dataset shape: *(rows, columns before cleaning)*  
- Final dataset shape: *(rows, columns after cleaning)*  
- Missing values handled: *X*  
- Duplicate rows removed: *Y*  
- Text columns standardized: *list of columns*  
- Date columns converted: *list of columns*  

*(The exact numbers depend on the dataset and are updated each time the script runs.)*

## How to Run
1. Place your raw dataset in the project folder as `sales_data.csv`.  
2. Run the script with:
   ```bash
   python clean_sales_data.py

