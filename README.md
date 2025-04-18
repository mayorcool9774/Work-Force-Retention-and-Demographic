#  Workforce Retention and Demographic Insights Dashboard

This Power BI project analyzes employee data to uncover trends in workforce retention, experience, and demographic patterns. By combining **Power Query** transformations with **DAX-generated KPIs**, the dashboard provides clear answers to key HR business questions.

---

##  Dashboard Preview


![employee workforce dashboard_page-0001](https://github.com/user-attachments/assets/c17a7af2-6836-40bd-95d3-a9f23dae6750)

---

##  Project Review

This project gave me practical experience in applying Power Query for data preparation and DAX for performance metrics. It challenged me to interpret HR related data from a business perspective while presenting it in a clean, interactive format with Power BI. The insights revealed clear retention trends and employee patterns that could guide data driven HR decisions in a real organization.

I also gained deeper understanding in creating derived columns, developing meaningful KPIs, and building a dashboard that tells a complete story — from raw data to business insights.
---

##  Tools Used

- **Power BI** – For building interactive visualizations and calculating KPIs  
- **Power Query** – For data cleaning, column derivation, and preparation  
- **DAX (Data Analysis Expressions)** – For creating performance metrics and calculated fields

---

##  Research Questions

1. **What is the distribution of educational qualifications among employees?**  
2. **How does the length of service (Joining Year) vary across different cities?**  
3. **Is there a correlation between Payment Tier and Experience in Current Domain?**  
4. **What is the gender distribution within the workforce?**  
5. **Are there any patterns in leave-taking behavior among employees?**

---

##  Key KPIs (Created with DAX)

- **Total Staff**  
- **Leave Count**  
- **Stay Count**

These KPIs were derived from the `Decision` column, which was calculated from the original `LeaveOrStay` column (`1` = Left, `0` = Stayed).

---

##  Data Transformation & Calculated Columns

###  In Power Query:
- Cleaned and formatted the dataset
- Renamed columns and handled inconsistencies
- Derived new columns for clearer insights

###  Calculated Columns:

- **Decision**  
  - Derived from `LeaveOrStay`:  
    `1` = Employee Left, `0` = Employee Stayed  

- **Experience Level**  
  - Based on `Experience in Current Domain`:  
    - `0–2 years` → Junior  
    - `3–4 years` → Mid-level  
    - `5+ years` → Senior  

- **Career Start Age**  
  - Calculated as:  
    `CareerStartAge = 2025 - JoiningYear`

---

##  Dashboard Highlights

- **Treemap**: Avg. service years by city  
- **Bar Charts**: Education & experience breakdown  
- **Donut Chart**: Gender distribution  
- **Stacked Bar**: Experience level segmentation  
- **Dynamic Table**: Leave behavior by education, tier, and benching status  
- **KPI Cards**: Total staff, Stay count, Leave count


---

##  Contact

- [LinkedIn](https://www.linkedin.com/in/mayor9774/) 
- [Email](mayowa24.jan@gmail.com)

---
