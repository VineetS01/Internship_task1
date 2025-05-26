# Marketing Customer Data Cleaning

This repository contains the Python code used to clean and preprocess a marketing customer dataset.

## Dataset Columns

The dataset includes the following columns:

- ID
- Year_Birth
- Education
- Marital_Status
- Income
- Kidhome
- Teenhome
- Dt_Customer
- Recency
- MntWines
- MntFruits
- MntMeatProducts
- MntFishProducts
- MntSweetProducts
- MntGoldProds
- NumDealsPurchases
- NumWebPurchases
- NumCatalogPurchases
- NumStorePurchases
- NumWebVisitsMonth
- AcceptedCmp1 to AcceptedCmp5
- Complain
- Z_CostContact
- Z_Revenue
- Response

## Data Cleaning Steps

1. **Loaded dataset** using `pandas` with tab-separated values.
2. **Identified and displayed missing values** per column.
3. **Removed or handled missing values** by either dropping rows with nulls or filling them.
4. **Checked for and removed duplicate rows** to ensure data integrity.
5. **Explored text columns** (like Education, Marital_Status) before standardizing values.
6. **Standardized text values** by trimming whitespace and converting to lowercase.
7. **Displayed date values** before converting to a consistent date format.
8. **Converted date columns** (`Dt_Customer`) to `datetime` format.
9. **Displayed column headers** before renaming.
10. **Renamed columns** to lowercase and replaced spaces with underscores for consistency.
11. **Checked and fixed data types** for all relevant columns, including integers, floats, dates, and binary flags.
12. **Saved the cleaned dataset** for further analysis.

## Tools & Libraries Used

- Python 3.x
- pandas
- Jupyter Notebook

## How to Use

1. Clone the repository.
2. Open the Jupyter Notebook.
3. Run the cells step-by-step to perform data cleaning.
4. Use the cleaned dataset for analysis or modeling.

---

Feel free to contribute or raise issues!

---

*This project is a part of data preprocessing and cleaning workflow for marketing customer data.*

