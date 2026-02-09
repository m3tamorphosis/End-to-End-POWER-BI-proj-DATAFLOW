# 📊 Loan Default & Financial Risk Analytics Dashboard  
**Power BI Fabric | SQL Server | DAX | Data Modeling**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-005571?style=flat)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-4CAF50?style=flat)

---

## 📌 Project Overview
This project delivers an **end-to-end loan default and financial risk analytics solution** using **Power BI Fabric, SQL Server, and advanced DAX measures**.
The dashboard analyzes **borrower demographics, credit behavior, loan distribution, and default risk trends** to support data-driven financial decision-making. The solution integrates data engineering, modeling, validation, and visualization into a single analytics workflow.
<img width="1353" height="744" alt="image" src="https://github.com/user-attachments/assets/82286250-dd2d-4834-a073-76a3f9e2c922" />
<img width="1354" height="762" alt="image" src="https://github.com/user-attachments/assets/a765e1e0-7a1b-4131-bcb3-cce74b676438" />
<img width="1349" height="748" alt="image" src="https://github.com/user-attachments/assets/e68d4a16-8d66-45b5-a548-4ca768bfee2d" />



---

## 🏗️ Architecture & Data Flow
1. **Power BI Fabric – Dataflow Gen1**
   - Selected and extracted loan data from Fabric Dataflows  
2. **SQL Server / MySQL Integration**
   - Uploaded and validated datasets
   - Checked column structure and data types
3. **Power BI Data Model**
   - Created calculated columns and validation tables
   - Implemented complex DAX measures
4. **Power BI Reports**
   - Designed interactive dashboards
   - Published to **Power BI Fabric**

---

## 🧹 Data Preparation & Validation
- Column and data type validation
- Null and blank value checks
- Data consistency verification
- Created calculated columns for analytical grouping
- Built validation tables to ensure measure accuracy

---

## 📐 DAX Measures Implemented
- **Loan Amount by Purpose**
- **Average Income by Employment Type**
- **Default Rate by Employment Type**
- **Default Rate by Age Group**
- **Default Rate by Year**
- **Median Loan Amount by Credit Score Bins**
- **Average Loan Amount (High Credit Score)**
- **Total Loan Amount by Credit Score Bins**
- **Total Loan Amount (Middle-Age Adults)**
- **Loan Amount by Education Type**
- **Year-over-Year (YoY) Loan Amount**
- **YoY Default Loan Change**
- **Year-to-Date (YTD) Loan Amount**

---

## 📊 Dashboard Pages & Visuals

### 🔹 Page 1: Loan Overview
- KPI: Loan Amount by Purpose
- Default Rate (%) by Employment Type
- Average Income by Employment Type
- Loan Amount by Age Group
- Default Rate Trend by Year

### 🔹 Page 2: Applicants Demographics & Financial Profile
- Median Loan Amount by Credit Score Category (KPI / Line Chart)
- Average Loan Amount (High Credit) by Age Group & Marital Status (Donut Chart)
- Total Loan Amount by Credit Score Bins (Line Chart)
- Loan Amount (Middle-Age Adults) by Mortgage & Dependents (Clustered Column)
- Number of Loans by Education Type (Line Chart)

### 🔹 Page 3: Financial Risk Metrics
- Year-over-Year Loan Amount Trend
- Year-over-Year Default Loan Trend
- YTD Loan Amount by Credit Score Bin & Marital Status (Ribbon Chart)
- Income Bracket Analysis by Employment Type (Ribbon Chart)

---

## 🗂 Dataset Columns
- LoanID
- Age
- Income
- LoanAmount
- CreditScore
- MonthsEmployed
- NumCreditLines
- InterestRate
- LoanTerm
- DTIRatio
- Education
- EmploymentType
- MaritalStatus
- HasMortgage
- HasDependents
- LoanPurpose
HasCoSigner
Default
Loan Date (DD/MM/YYYY)
---

## 🛠 Tools & Technologies
- **Power BI Fabric**
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **SQL Server / MySQL**
- **Power Query**
- **Dataflow Gen1**

---

## 🎯 Key Insights Generated
- Identification of high-risk borrower segments
- Credit score and employment impact on default probability
- Loan distribution patterns by demographics
- Time-based financial risk monitoring using YoY and YTD metrics
- Enhanced visibility into income, education, and marital status effects on loans

---

## 🚀 Use Case
This project is ideal for:
- Financial risk analysis
- Credit portfolio monitoring
- Loan default prediction support
- Business intelligence reporting in banking and finance

