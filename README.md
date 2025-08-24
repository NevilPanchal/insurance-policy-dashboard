# Insurance Policy Dashboard (Excel Cleaning + Power BI)

A simple data-cleaning and visualization project. I cleaned an insurance dataset in Excel (handling missing values) and then built an interactive dashboard in Power BI.

## 🧰 What I did

**Data Cleaning in Excel**
- Filled `Claim Amount` nulls with the **average (mean) claim amount**.
- Filled `Policy End Date` nulls as **`Policy Start Date + 365 days`**.
- Ensured correct data types for dates and numbers.

**Built a Power BI Dashboard**
- KPIs: Total Claim Amount, Total Policies, Min/Max Duration (days), Distinct Policy Year, Average Years.
- Visuals: 
  - Bar chart: **Sum of Claim Amount by Policy Year**
  - Line chart: **Count of Policy Start Date by Year**
  - Donut chart: **Sum of Claim Amount by Policy Type**
  - Table: record-level details
  - Slicers: Region, Policy Type, Claim Status

