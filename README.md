# students_performance-eda
students_EDA_task10

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a dataset containing students' exam scores and demographic information. The goal is to understand the data, detect outliers, and prepare it for further analysis or modeling.

## Dataset
- **Dataset used:** `Students Performance Dataset`
- **Number of rows:** [replace with df.shape[0]]
- **Number of columns:** [replace with df.shape[1]]
- **Columns:** [list df.columns]

## EDA Steps Performed
1. **Data Inspection**
   - Checked dataset shape, columns, data types, and first few rows
   - Verified there are no missing values

2. **Descriptive Statistics**
   - Calculated mean, min, max, standard deviation, and quartiles for numeric columns

3. **Outlier Analysis**
   - Visualized distributions using histograms and boxplots
   - Detected outliers using the IQR method
   - Created outlier flag columns and capped extreme values

4. **Correlation Analysis**
   - Calculated correlations between numeric features
   - Identified strong relationships between exam scores

5. **Export Cleaned Dataset**
   - Cleaned dataset saved as `cleaned_dataset.csv` for further use

## Files in Repository
- `StudentsPerformance.csv` → Original dataset  
- `cleaned_dataset.csv` → Cleaned dataset after EDA  
- `eda_findings.txt` → Summary of EDA insights  
- `README.md` → This file
