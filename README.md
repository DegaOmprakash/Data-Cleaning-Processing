# Sales Data Cleaning Project

## 📌 Overview
This project demonstrates a **data cleaning pipeline** using Python and Pandas.  
The goal is to transform raw sales data into a clean, consistent format suitable for analysis.

## 🛠️ Steps Performed
1. **Load Dataset**  
   - Read `sales_data.csv` into a Pandas DataFrame.  

2. **Explore Dataset**  
   - Checked shape, first few rows, dataset info, and missing values.  

3. **Handle Missing Values**  
   - Filled **categorical columns** with the most frequent value (mode).  
   - Filled **numeric columns** with the median.  

4. **Remove Duplicates**  
   - Dropped duplicate rows to ensure unique records.  

5. **Standardize Text Columns**  
   - Converted all text to lowercase and removed extra spaces.  

6. **Fix Date Columns**  
   - Converted any column containing `date` into proper datetime format.  

7. **Fix Numeric Data Types**  
   - Converted float-like integers into `int` type for consistency.  

8. **Save Clean Dataset**  
   - Exported cleaned data as `sales_data_cleaned.csv`.  

## 📊 Cleaning Report (Auto-Generated)
- **Initial Shape**: *(rows, columns)*  
- **Final Shape**: *(rows, columns)*  
- **Missing Values Fixed**: *X*  
- **Duplicates Removed**: *Y*  
- **Standardized Text Columns**: *[col1, col2, ...]*  
- **Date Columns Converted**: *[col1, col2, ...]*  

*(Values are filled automatically when the script runs.)*

## 🚀 How to Run
1. Place your raw dataset in the `/content/` folder as `sales_data.csv`.  
2. Run the script:
   ```bash
   python clean_sales_data.py
