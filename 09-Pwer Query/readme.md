# Advanced Excel – Power Query Data Cleaning and Transformation Project

## Overview

This project demonstrates the use of **Power Query in Excel** to perform data cleaning, transformation, and preparation on a structured sales dataset. The goal was to simulate real-world Data Analyst tasks such as importing raw data, transforming it into a clean format, and preparing it for reporting and analysis.

Power Query enables automation of repetitive data preparation steps, ensuring efficiency, accuracy, and scalability.

---

## Dataset Description

The dataset consists of **100 sales records** with the following columns:

* Order_ID – Unique identifier for each order
* Date – Transaction date
* Customer – Customer name
* Region – Sales region (North, South, East, West)
* Product – Product name
* Category – Product category (Electronics, Furniture)
* Sales – Sales amount
* Quantity – Number of units sold

---

## Objectives

The main objectives of this project were to:

* Import data into Power Query
* Clean and transform the dataset
* Create calculated columns
* Perform aggregation using Group By
* Automate data preparation using Applied Steps
* Load transformed data back into Excel for analysis

---

## Power Query Operations Performed

### 1. Data Import

* Imported dataset using **Get Data from Workbook**
* Loaded data into the **Power Query Editor**

### 2. Data Cleaning

* Removed unnecessary columns
* Filtered rows based on specific conditions
* Changed incorrect data types to appropriate formats

### 3. Data Transformation

* Created a **Custom Column** to calculate total revenue:

  Revenue = Sales × Quantity

* Added a **Conditional Column** to classify sales level:

  * High → Sales greater than 30,000
  * Low → Sales less than or equal to 30,000

* Added an **Index Column** to create unique row identifiers

### 4. Data Aggregation

* Used **Group By** to calculate total sales by region
* Generated summary-level insights from raw transactional data

<img width="1137" height="293" alt="Screenshot 2026-02-22 150011" src="https://github.com/user-attachments/assets/135d1b4c-96f9-4999-9c9b-7368b8e2e6a4" />


### 5. Automation Using Applied Steps

Power Query automatically recorded all transformation steps, enabling:

* Automatic data cleaning
* Reusability of transformation logic
* One-click refresh capability for future datasets

### 6. Load Clean Data

* Loaded transformed dataset into Excel
* Prepared dataset for further analysis and visualization

---

## Key Skills Demonstrated

* Power Query data import
* Data cleaning and preprocessing
* Data transformation
* Custom column creation
* Conditional logic implementation
* Data aggregation using Group By
* Query automation using Applied Steps
* Preparing data for reporting and dashboards

---

## Tools Used

* Microsoft Excel
* Power Query Editor

---

## Key Learning Outcomes

Through this project, I gained hands-on experience in:

* Automating data cleaning workflows
* Transforming raw data into analysis-ready format
* Using Power Query to improve efficiency and productivity
* Applying professional data preparation techniques used by Data Analysts

<img width="939" height="606" alt="image" src="https://github.com/user-attachments/assets/916e6661-d901-47e2-b3a4-c1521f2704fb" />

---

## Conclusion

Power Query is a powerful tool for automating data preparation tasks. This project helped build a strong foundation in data cleaning, transformation, and automation, which are essential skills for Data Analyst roles.

The techniques learned in this project can be applied to real-world datasets to improve efficiency and ensure consistent, accurate data preparation.

