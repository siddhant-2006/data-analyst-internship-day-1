summary

Dataset    : Mall Customer Segmentation
Source     : Kaggle
Tool used  : Python (Pandas)

ORIGINAL DATA
  Rows      : {df.shape[0]}
  Columns   : {df.shape[1]}
  Missing   : {df.isnull().sum().sum()}
  Duplicates: {df.duplicated().sum()}

ISSUES FIXED
  1. Renamed columns → lowercase, underscores
  2. Standardized Genre → Male / Female
  3. Filled {df.isnull().sum().sum()} missing values
  4. Removed {df.duplicated().sum()} duplicate rows
  5. Verified all data types correct
  6. Removed invalid age outliers

FINAL DATA
  Rows      : {df_clean.shape[0]}
  Columns   : {df_clean.shape[1]}
  Missing   : {df_clean.isnull().sum().sum()}
  Duplicates: {df_clean.duplicated().sum()}


print(summary)
****
I downloaded the Mall Customers dataset from Kaggle and performed data cleaning using Python Pandas in Google Colab. Steps included renaming columns, handling missing values, removing duplicates, and standardizing text fields.
