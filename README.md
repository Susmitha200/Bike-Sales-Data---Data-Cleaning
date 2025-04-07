# Bike Sales Data Cleaning - README

## Overview
This dataset was cleaned and preprocessed using **Microsoft Excel** to prepare it for analysis. The raw data contained formatting issues, inconsistent text values, incorrect data types, and some missing or unnecessary entries. Below are the steps taken to clean the data.

## Cleaning Steps

1. **Auto-Fit Column Widths**
   - Adjusted all columns to fit the content using Excel's "AutoFit Column Width" for better visibility.

2. **Removed Duplicates**
   - Selected the entire dataset (Ctrl + A) and used `Data > Remove Duplicates`, checking all columns. No duplicates were found.

3. **Applied Filters**
   - Added filters to the first row (`Data > Filter`) to enable easy sorting and inspection of column-wise values.

4. **Corrected Spelling Errors**
   - Fixed a typo in the `Month` column by replacing `"Decmber"` with `"December"` using `Find & Replace (Ctrl + H)`.

5. **Standardized Gender Values**
   - Replaced short codes: `F` → `Female` and `M` → `Male` in the `Gender` column for clarity and consistency.

6. **Trimmed Extra Spaces**
   - Used the `TRIM()` function to clean up leading, trailing, or extra spaces in the `Country` column.

7. **Handled Missing/Blank Values**
   - Deleted unnecessary blank **rows and columns** to streamline the dataset.

8. **Formatted Numerical Data**
   - Changed data types from **Currency to Number** format.
   - Removed decimal places for cleaner presentation and ease of querying.

9. **Fixed Data Type Errors**
   - Corrected the `sales_order` column by changing its data type from **Text to Number**, resolving display and formula issues.

# Final Result
The dataset is now:
- Free of duplicates and formatting errors
- Consistent in text values and numeric formatting
- Clear of unnecessary or blank entries
- Ready for analysis or use in data-driven applications
