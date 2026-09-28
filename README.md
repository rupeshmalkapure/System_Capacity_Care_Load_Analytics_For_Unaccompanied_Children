# System Capacity & Care Load Analytics for Unaccompanied Children

## Project Overview

This project analyzes system capacity, care load, intake patterns, backlog dynamics, and periods of prolonged operational strain associated with unaccompanied children moving through U.S. Customs and Border Protection (CBP) custody and Health and Human Services (HHS) care.

The analysis uses operational time-series data covering the period from **12 January 2023 to 21 December 2025**. Python and Pandas were used for data preparation, transformation, and feature engineering, while Tableau was used to develop an interactive dashboard for monitoring key operational patterns.

---

## Project Objectives

- Analyze overall System Load and its variation over time.
- Compare children in CBP custody with children in HHS care.
- Examine Net Daily Intake and backlog patterns.
- Identify High Load and Sustained High Load periods.
- Detect periods of Prolonged Strain.
- Analyze short-term and longer-term trends using 7-day and 14-day moving averages.
- Develop an interactive Tableau dashboard for operational monitoring and analysis.

---

## Tools & Technologies

- **Python**
- **Pandas**
- **Jupyter Notebook**
- **Tableau**
- **CSV / Data Analysis**
- **Time-Series Analysis**
- **Feature Engineering**
- **Data Visualization**

---

## Key Analytical Measures

The following analytical measures were used or developed during the project:

- **System Load**
- **Net Daily Intake**
- **High Load**
- **Sustained High Load**
- **High Load Duration**
- **Prolonged Strain**
- **7-Day Moving Average**
- **14-Day Moving Average**
- **Backlog Accumulation Rate**

High Load was defined as a System Load greater than the overall mean System Load, while duration-based indicators were used to distinguish temporary fluctuations from sustained operational pressure.

---

## Key Findings

- **Average System Load:** 6,233 children
- **Maximum System Load:** 11,762 children — 20 December 2023
- **Minimum System Load:** 2,002 children — 24 August 2025
- **Average CBP Custody:** 171.5 children
- **Average HHS Care:** 6,061 children
- **Average Net Daily Intake:** -44.74 children
- **Maximum Net Daily Intake:** +206 — 12 February 2024
- **Minimum Net Daily Intake:** -465 — 11 January 2024
- **High Load Observations:** 429
- **Prolonged Strain Observations:** 411
- **Aggregated Backlog Accumulation Rate:** 33.06%

> **Note:** The 33.06% Backlog Accumulation Rate represents the aggregated result of the Tableau table calculation under the applied view and aggregation settings. It should not be interpreted as total backlog growth of 33.06% over the entire study period.

---

## Tableau Dashboard

The interactive Tableau dashboard provides visual analysis of:

- System Load trends
- CBP vs HHS care load
- Net Daily Intake
- High Load and Prolonged Strain
- Backlog Accumulation Rate
- Operational patterns over time

### Live Interactive Dashboard

**[View the Interactive Tableau Dashboard](https://public.tableau.com/app/profile/rupesh.malkapure5108/viz/SYSTEMCAPACITYCARELOADANALYTICSFORUNACCOMPANIEDCHILDREN_17902316822610/Dashboard1))**

---

## Project Files

| File | Description |
|---|---|
| `System Capacity & Care Load Analytics for Unaccompanied Children.ipynb` | Python and Pandas data analysis and feature engineering |
| `System Capacity & Care Load Analytics for Unaccompanied Children.csv` | Dataset used for the analysis |
| `System Capacity & Care Load Analytics for Unaccompanied Children.twb` | Tableau workbook containing the dashboard and visualizations |
| `System Capacity & Care Load Analytics for Unaccompanied Children.pdf` | Complete research paper and analytical findings |

---

## Analytical Approach

The project followed a structured analytics workflow:

**Data Preparation → Data Cleaning → Feature Engineering → Exploratory Analysis → Time-Series Analysis → Operational KPI Analysis → Tableau Visualization → Interpretation & Recommendations**

Python and Pandas were used to prepare and transform the operational dataset. Derived indicators were created to measure overall system load, daily intake patterns, sustained high-load conditions, moving averages, and prolonged strain. Tableau was then used to transform these analytical measures into an interactive dashboard.

---

## Business / Operational Value

This project demonstrates how operational time-series data can be transformed into meaningful indicators for identifying changes in system load and sustained periods of pressure.

The analytical framework supports:

- Monitoring changes in care load over time.
- Distinguishing temporary load spikes from sustained strain.
- Comparing operational load across CBP custody and HHS care.
- Tracking intake and backlog-related patterns.
- Supporting structured, data-driven operational monitoring.

---

## Skills Demonstrated

**Python | Pandas | Data Cleaning | Feature Engineering | Time-Series Analysis | KPI Development | Tableau | Dashboard Development | Data Visualization | Analytical Interpretation | Research & Reporting**

---

## Author

**Rupesh Sunilrao Malkapure**

Management Consulting | Business Analytics | Data Analytics
