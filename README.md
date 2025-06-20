# Customer-Personality-Analysis
Issues Detected:
Missing values: Income has 24 null values.
Date format inconsistency: Dt_Customer is in string format.
Potential duplicates: We will check and remove if any.
Column formatting: Normalize categorical fields like Education, Marital_Status.

Let's now proceed to clean this dataset:
Handle nulls in Income (impute with median).
Convert Dt_Customer to datetime.
Remove duplicates if any.
Standardize text columns.
Save cleaned dataset.

 Summary of Changes Made:
24 null values in Income column were replaced with the median income.
Dt_Customer converted to datetime format.
No duplicate rows found.
Text fields standardized:
Education and Marital_Status were title-cased and stripped of extra spaces.
