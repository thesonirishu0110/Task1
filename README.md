# Task1

# 🩺 Medical Appointment No Shows — Data Cleaning Project

## 📁 Dataset Overview

This project involves cleaning and structuring the **Medical Appointment No Shows** dataset. The dataset contains information about medical appointments and whether patients showed up, including features like age, gender, appointment dates, and other demographic or behavioral factors.

---

## 🛠️ Objective

To transform raw medical appointment data into a clean, structured format suitable for analysis and modeling.

---

## 🧼 Cleaning & Structuring Steps

The following data preprocessing steps were performed using **Python (Pandas)**:

### ✅ Column Standardization
- Renamed all column headers to be in `lowercase` and replaced `spaces` with `underscores` for consistency.
- Trimmed leading/trailing spaces from column names.

### ✅ Missing Values
- Identified missing values using `.isnull()`.
- Ensured all datetime conversions handled `NaT` values appropriately.

### ✅ Duplicate Removal
- Removed all duplicate rows using `.drop_duplicates()`.

### ✅ Text Standardization
- Standardized categorical values such as `gender` (e.g., converted to uppercase and removed whitespace).
- Cleaned and normalized fields like `neighbourhood` using title case formatting.

### ✅ Date Format Conversion
- Converted all columns containing the word `"date"` to `datetime` format using `pd.to_datetime()` with error handling.

### ✅ Data Type Correction
- Converted `age` to integer (`int`).
- Ensured all categorical and datetime fields are in appropriate data types.

---

## 📊 Output

The cleaned dataset was saved as:

