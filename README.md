# 🗺️ U.S. Health Profile Dashboard (Behavioral Risk Factor Surveillance System (BRFSS) 2021–2023)

## Overview

This project demonstrates my ability to extract, transform, and load (ETL) data into an interactive, user-friendly dashboard for decision-making. I used R to process raw ASCII files from the Behavioral Risk Factor Surveillance System (BRFSS), then visualized key indicators in Tableau to support exploratory analysis across time and geography.

## 🔍 Purpose

The goal was to simulate a real-world workflow where a data analyst prepares messy, multi-year data and delivers clean, actionable insights to end users. This project was designed to highlight:

- **Data extraction and transformation** using R
- **Data cleaning and structuring** across multiple years (2021–2023)
- **Interactive dashboard design** in Tableau for flexible, self-serve exploration

## 🧰 Tools Used

- **R** (data cleaning, transformation, and integration)
- **Tableau** (dashboard design and data visualization)
- **GitHub** (project version control and portfolio hosting)
- **BRFSS** (data source)

---

## 📊 Dashboard Preview

👉 **[View the Interactive Dashboard (Tableau Public)](https://public.tableau.com/app/profile/tony.bardo/viz/USHealthProfile/Dashboard1?publish=yes)**

---

## 🧱 Project Structure

```bash
us-health-profile/
├── data/
│   ├── LLCP2021.asc
│   ├── LLCP2022.asc
│   ├── LLCP2023.asc
│   ├── brfss2021.dat
│   ├── brfss2022.dat
│   ├── brfss2023.dat
│   ├── brfss_2021_clean.dat
│   ├── brfss_2022_clean.dat
│   ├── brfss_2023_clean.dat
│   ├── brfss_combined.dat
│   └── brfss_combined.csv  # Cleaned, merged data ready for Tableau
├── code/
│   └── brfss_script.R
├── dashboard/
│   └── BRFSS.twb  # Tableau workbook file
└── README.md
```
---

## 📈 Key Features of the Dashboard

- Nationwide and regional maps showing prevalence of:
  - Diabetes
  - Obesity (based on BMI)
  - Poor or Fair Self-Rated Health
- Trend lines over time for:
  - The U.S. overall
  - Regions (Northeast, Midwest, South, West)
  - Individual states
- Dropdown filters for:
  - Year (2021–2023)
  - Health outcome
  - Region or state
- Interactive legends and dynamic titles

Designed for public health staff and policy decision-makers to explore trends, compare regions, and identify high-priority states or outcomes.

---

## 🔄 Data Source

- U.S. CDC's Behavioral Risk Factor Surveillance System (BRFSS)  
  🔗 https://www.cdc.gov/brfss/annual_data/annual_data.htm

---

## 🧠 Key Skills Demonstrated

✅ Extracting and cleaning raw ASCII data using R  
✅ Standardizing and combining multi-year survey data  
✅ Creating calculated fields and filtering logic  
✅ Designing user-friendly dashboards with responsive interactivity  
✅ Translating complex data into policy-relevant insights

---

## 📬 Contact

**Tony Bardo**  

📫 bardoar@gmail.com  
