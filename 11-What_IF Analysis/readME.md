# Excel What-If Analysis Project (Goal Seek, Scenario Manager, Data Tables)
## 1. Project Overview

This project demonstrates the use of Excel’s What-If Analysis tools to analyze how changes in input variables affect business outcomes such as Revenue, Cost, and Profit.

A dataset containing 100 sales records was used to simulate real-world business conditions. The analysis focuses on profit forecasting, scenario comparison, and decision-making support.

This project reflects real Data Analyst responsibilities in sales, finance, and operations domains.

## 2. Dataset Description

The dataset contains 100 rows with the following columns:

- Product_ID – Unique identifier for each product

- Product_Name – Name of the product

- Region – Sales region

- Price_per_Unit – Selling price per unit

- Quantity_Sold – Number of units sold

- Revenue – Total sales revenue (Price × Quantity)

- Cost_per_Unit – Cost per unit

## 3. Profit Calculation Logic

The following formulas were used:

Revenue:

`Revenue = Price_per_Unit × Quantity`

Total Cost:

`Total_Cost = Cost_per_Unit × Quantity`

Profit:

`Profit = Revenue − Total_Cost`

Profit is the key performance indicator used for What-If Analysis.

## 4. What-If Analysis: Concept Explanation

What-If Analysis is an Excel feature used to evaluate how changes in input variables affect calculated results.

**It helps answer business questions such as:**

- How many units must be sold to reach a profit target?

- What happens if price increases or decreases?

- How does profit change for different sales volumes?

**Excel provides three main What-If Analysis tools:**

- Goal Seek

- Scenario Manager

- Data Tables

## 5. Goal Seek – Theory and Practical Implementation

#### Definition

Goal Seek is used to determine the required input value needed to achieve a specific target output.

It works by adjusting one input variable until the desired result is reached.

Business Problem Solved

#### Objective:

Determine how many units must be sold to achieve a target profit of ₹500,000.

**Method**

Profit formula:

`Profit = (Price − Cost) × Quantity`

Using Goal Seek:

Set Cell: Profit cell

To Value: 500000

By Changing Cell: Quantity cell

Excel automatically calculated the required Quantity.

<img width="306" height="199" alt="Screenshot 2026-02-25 114726" src="https://github.com/user-attachments/assets/eedc5da7-a693-4cbd-8f4e-38da074a47fd" />

**Business Use Case**

- Goal Seek is used in:

- Sales target planning

- Revenue forecasting

- Production planning

- Financial analysis

## 6. Scenario Manager – Theory and Practical Implementation

#### Definition

Scenario Manager is used to evaluate multiple business situations by changing input variables and comparing results.

It allows analysts to create and compare different scenarios such as:

- Worst case

- Expected case

- Best case

Business Problem Solved

#### Objective:

Compare profit under different price and quantity combinations.

**Example scenarios:**

- Worst Case:

Price = Lower value

Quantity = Lower value

- Expected Case:

Price = Medium value

Quantity = Medium value

- Best Case:

Price = Higher value

Quantity = Higher value

Excel calculated profit for each scenario.

**Business Use Case**

**Scenario Manager is used in:**

- Risk analysis

- Financial forecasting

- Budget planning

- Strategic decision-making

<img width="502" height="472" alt="Screenshot 2026-02-25 115056" src="https://github.com/user-attachments/assets/5438a93a-1a3d-4841-bb15-66cada5c6499" />


## 7. Data Tables – Theory and Practical Implementation

#### Definition

Data Tables are used to analyze how changing one or two variables affects a formula result.

This project used a One-Variable Data Table.

Business Problem Solved

#### Objective:
Analyze how profit changes for different Quantity values.

Quantity values tested:
5, 10, 15, 20, …, 50

Excel automatically calculated profit for each Quantity.

**Key Concept**

Excel substitutes each Quantity value into the Profit formula and recalculates the result.


**Business Use Case**

Data Tables are used in:

- Profit forecasting

- Sales analysis

- Sensitivity analysis

- Business planning

## 8. Key Insights from Analysis

**The analysis revealed:**

- Profit increases as Quantity increases

- Profit depends directly on Price, Cost, and Quantity

- What-If Analysis helps predict business performance

- These tools support data-driven decision making

## 9. Skills Demonstrated

This project demonstrates the following Data Analyst skills:

- Advanced Excel

- What-If Analysis

- Goal Seek

- Scenario Manager

- Data Tables

- Financial Analysis

- Profit Forecasting

- Business Decision Support

## 10. Real-World Applications

**These techniques are used by companies such as:**

- E-commerce companies for sales forecasting

- Hospitals for revenue planning

- Retail companies for profit analysis

- Finance teams for budgeting and forecasting

## 11. Conclusion

This project successfully demonstrates the use of Excel What-If Analysis tools to evaluate business performance under different conditions.

These techniques help organizations make informed, data-driven decisions and are essential skills for Data Analysts.

## 12. Tools Used

- Microsoft Excel

- What-If Analysis Tools

- Sales Dataset (100 rows)

## 13. Project Status

Completed

This project is part of my Data Analyst portfolio.
****
