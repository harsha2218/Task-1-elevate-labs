# Sales Data Cleaning Project

This repository demonstrates the process of **cleaning and preprocessing a sales dataset** using Python.

---

## Overview

The dataset was cleaned and prepared for analysis with the following steps:

1. **Initial Inspection**  
   - Checked for missing values and non-null counts.  
   - Examined data types of all columns.

2. **Date Column Processing**  
   - Converted `Sale_Date` from `object` to `datetime` type.  
   - Formatted dates in `dd-mm-yyyy` format.

3. **Categorical Data Handling**  
   - Converted all `object` type columns to `category` type.  
   - Check if Standardizing text values required (e.g., capitalization, spelling).

4. **Numeric Data Cleaning**  
   - Checked numeric columns for inconsistencies or anomalies.  
 

5. **Save Cleaned Data**  
   - Saved the cleaned dataset as `sales_data_cleaned.csv`.

---

##  Tools & Libraries

- Python   
- Pandas 
