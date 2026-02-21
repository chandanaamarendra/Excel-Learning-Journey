# Excel Named Ranges & Dynamic Named Range Analysis Project

## Project Overview

This project demonstrates the implementation of Excel Named Ranges and Dynamic Named Ranges using a structured 100-row sales dataset. The objective was to build an automated and scalable data analysis model where formulas dynamically update when new data is added.

Instead of using fixed cell references, named ranges and structured table references were used to improve formula readability, maintainability, and automation. This approach reflects real-world practices followed by Data Analysts to manage growing datasets efficiently.

The project includes a clean dataset, dynamic formulas, and a professional summary section that calculates key business metrics automatically.

---

## Dataset Description

The dataset contains 100 rows of simulated sales data with the following fields:

- Date – Transaction date
- Product – Product name (Product 1 to Product 5)
- Region – Sales region (North, South, East, West)
- Sales – Sales amount in currency units

The dataset was designed to simulate real business transaction data for analysis and reporting.

---

## Objectives

The main objectives of this project were:

- To understand and implement Named Ranges in Excel
- To create Dynamic Named Ranges that automatically expand
- To eliminate hardcoded cell references in formulas
- To implement structured references using Excel Tables
- To perform automated sales analysis using dynamic formulas
- To build a scalable and professional summary report

---

## Key Concepts Implemented

### 1. Named Ranges

Named ranges were created for key dataset columns:

- Sales → Sales column
- Region → Region column
- Product → Product column
- Date → Date column

Example formula using Named Range: 

=SUM(Sales)

This improves formula readability compared to traditional cell references.

---

### 2. Dynamic Named Range

A Dynamic Named Range was created using INDEX and COUNTA functions:

=$D$2:INDEX($D:$D,COUNTA($D:$D))


This ensures the range automatically expands when new sales data is added.

This eliminates the need for manual updates and enables automation.

---

### 3. Excel Table Structured References

The dataset was converted into an Excel Table to enable fully dynamic data handling.

Example structured reference formula:

=SUM(Sales_Table[Sales])

Excel Tables automatically include new rows in calculations.

This is the most modern and recommended approach in industry.

---

### 4. Summary Metrics Created
A professional summary section was built to calculate key business metrics using Named Ranges, Dynamic Named Ranges, and Structured Table References. These metrics automatically update when new data is added, ensuring scalability and automation.

The following metrics were created:

- Total Sales using Named Range
- Average Sales using Named Range
- Maximum Sale value using Named Range
- Minimum Sale value using Named Range
- Total Number of Sales Transactions using Named Range
- Total Sales in South Region using SUMIFS with Named Range
- Total Sales in North Region using SUMIFS with Named Range
- Total Sales using Dynamic Named Range to demonstrate automatic range expansion
- Total Sales of Product 1 using SUMIFS with Named Range
- Total Sales of Product 3 in South Region using multi-condition SUMIFS
- Average Sales of South Region using AVERAGEIFS with Named Range
- Total Sales using Excel Table Structured Reference
- Average Sales using Excel Table Structured Reference

These summary metrics demonstrate how dynamic references and structured formulas enable automated, scalable, and professional data analysis in Excel.

<img width="852" height="399" alt="image" src="https://github.com/user-attachments/assets/34b0079e-c3c5-4f8d-abc2-0d24a0de9012" />

---

## Dynamic Behavior Demonstrated

This project demonstrates automatic formula updates when new data is added.

The following methods were compared:

| Method | Dynamic Behavior |
|------|------------------|
| Normal Cell Range | No |
| Named Range | No |
| Dynamic Named Range | Yes |
| Excel Table | Yes |

Dynamic Named Range and Excel Tables ensure scalable and automated analysis.

---

## Skills Demonstrated

This project demonstrates the following Excel and Data Analysis skills:

- Named Ranges
- Dynamic Named Ranges
- INDEX Function
- COUNTA Function
- Structured References
- Excel Tables
- SUM Function
- AVERAGE Function
- MAX and MIN Functions
- COUNT Function
- SUMIFS Function
- AVERAGEIFS Function
- Data Structuring
- Automated Reporting

---

## Business Value

This approach is used by Data Analysts to:

- Automate reporting workflows
- Handle growing datasets efficiently
- Build scalable dashboards
- Improve formula readability
- Reduce manual maintenance
- Enable reliable data analysis

---

## File Included

- `Day8_Named_Ranges.xlsx`  
  Contains dataset, named ranges, dynamic ranges, and summary analysis.

---

## Author

A.Chandana  
Aspiring Data Analyst  

Skills:
- Excel
- SQL
- Power BI
- Python 
- Data Analysis
- Data Visualization

---

## Project Status

Completed  
This project is part of my Data Analyst portfolio showcasing Excel automation and dynamic data handling skills.

