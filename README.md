📊 Data Cleaning & Quality Improvement Case Study
🏢 Business Problem

Organizations often rely on operational datasets for reporting, dashboarding, and decision-making. However, raw data frequently contains:

Duplicate records

Missing values

Inconsistent text formatting

Non-standardized column naming

Data quality issues affecting analysis accuracy

The objective of this project was to:

Clean and standardize the raw dataset to make it analysis-ready, reliable, and suitable for reporting & visualization.

📁 Project Structure
├── raw_data.xlsx          # Original unclean dataset
├── cleaned_data.xlsx      # Cleaned & processed dataset
└── README.md              # Project documentation

🧹 Data Cleaning Steps Performed
1️⃣ Removed Duplicate Records

Identified and removed exact duplicate rows

Ensured no double counting in reporting

2️⃣ Trimmed & Standardized Text Fields

Removed leading and trailing spaces

Standardized inconsistent text formatting

Prevented mismatches like "Delhi " vs "Delhi"

3️⃣ Standardized Column Names

Converted all column names to lowercase

Replaced spaces with underscores

Example:
Customer Name → customer_name

This improves:

SQL compatibility

Python handling

Power BI usability

4️⃣ Missing Value Treatment
🔢 Numeric Columns

Imputed missing values using median

Chosen because it is robust against outliers

🔤 Categorical Columns

Replaced missing values with "Unknown"

Ensures no null-related errors in dashboards

5️⃣ Data Consistency Improvements

Converted inconsistent data types

Ensured structured formatting
