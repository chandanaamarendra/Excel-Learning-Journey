# Data Cleaning & Handling in Excel

## Project Overview

This project focuses on cleaning and preparing a raw HR dataset using Excel. Raw datasets often contain missing values, duplicates, and inconsistent formatting, which must be cleaned before analysis.

This project demonstrates real-world data cleaning techniques used by Data Analysts to make datasets accurate, consistent, and analysis-ready.

---

## Dataset Information

Columns included:

- Employee ID
- Full Name
- Department
- Email
- Salary
- Bonus
- Manager
- Joining Date

  RAW DATASET
<img width="922" height="715" alt="image" src="https://github.com/user-attachments/assets/79a7fb01-3cd6-4f25-ab28-32d452b9eb8c" />

Issues identified in raw dataset:

- Duplicate employee records
- Missing salary values
- Missing bonus values
- Missing emails
- Missing manager names
- Inconsistent text formatting

---

## Data Cleaning Steps and Functions Used

### 1. Remove Duplicates

Tool Used:
Excel → Data → Remove Duplicates

Use:
Ensures each employee record is unique and prevents incorrect analysis caused by duplicate entries.

---

### 2. TRIM Function

Formula:
=TRIM(B2)

Use:
Removes extra spaces before, after, or between text.

Example:
"  ram kumar  " → "ram kumar"

Why important:
Extra spaces can cause lookup failures and incorrect matching.

---

### 3. PROPER Function

Formula:
=PROPER(B2)

Use:
Converts text into proper case (first letter capitalized).

Example:
"ram kumar" → "Ram Kumar"  
"JOHN RAO" → "John Rao"

Why important:
Ensures consistent and professional text formatting.

---

### 4. IF Function

Formula:
=IF(E2="", Average_Salary, E2)

Use:
Replaces missing salary values with average salary.

Why important:
Missing values can cause incorrect calculations and analysis errors.

Also used for Bonus:

=IF(F2="", 0, F2)

Use:
Replaces missing bonus with 0.

---

### 5. IFERROR Function

Formula:
=IFERROR(H2+J2, 0)

Use:
Prevents Excel from showing errors in calculations.

Example:
If salary or bonus is missing, Excel would normally show an error. IFERROR replaces it with 0.

Why important:
Keeps reports clean and professional.

---

### 6. Data Standardization

Functions Used:

=PROPER(TRIM(Text))

Use:
Standardizes text formatting and removes inconsistencies.

Why important:
Ensures accurate filtering, sorting, and reporting.

---

## Calculated Column Created

### Total Pay

Formula:
Clean Salary + Clean Bonus

Use:
Calculates total compensation for each employee.

Why important:
Helps analyze employee cost and compensation structure.

---

## Summary Statistics Created

Using functions:

COUNTA → counts total employees  
AVERAGE → calculates average salary  
MAX → finds highest salary  
MIN → finds lowest salary  
SUM → calculates total salary and bonus  

<img width="267" height="244" alt="image" src="https://github.com/user-attachments/assets/e2571e9d-3327-442f-bc27-5381a026054f" />

Use:
Provides quick insights into workforce and compensation.

---

## Skills Demonstrated

- Data Cleaning
- Data Preparation
- Handling Missing Values
- Text Standardization
- Error Handling
- Excel Formula Usage
- Real-world HR Dataset Cleaning

---

## Files Included

- HR_Data_Cleaning_Project.xlsx
- Raw Data Sheet
- Cleaned Data Sheet
- Summary Sheet
- Screenshots

---

## Project Outcome

Successfully cleaned and prepared a raw HR dataset by removing duplicates, handling missing values, fixing text inconsistencies, and creating summary statistics.

The dataset is now analysis-ready.

<img width="1548" height="725" alt="image" src="https://github.com/user-attachments/assets/b1d0fc31-b8f6-453d-8bb3-9a79ecc8c5d3" />

---

## Status

Completed ✅
