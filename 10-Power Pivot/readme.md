# Excel Power Pivot Data Modeling Project

## Overview

This project demonstrates how to use **Power Pivot in Excel** to build a structured Data Model, create relationships between multiple tables, and perform advanced data analysis using DAX measures.

The objective was to simulate a real-world data modeling workflow where raw transactional data is organized into related tables and analyzed efficiently.

---

## Dataset Structure

The project uses three related tables:

### 1. Customers Table

Contains customer information.

| Column Name   | Description                         |
| ------------- | ----------------------------------- |
| Customer_ID   | Unique identifier for each customer |
| Customer_Name | Customer name                       |
| Region        | Customer region                     |

---

### 2. Products Table

Contains product details.

| Column Name  | Description                        |
| ------------ | ---------------------------------- |
| Product_ID   | Unique identifier for each product |
| Product_Name | Product name                       |
| Category     | Product category                   |

---

### 3. Orders Table

Contains transactional sales data.

| Column Name | Description              |
| ----------- | ------------------------ |
| Order_ID    | Unique order identifier  |
| Customer_ID | Links to Customers table |
| Product_ID  | Links to Products table  |
| Quantity    | Number of units sold     |
| Sales       | Sales amount             |

---

## Data Model

A **Star Schema Data Model** was created using Power Pivot:

* Customers → Orders (One-to-Many relationship)
* Products → Orders (One-to-Many relationship)

Orders table acts as the **Fact Table**
Customers and Products act as **Dimension Tables**

---

## Relationships Created

| From Table | Column      | To Table | Column      |
| ---------- | ----------- | -------- | ----------- |
| Customers  | Customer_ID | Orders   | Customer_ID |
| Products   | Product_ID  | Orders   | Product_ID  |

These relationships enable multi-table analysis.

<img width="866" height="549" alt="Screenshot 2026-02-22 170758" src="https://github.com/user-attachments/assets/f8c3e1f5-1c59-45ff-b6d3-1027127fc3de" />

---

## Measures Created (DAX)

The following measures were created using DAX:

### Total Sales

```
Total Sales = SUM(Orders[Sales])
```

### Total Orders

```
Total Orders = COUNT(Orders[Order_ID])
```

### Unique Customers

```
Unique Customers = DISTINCTCOUNT(Orders[Customer_ID])
```

### Average Sales per Order

```
Average Sales = DIVIDE([Total Sales], [Total Orders])
```

<img width="515" height="673" alt="Screenshot 2026-02-22 171001" src="https://github.com/user-attachments/assets/47896584-4a2d-45ea-8400-0014e5e44ac7" />

---

## Analysis Performed

Using Pivot Table connected to the Data Model:

* Total Sales by Region
* Total Sales by Category
* Customer-level analysis
* Product-level analysis

<img width="290" height="380" alt="Screenshot 2026-02-22 171015" src="https://github.com/user-attachments/assets/b87182e1-6531-4e2d-8f83-37cabec09007" />

---

## Skills Demonstrated

* Power Pivot Data Modeling
* Creating Relationships
* Star Schema Design
* DAX Measures Creation
* Multi-table Analysis
* Data Model-based Pivot Table Analysis

---

## Tools Used

* Microsoft Excel
* Power Pivot
* DAX (Data Analysis Expressions)

---

## Key Learning Outcomes

This project helped me understand:

* How to build structured data models
* How relationships enable multi-table analysis
* Difference between measures and calculated columns
* How DAX is used for dynamic calculations
* How professional data models are designed

---

## Project Status

Completed as part of my Excel Data Analytics Learning Journey.

