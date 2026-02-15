Excel Data Analysis – Text & Date Functions
📌 Overview

This project demonstrates the practical use of essential Excel Text and Date functions used in real-world MIS reporting and Data Analytics. The objective was to clean raw employee data, extract structured information from IDs, and calculate employee experience dynamically.

These functions are widely used in HR analytics, reporting systems, and business dashboards.

📂 Dataset Used

The dataset contains the following columns:

Full Name

Employee ID

Joining Date

<img width="384" height="179" alt="image" src="https://github.com/user-attachments/assets/a7221fb2-3b5b-4fb6-b29f-f342809dcd4a" />

🧹 Data Cleaning & Transformation Performed

The following transformations were applied:

1. Clean Name Formatting

Standardized names using:

=PROPER(A2)

<img width="634" height="229" alt="image" src="https://github.com/user-attachments/assets/4acfec43-1a9d-4f51-8c07-0074a5ace3b1" />

2. Extract Department Code

Extracted department dynamically from Employee ID:

=LEFT(B2,LEN(B2)-4)

<img width="725" height="231" alt="image" src="https://github.com/user-attachments/assets/6d6f9e78-bbf5-4b4b-aaef-5d083e8e8dde" />

3. Extract Employee Number

=RIGHT(B2,4)

<img width="1020" height="223" alt="image" src="https://github.com/user-attachments/assets/54b03933-fbe5-4902-bd8c-e4161abc1109" />

4. Calculate Employee Experience

=DATEDIF(C2,TODAY(),"Y")

<img width="1030" height="175" alt="image" src="https://github.com/user-attachments/assets/d5e0e68e-2adc-4844-9247-f871e4a83548" />

5. Extract Month and Year

Month: =MONTH(C2)

Year: =YEAR(C2)

<img width="1211" height="226" alt="image" src="https://github.com/user-attachments/assets/817cc3d3-41cb-4ec5-87b7-ae7e76ffdf82" />

6. Combine Information Using TEXTJOIN

=TEXTJOIN("-",TRUE,E2,F2)

<img width="1472" height="222" alt="image" src="https://github.com/user-attachments/assets/ca68503e-0a01-48a8-a368-a0b2d450aef9" />


**📊 Final Output Columns Created**

Clean Name

Department Code

Employee Number

Experience (Years)

Joining Month

Joining Year


**💼 Business Use Case**

In real-world business environments, employee data is often stored in raw formats where important information such as department codes and employee experience must be extracted and standardized.

This project demonstrates how Excel Text and Date functions can be used to support business operations such as:

Identifying employee departments from structured IDs

Calculating employee experience for HR analysis and appraisal decisions

Preparing clean datasets for MIS reports and dashboards

Standardizing employee records for accurate reporting

Preparing structured data for visualization tools like Power BI and Tableau

These techniques are commonly used by Data Analysts, MIS Executives, and HR Analysts to transform raw data into actionable insights.


**📈 Project Impact**

This project demonstrates the practical application of Excel Text and Date functions in transforming raw organizational data into structured, analysis-ready information.

Through this exercise, I was able to:

Convert unstructured employee data into clean and standardized format

Extract meaningful business information such as department codes and employee numbers

Calculate employee experience dynamically using real-time date functions

Prepare structured datasets suitable for MIS reporting and dashboard creation

Apply data cleaning techniques commonly used in real-world business environments

These skills are fundamental in Data Analyst and MIS roles, where raw data must be cleaned, transformed, and prepared before analysis and visualization.

This project reflects my hands-on learning approach and commitment to building strong foundational skills in data analytics.


**🛠 Tools Used**

Microsoft Excel

**🚀 Key Learning Outcome**

This project strengthened my ability to clean raw data and extract meaningful information using Excel functions. These skills form the foundation of real-world data analysis and reporting workflows.

For concept explanation, interview-focused discussion, and learning insights, you can read my Medium article:

🔗 Read Medium Article:

## 👩‍💻 Author

Chandana  
Aspiring Data Analyst

🔗 LinkedIn: [https://linkedin.com/in/your-link  ](https://www.linkedin.com/in/chandana-ammagaripeta-amarendra/)

Skilled in Excel, SQL, Power BI, and Python.  
Currently building hands-on projects to strengthen my data analytics skills.
