# Loan Default Risk Analysis Dashboard

### Dashboard Link: restricted Power BI Access

---

## Problem Statement

This dashboard helps financial institutions analyze loan distribution, customer profiles, and default risk patterns. It enables better decision-making by identifying high-risk segments and understanding key factors such as income, employment, and credit score.

---

## Steps Followed

- **Step 1: Data Setup using Dataflow**
  - Created Dataflow in Power BI Fabric environment
  - Used SQL interface to manually input and structure data as tables
  - Stored and managed data within Dataflow for centralized access

- **Step 2: Environment & Connectivity Setup**
  - Installed On-Premises Data Gateway for secure data transfer
  - Set up SQL Server Management Studio (SSMS) and SQL Workbench 2022
  - Established connection between Dataflow and Power BI

- **Step 3: Data Loading in Power BI**
  - Imported data from Dataflow into Power BI Desktop
  - Verified successful connection and data availability

- **Step 4: Data Cleaning & Profiling**
  - Performed column profiling (data types, distributions, null values)
  - Cleaned and transformed data using Power Query
  - Ensured data accuracy and consistency

- **Step 5: Data Modeling & DAX**
  - Created calculated columns and measures using DAX
  - Applied business logic for KPIs and metrics
  - Structured model for efficient reporting

- **Step 6: Data Visualization**
  - Designed interactive dashboards in Power BI
  - Created visuals such as:
    - KPI Cards
    - Bar Charts and Line Charts
    - Filters and Slicers for interactivity

- **Step 7: Dashboard Design**
  - Applied clean layout and visual theme
  - Focused on readability and business insights
  - Organized visuals for storytelling

- **Step 8: Deployment & Sharing**
  - Published report to Power BI Service
  - Created workspace for project
  - Configured scheduled refresh for automatic updates

---

## Snapshot of Dashboard

### Loan Default & Overview
![Demographics](Screenshot%202026-04-21%20232656.png)

### Applicant Demographics & Financial Profile
![Overview](image.png)

### Financial Risk Metrics
![Risk](Financial%20Risk%20Metrics.P1.png)

---

## Insights

### [1] Loan Distribution
- Highest loan amounts observed in home and business categories

### [2] Employment Analysis
- Full-time employees have higher income  
- Unemployed individuals show highest default rates  

### [3] Credit Score Impact
- Medium credit score segment dominates loan distribution  

### [4] Age Group Analysis
- Adults receive highest loan amounts  
- Teen group has lowest  

### [5] Risk Trends
- Default rates fluctuate year over year  

---

## Conclusion

This dashboard helps identify high-risk customers and improves loan decision strategies by providing insights into financial behavior and default trends.

---

## Tools Used

- Power BI  
- DAX  
- Data Modeling  
- Data Visualization  
