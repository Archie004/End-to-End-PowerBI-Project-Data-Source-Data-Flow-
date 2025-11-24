# 🏦 Loan Default Analysis Dashboard | Power BI & Dataflow

## Project Overview

This project focuses on building a robust, end-to-end **Business Intelligence (BI)** solution for a financial institution to monitor and analyze loan portfolio health, customer demographics, and financial risk metrics. The solution utilizes **Power BI Service Dataflow** for automated ETL and features advanced **DAX calculations** for deep trend and risk analysis.

## Key Features & Business Impact

* **Data Scale Management:** The solution was built to handle a significant volume of data, processing a loan dataset of **over 25,000 rows**, utilizing Power BI Dataflow for efficient ETL.
* **Risk Mitigation:** Provides dynamic monitoring of **Year-over-Year (YOY) Default Rate Changes** to alert stakeholders to negative trends.
* **Customer Segmentation:** Breaks down loan amount and risk by critical demographic factors (**Credit Score Bins, Age Groups, Marital Status, Education**) to refine underwriting criteria.
* **Automated Data Pipeline:** Implements a scalable ETL process using **Power BI Dataflow** and **Incremental Refresh** to handle large, growing datasets efficiently.
* **Advanced Analytics:** Calculates complex measures like Median Loan Amounts and YTD (Year-to-Date) Loan Volumes, providing deep financial context.

## Technical Stack & Skills Demonstrated

| Category | Tools & Technologies | Skills Highlighted |
| :--- | :--- | :--- |
| **Data Source & ETL** | SQL Server, Power BI Dataflow, Standard Mode Gateway | Data Pipeline Architecture, Cloud Service Configuration, Incremental Refresh, ETL |
| **Data Analysis** | Power BI Desktop, DAX (CALCULATE, SUMX, MEDIANX, FILTER, ALLEXCEPT) | Advanced Formula Design, Data Modeling (Star Schema), Financial Metric Calculation |
| **Visualization** | Power BI Visuals (Decomposition Tree, Line Charts, Donut Charts) | Dashboard Design, Data Storytelling, UI/UX for BI |
| **Deployment** | Power BI Service, Scheduled Refresh | Report Publishing, Access Management, Service Administration |

## Dashboard Pages & Analysis

The final Power BI report is organized into three main pages:

### 1. Loan Default & Overview 
* **Focus:** High-level trends and basic risk segmentation.
* **Key Visuals:** Loan Amount by Purpose, Average Income and Default Rate by Employment Type, and Default Rate (%) by Year.

### 2. Applicant Demographics and Financial Profile 

[Image of Applicant Demographics and Financial Profile Dashboard Page]

* **Focus:** Detailed segmentation of the customer base.
* **Key Visuals:** Median Loan Amount by Credit Score Category, Average Loan Amount by Age Groups and Marital Status, and Loan volume by Education Type.

### 3. Financial Risk Metrics 
* **Focus:** Advanced time-series analysis for proactive risk management.
* **Key Visuals:** YOY Loan Amount Change by Year, **YOY Default Loans Change by Year** (critical risk metric), and YTD Loan Amount by Credit Score Bins.

## Project Execution Workflow

The project followed a strict, methodical process (Steps 410-441), ensuring technical rigor:

1.  **Data Source Setup:** Installation & Configuration of **SQL Server** and **Standard Mode Gateway**, with the initial dataset containing **over 25,000 loan records** (410-412).
2.  **ETL & Dataflow:** Creating the **Dataflow using Power BI Service** and importing data into Power BI Desktop (413-414).
3.  **Data Quality:** **Data Types & Profiling** performed meticulously in Power Query Editor (416).
4.  **Advanced DAX Modeling:** Developing over a dozen complex DAX measures, including **Median Calculations** (MEDIANX), **Default Rates** (using ALLEXCEPT, COUNTROWS, DIVIDE), and **YOY Loan & Default Changes** (433, 434).
5.  **Visualization & Validation:** Designing all three dashboard pages and performing **Data Validation** checks after adding major visuals to ensure accuracy (e.g., 422, 424, 428, 431).
6.  **Deployment & Maintenance:** Setting up **Incremental Refresh** for the Dataflow (439) and **Publishing the report to Power BI Service** with scheduled refresh and sharing (440-441).

---

## 🔗 How to View (For Interviewer/Recruiter)

This project showcases a production-ready BI solution. A live demo is available upon request.
