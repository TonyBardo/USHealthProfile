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
