# Diwali Sales Data Analysis
## Team: Error 404

* Ansh Dixit
* Srijan Pal
* Ansh Rawat
---
## Quick Overview 

This project involved analyzing Diwali sales data, performing data cleaning, and exploratory data analysis. The key findings indicate that married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are the primary buyers of Food, Clothing, and Electronics products.


---
## Key Working Of project
This project performs exploratory data analysis on a Diwali sales dataset. The steps involved are:
* **Data Loading and Initial Inspection**:   The 'Diwali Sales Data.csv' file was loaded into a pandas DataFrame, and initial checks for shape, head, and info were performed.
* **Data Cleaning**: Irrelevant columns ('Status', 'unnamed1') were dropped, null values were handled by dropping rows with missing 'Amount' values, and the 'Amount' column's data type was converted to integer.
* **Data Exploration**:
  * **Gender Analysis**: It was found that most buyers are females, and their purchasing power is greater than men.
  * **Age Group Analysis**: The majority of buyers are females in the 26-35 age group.
  * **State Analysis**: Uttar Pradesh, Maharashtra, and Karnataka accounted for most orders and total sales.
  * **Marital Status Analysis**: Married women have the highest purchasing power.
  * **Occupation Analysis**: Buyers from IT, Healthcare, and Aviation sectors are the most frequent.
  * **Product Category Analysis**: Food, Clothing, and Electronics were the most sold product categories.
  * **Product ID Analysis**: The top 10 most sold products were identified.
---
## Libraries Used  
- Python  
- NumPy
- Pandas
- Matplotlib
    - Inline
- Seaborn  
## Conclusion
This project demonstrates a comprehensive data analysis workflow, starting from data loading and preprocessing to performing exploratory data analysis (EDA). Through various visualizations, we've identified key customer demographics, purchasing behaviors, and popular product categories, providing valuable insights for business strategy.
