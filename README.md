# Task 1: Data Cleaning and Preprocessing

## 📊 Dataset
**Customer Personality Analysis** dataset (sourced from Kaggle)

## 🛠 Tools Used
- Microsoft Excel (for initial file review)
- Python (Pandas, for cleaning and transformation)
- Jupyter Notebook environment

## 🧹 Cleaning and Preprocessing Performed

1. **Removed Duplicate Rows**  
   - Checked and dropped duplicate records to ensure uniqueness of data entries.

2. **Handled Missing Values**  
   - The `Income` column had 24 missing values.  
   - Replaced missing entries with the **median income** to maintain consistency without introducing bias.

3. **Standardized Text Data**  
   - Converted all entries in `Education` and `Marital_Status` columns to **lowercase** and **removed extra spaces** to avoid mismatches due to formatting inconsistencies.

4. **Date Format Conversion**  
   - Converted the `Dt_Customer` column to a **datetime object** using the `dd-mm-yyyy` format for consistent temporal analysis.

5. **Renamed Columns**  
   - Transformed all column headers to **lowercase** and replaced **spaces with underscores** to follow standard naming conventions (PEP8 compliance for code readability).

6. **Data Type Fixes**  
   - Ensured all numerical fields remained in their appropriate data types (integer/float).
   - Date column (`dt_customer`) successfully converted to datetime type.

## 🧾 Output Files

- `cleaned_dataset.xlsx`: Final cleaned dataset, ready for analysis or modeling.

## ✅ Outcome

This task enabled hands-on experience with:
- Identifying and correcting common data quality issues.
- Understanding the importance of preprocessing as a crucial step before analysis.
- Gaining confidence in preparing real-world datasets for further analytics or visualization.




**GitHub Repository:** [https://github.com/aditya-dabade123/data-cleaning-task1.git]  


