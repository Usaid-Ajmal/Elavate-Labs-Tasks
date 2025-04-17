# Elavate-Labs-Tasks
# Mall Customer Segmentation Data Cleaning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/your-repo/blob/main/Mall_Customer_Cleaning_Task.ipynb)

## Overview
Cleaned and preprocessed the Kaggle Mall Customer Segmentation dataset to handle missing values, duplicates, and formatting issues—making it analysis-ready.

## Files
- `Mall_Customers.csv` — raw data
- `cleaned_Mall_Customers.csv` — cleaned output
- `Mall_Customer_Cleaning_Task.ipynb` — step-by-step notebook

## Tools & Libraries
- Python 3.x
- pandas, numpy

## Cleaning Steps
1. Loaded data and inspected structure (`.head()`, `.info()`).
2. Handled nulls with `.dropna()` / `.fillna()`.
3. Removed duplicates via `.drop_duplicates()`.
4. Standardized text columns (e.g., stripped whitespace, lowercased).
5. Renamed headers to snake_case using `df.columns.str`.
6. Converted types (e.g., `Age` to int).
7. Saved cleaned CSV.

## Summary of Changes
- Removed X duplicate rows
- Filled Y missing values in `[column_names]`
- Standardized `gender` entries
- Renamed columns for consistency
- Ensured correct data types
