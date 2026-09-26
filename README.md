# Week 1 - Data Acquisition, Cleaning and Preprocessing

## Project Overview

This project was completed as part of the YuvaIntern Virtual Data Science with Python Trainee internship.

The objective of this task was to acquire a real-world dataset, inspect its structure, identify data quality issues, clean and preprocess the data, and prepare the final dataset for further analysis.

## Dataset

The project uses the IBM Telco Customer Churn dataset.

The dataset contains customer information related to demographics, services, contract details, monthly charges, total charges, and churn status.

## Tools Used

- Python
- Pandas
- Google Colab
- GitHub

## Data Cleaning Steps

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected the dataset structure, columns, data types and statistics.
3. Checked for missing values.
4. Checked for blank values in the dataset.
5. Converted `TotalCharges` from text to numeric format.
6. Identified 11 blank values in `TotalCharges`.
7. Replaced the missing `TotalCharges` values using the median value.
8. Checked for duplicate rows.
9. Checked for duplicate customer IDs.
10. Performed IQR-based outlier detection on numerical columns.
11. Validated numerical ranges and checked for invalid negative values.
12. Performed categorical value consistency checks.
13. Conducted a final data quality validation.

## Results

- Dataset size: 7,043 rows and 21 columns
- Blank `TotalCharges` values found: 11
- Missing values after cleaning: 0
- Duplicate rows: 0
- Duplicate customer IDs: 0
- `TotalCharges` data type after cleaning: `float64`
- `MonthlyCharges` data type: `float64`
- Potential IQR outliers identified: 0 in the checked numerical columns

## Output

The cleaned dataset was exported as:

`Telco_Customer_Churn_Cleaned.csv`

The complete Python notebook is also included:

`Week1_Data_Cleaning.ipynb`

## Conclusion

The dataset was successfully cleaned and validated. The resulting dataset is suitable for further exploratory data analysis and machine learning tasks.
