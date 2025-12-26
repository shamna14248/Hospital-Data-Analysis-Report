# Hospital ER Data Analysis Report - Power BI Project

## Project Overview

This Power BI project provides a comprehensive analysis of Hospital Emergency Room (ER) operations covering a 19-month period from **April 2023 to October 2024**. The dashboard is designed to monitor patient flow, departmental efficiency, and patient satisfaction to help hospital administrators optimize resource allocation.

---

## Key Features & Dashboards

### 1. Consolidated View

A high-level executive summary of the ER's performance metrics.

* **KPI Cards:** Total Patients (9,216), Average Wait Time (35.3 Min), Patient Satisfaction Score (4.99/10), and Patients Referred (3,816).
* **Demographics:** Breakdowns by Age Group, Gender, and Race.
* **Operational Insights:** Heatmap of patient volume by Day and Hour, Admission Status (Admitted vs. Not Admitted), and Departmental Referral volume.

### 2. Monthly View

Allows for granular time-series analysis.

* **Trend Lines:** Visualizes fluctuations in patient volume and wait times month-over-month.
* **Filtering:** Users can filter by specific years and months to track seasonal peaks.

### 3. Patient Details

A tabular drill-through page providing row-level data for clinical or administrative review.

* **Fields included:** Patient ID, Name, Gender, Age, Admission Date, Race, Wait Time, Department Referral, and Admission Status.

### 4. Key Takeaways

A summary report highlighting critical descriptive analysis:

* **Busiest Periods:** Mondays and Saturdays are peak days; 11 AM, 1 PM, 7 PM, and 11 PM are peak hours.
* **Top Referrals:** General Practice (1,840 cases) and Orthopedics (995 cases).
* **Admission Patterns:** Roughly 50% of patients are admitted (4,612), while the rest (4,604) are treated and released.

---

## Technical Specifications

* **Tool:** Power BI Desktop
* **Data Sources:** Hospital ER Dataset (CSV/Excel)
* **Data Modeling:** Includes a dedicated `Date Table` for time intelligence and the primary `Hospital ER_Data` table.
* **Visuals Used:** Heatmaps, Donut Charts, Bar Charts, KPI Cards, and Slicers.

---

## Insights & Recommendations

* **Improve Wait Times:** With an average wait time of 35.3 minutes, staffing should be optimized during the identified peak hours (late morning and late evening).
* **Patient Experience:** The satisfaction score of 4.99 indicates a significant opportunity for service improvement.
* **Resource Allocation:** Since 50% of ER visits result in admissions, ensure a streamlined handoff process between the ER and hospital wards.

---

## How to Use

1. **Navigation:** Use the vertical button bar on the left to switch between "Monthly View", "Consolidated View", "Patient Details", and "Key Takeaways".
2. **Filtering:** Use the date slicer at the top right to adjust the reporting period.
3. **Cross-Filtering:** Click on any chart element (e.g., a specific age group) to filter the entire page by that segment.

