Data Cleaning Pipeline – Python

Overview
This project implements a practical data-cleaning pipeline using Python to transform a raw, inconsistent dataset into a clean and analysis-ready format. The workflow reflects real-world data preprocessing practices used in analytics and machine-learning tasks.

Tools Used
pandas, numpy, matplotlib

Key Data Issues Addressed
• Inconsistent text formatting
• Invalid and non-numeric values
• Currency symbols and delimiters in numeric fields
• Mixed date formats
• Missing values

Processing Steps 1. Data auditing to assess structure, data types, and missing values 2. Text normalization (trimming, case standardization, whitespace handling) 3. Numeric cleaning and safe type conversion 4. Robust date parsing across multiple formats 5. Missing-value handling using median imputation for numeric fields and categorical placeholders for text

Output
The cleaned dataset is exported as:
cleaned_data.csv

Learning Outcomes
• Application of systematic data auditing
• Robust handling of real-world dirty data
• Reproducible preprocessing logic
• Improved data quality for downstream analysis
