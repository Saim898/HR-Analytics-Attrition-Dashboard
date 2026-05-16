# 📊 HR Analytics & Workforce Attrition Dashboard

[![Live Dashboard](https://img.shields.io/badge/View_Live_Project-Web_Page-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://saim898.github.io/HR-Analytics-Attrition-Dashboard/)

## 👥 Executive Summary
This interactive Power BI dashboard provides a comprehensive analysis of workforce demographics and employee attrition trends for an organization of **1,470 total employees**. Designed as a strategic resource for HR leadership and business executives, the report reveals a corporate **attrition rate of 16.1% (237 exited employees)**. By analyzing cross-sections of department data, gender distribution, specific job roles, and workforce stressors like overtime, this tool empowers decision-makers to identify at-risk teams and develop targeted retention strategies.

---

## 🛠️ Tech Stack & Key Metrics Built
* **BI Platform:** Microsoft Power BI Desktop
* **Data Modeling:** Custom `_Calculated Measures` table housing foundational DAX metrics.
* **Core KPIs Calculated (via DAX):**
  * `Total Employees` = Count of active headcount registry.
  * `Exited Employees` = Aggregated volume of workforce departures.
  * `Attrition Rate` = `DIVIDE([Exited Employees], [Total Employees], 0)` formatted cleanly as a percentage.

---

## 🔍 Key Insights & Dashboard Breakdown

### 1. Executive KPI Summary Cards
* **Total Headcount:** 1,470 active employees tracked.
* **Total Departures:** 237 employees have exited the company.
* **Corporate Baseline Turnover:** 16.1% benchmark attrition rate.

### 2. Analytical Visualizations
* **Turnover Context by Department:** A horizontal bar chart comparing overall department size against exited volume. The **Research & Development** department holds the highest absolute headcount and departure numbers, followed closely by **Sales**.
* **Gender Demographics Split:** A pie chart detailing attrition distribution by gender. Departures trend significantly higher among **Male employees (63.29% / 150 exits)** compared to **Female employees (36.71% / 87 exits)**.
* **The Overtime Impact Analysis:** A clustered column chart displaying total vs. exited employees divided by overtime status. The visual clearly indicates that while a smaller overall portion of the workforce works overtime ("Yes"), they represent a disproportionately high turnover risk factor for the company.
* **Granular Job Role Breakdown Matrix:** A deep-dive matrix table providing structural clarity across individual roles. Key problem areas are flagged instantly—for instance, **Sales Representatives** experience a critical attrition rate of **39.8%**, while **Laboratory Technicians** account for the highest absolute volume of exits at **62**.

### 3. Interactive Data Slicers
* **Business Travel Frequency Slicer:** Dynamically filters the workspace to isolate employees based on how often they travel (*Non-Travel, Travel_Frequently, Travel_Rarely*).
* **Education Field Slicer:** Instantly recalibrates the entire dashboard to analyze attrition behavior by academic backgrounds (*Life Sciences, Medical, Marketing, Technical Degree, Human Resources, Other*).

---

## 📂 File Directory Structure
Organize your repository matching this standard configuration layout to ensure your portfolio looks exceptionally polished:

```text
├── Data/
│   └── HR_Employee_Data.csv
├── Dashboard/
│   └── HR_Attrition_Dashboard.pbix
├── Screenshots/
│   └── HR_Dashboard_Overview.png
└── README.md
