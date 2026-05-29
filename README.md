# data-analyst-internship-day-1
summary
DATA CLEANING SUMMARY
Dataset: Mall Customer Segmentation

BEFORE CLEANING:
- Rows: 200, Columns: 5
- Missing values: 2 (in Age column)
- Duplicates: 3 rows
- Column names: inconsistent (spaces, special chars)
- Gender values: inconsistent (Male/male/M)

ACTIONS TAKEN:
1. Filled 2 missing Age values with mean (38.85)
2. Removed 3 duplicate rows
3. Renamed all columns to lowercase with underscores
4. Standardized Gender to 'Male'/'Female' format
5. Converted Age to integer type
6. Removed 0 outliers (data was clean)

AFTER CLEANING:
- Rows: 197, Columns: 5
- Missing values: 0
- Duplicates: 0
- Dataset is ready for analysis
