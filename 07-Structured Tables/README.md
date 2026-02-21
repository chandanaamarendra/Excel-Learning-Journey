# Structured Tables in Excel

## Introduction to Structured Tables

Structured Tables are an advanced Excel feature that converts a normal data range into a dynamic and intelligent table object. Unlike regular cell ranges, Structured Tables automatically expand when new data is added, apply formulas consistently across columns, and allow the use of structured references instead of traditional cell references.

This feature is essential for building scalable Excel models, dynamic dashboards, and automated reporting systems. Structured Tables also integrate seamlessly with Pivot Tables, Power Query, and Power Pivot, making them a foundational skill for Data Analysts.

Using Structured Tables improves data readability, reduces manual effort, and ensures accuracy in large datasets.

---

## Overview

This project demonstrates the practical implementation of Structured Tables to organize, calculate, and analyze sales transaction data efficiently. It highlights how structured references, automatic expansion, and dynamic Pivot Tables improve workflow efficiency and data reliability.

---

## Dataset Description

The dataset contains sales transaction records with the following fields:

- Date
- Product
- Region
- Sales
- Quantity

RAW DATA

<img width="443" height="249" alt="image" src="https://github.com/user-attachments/assets/81921046-c64b-411a-86b9-0bcc21704ebc" />

---

## Key Concepts Practiced

### 1. Creating Structured Tables
- Converted raw data into a structured table using Ctrl + T
- Enabled automatic filtering and formatting
- Renamed the table to `Sales_Data` for professional referencing

### 2. Structured References
- Used structured reference formulas instead of cell references
- Example:
  
  =[@Sales]*[@Quantity]

- Improved formula readability, scalability, and maintainability

### 3. Automatic Formula Expansion
- Applied formula once and Excel automatically filled entire column
- Eliminated need for manual dragging
- Ensured consistency across all rows

### 4. Automatic Table Expansion
- Added new rows and verified automatic table expansion
- Confirmed formulas and table structure updated automatically

### 5. Total Row Feature
- Enabled Total Row to calculate summary metrics such as:
- Sum of Revenue
- Average values
- Count of records

### 6. Dynamic Pivot Table Integration
- Created Pivot Table using Structured Table as source
- Ensured Pivot Table updates dynamically when new data is added
- Demonstrated scalable data analysis workflow

PIVOT Table

<img width="582" height="282" alt="image" src="https://github.com/user-attachments/assets/cc8b5989-7db1-4724-b3b9-7173865b4d69" />

---

## Skills Demonstrated

- Data structuring and organization
- Structured references and professional formula usage
- Automated calculations and formula management
- Dynamic data expansion handling
- Pivot Table integration with structured data
- Excel best practices for scalable and professional data analysis

## Final Output

<img width="593" height="368" alt="image" src="https://github.com/user-attachments/assets/0c69d75f-a78c-4369-96e0-cbf50d6bf068" />

---

## File Included

- `Day7_Structured_Tables.xlsx` — Contains structured table, calculated columns, and Pivot Table

---

## Why This Matters for Data Analysis

Structured Tables are critical for:

- Building dynamic dashboards
- Preparing data for Power Query transformations
- Creating scalable and automated Excel reports
- Improving data accuracy and reducing manual errors
- Supporting real-world business reporting workflows

This skill is widely used by Data Analysts in business intelligence and reporting environments.

---

## Author

Chandana A
Aspiring Data Analyst  
Focused on building strong foundations in Excel, SQL, Python, and Data Visualization
