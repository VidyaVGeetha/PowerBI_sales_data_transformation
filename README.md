# 📊 Power BI Sales Data Cleaning & Transformation

## 📌 Project Overview

This project demonstrates practical data cleaning and transformation using **Power Query (M Language)** in Microsoft Power BI.

The dataset contained common real-world data quality issues such as:

- Missing (null) values  
- Inconsistent data types  
- Incorrect text entries in numeric fields  
- Duplicate product records  

The objective was to prepare a clean, reliable, and analysis-ready dataset suitable for reporting and business insights.

---

## 🎯 Business Scenario

A sales dataset required preprocessing before analysis. Without cleaning, the dataset could produce:

- Incorrect financial calculations  
- Reporting inconsistencies  
- Inflated sales figures due to duplicates  
- Errors caused by invalid data types  

This project ensures the dataset is accurate, structured, and ready for analytical use.

---

## 🛠 Data Transformation Steps

### 1. Header Promotion
- Promoted the first row to column headers for proper structure.

### 2. Data Type Standardisation
- Converted columns to appropriate data types:
  - Text
  - Whole Number
  - Decimal Number
  - Date
- Ensured consistent formatting across the dataset.

### 3. Null Value Handling
Replaced missing values with logical defaults:

- Units Sold → 0  
- Sale Price → 0  
- Sales → 0  
- Profit → 0  
- Manufacturing Price → 0  
- Date → 03 March 2023 (default placeholder)

### 4. Text Correction & Standardisation
- Replaced invalid value `"1"` with `"None"` in Discount Band.
- Corrected inconsistent entry `"six hundred"` to `"600"` in Units Sold.

### 5. Final Type Refinement
- Converted cleaned text fields into numeric formats.
- Ensured Date column consistency.

### 6. Duplicate Removal
- Removed duplicate records based on Product column to prevent inflated reporting.

---

## 🧠 Skills Demonstrated

- Microsoft Power BI
- Power Query (M Language)
- Data Cleaning Techniques
- Null Value Handling
- Data Type Management
- Text Standardisation
- Duplicate Detection & Removal
- Data Preparation Best Practices

---

## 📊 Business Impact

After transformation:

- Dataset became analysis-ready
- Financial calculations became reliable
- Reporting accuracy improved
- Duplicate-driven errors were eliminated
- Data integrity was strengthened

---

## 🛠 Tools Used

- Microsoft Power BI Desktop
- Power Query Editor
- Excel (Source Data)

---

## 📁 Repository Structure

```
powerbi-sales-data-transformation/
│
├── Sales-Data-Transformation.pbix
├── power-query-m-code.txt
├── README.md
└── screenshots/
```

---

## 🚀 Project Value

This project demonstrates the ability to transform messy business data into a clean and structured dataset using industry-standard tools and practices.

Data preparation is a critical step in analytics workflows, and this project highlights practical experience in ensuring data accuracy, reliability, and usability.

---

## 👤 Author

**Vidya Vishnuvihar Geetha**  
Aspiring Data Analyst  

🔹 Passionate about data cleaning, transformation, and generating business insights using Power BI  
🔹 Currently building practical analytics projects to strengthen real-world data skills  

---
