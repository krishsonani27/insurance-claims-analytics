# Insurance Claims Analytics

## Overview
This project demonstrates an end-to-end analytics workflow for the insurance domain.  
Data was stored and queried in **MS SQL Server**, then visualized in **Power BI** to uncover business insights around insurance claims, premiums, and policy performance.

---

## Objectives
- Store and manage raw insurance data in SQL Server.
- Perform queries and profiling for data validation.
- Build interactive Power BI dashboards for executives.
- Analyze key metrics such as premiums, coverage, claims, and policy activity.

---

## Tech Stack
- **Database**: Microsoft SQL Server  
- **Query Language**: SQL  
- **Visualization**: Power BI Desktop  

---

## Project Workflow
1. **Data Ingestion**  
   - Created a database `Insurancedb` in SQL Server.  
   - Imported insurance dataset with customer, policy, and claim details.  

2. **Data Processing**  
   - SQL queries for exploring and validating data.  
   - Profiling by gender, policy type, and claim status.  

3. **Visualization (Power BI)**  
   - Premium, Coverage, and Claim KPIs.  
   - Claims by Status (Settled, Pending, Rejected).  
   - Premium Amount by Policy Type.  
   - Active vs Inactive Policies.  
   - Claim Amount by Age Group.  

---

## Dashboard Preview
![Dashboard Screenshot](screenshots/dashboard.png)  
![SQL Data](screenshots/sql_data.png)  

---

## Insights
- Total **Premiums**: 5.98M  
- Total **Coverage**: 600.55M  
- Total **Claims**: 16.91M  
- Majority of claims come from **Travel** policies.  
- **Adults** have the highest claim amounts, followed by elders.  
- About **58% policies** are inactive.  

---

## How to Run
1. Import the provided SQL script into Microsoft SQL Server.  
2. Open `InsuranceDashboard.pbix` in Power BI Desktop.  
3. Connect to your local SQL Server instance.  
4. Explore the dashboard interactively.  

---

## Future Improvements
- Automate ETL pipeline for incremental data refresh.  
- Add sentiment analysis on claim notes.  
- Deploy dashboard to Power BI Service with scheduled refresh.
