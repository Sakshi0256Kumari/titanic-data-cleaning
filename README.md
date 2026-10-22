# Titanic Data Cleaning and Preprocessing

## Overview
This project focuses on acquiring, cleaning, and preprocessing the Titanic dataset using Python and Pandas.

## Objectives
- Load a public dataset
- Inspect data types and missing values
- Handle missing values
- Standardize column names and text values
- Remove duplicate records
- Identify potential outliers using the IQR method
- Export the cleaned dataset as a CSV file

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Dataset
Source: https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv

## Workflow
1. Load the Titanic dataset.
2. Inspect its shape, columns, missing values, and duplicates.
3. Standardize column names and text values.
4. Fill missing age values using the median.
5. Fill missing embarked values using the mode.
6. Remove the deck column because it contains many missing values.
7. Remove duplicate rows.
8. Identify potential outliers in age and fare using the IQR method.
9. Export the cleaned dataset to CSV.

## Results
- Original dataset: 891 rows and 15 columns.
- Cleaned dataset: 775 rows and 14 columns.
- Duplicate rows after cleaning: 0.
- Two missing values remain in `embark_town`.
- Potential outliers were identified in `age` and `fare` and retained for analysis.

## Project Files
- `Week1_Data_Cleaning.ipynb` — notebook containing the code and analysis.
- `titanic_cleaned.csv` — exported cleaned dataset.

## Learning Outcomes
Practised data inspection, missing-value treatment, duplicate removal, outlier detection, and CSV export using Pandas.


