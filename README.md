# Data Cleaning and Preprocessing

## 📌 Objective

The goal of this task was to clean and preprocess a raw dataset by
handling missing values, removing duplicates, fixing inconsistencies,
and ensuring proper formatting.

## 🔧 Tools Used

-   Python (Pandas, NumPy)
-   Jupyter Notebook

## 📝 Steps Performed

1.  **Handled Missing Values**
    -   Identified null values using `.isnull().sum()`.
    -   Plan: Fill numeric columns with median, categorical with mode
        (or drop rows if necessary).
2.  **Removed Duplicates**
    -   Dropped duplicate rows using `.drop_duplicates()`.
3.  **Standardized Text Values**
    -   Cleaned and standardized categorical values (e.g., gender →
        `male`, `female`).
    -   Removed extra spaces and ensured lowercase consistency.
4.  **Renamed Columns**
    -   Column headers cleaned: converted to lowercase, replaced spaces
        with underscores.
5.  **Fixed Data Types**
    -   Numeric columns converted to `int` or `float`.
    -   Example: `age` column set as integer.
6.  **Exported Final Dataset**
    -   Saved the cleaned dataset as `cleaned_student_performance.csv`.

## 📂 Deliverables

-   `cleaned_student_performance.csv` → Final cleaned dataset
-   `task_01_DA.ipynb` → Jupyter Notebook with full preprocessing steps
-   `README.md` → This summary file

## ✅ Summary of Changes

-   Removed duplicate records.
-   Standardized categorical values (gender, text fields).
-   Corrected column names and data types.
-   Converted date fields to consistent format.
-   Handled missing values (numeric → median, categorical → mode).
