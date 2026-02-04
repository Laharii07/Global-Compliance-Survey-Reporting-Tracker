
# 📊 Global Survey Data Quality & Reporting System (Excel-Based)

## 📌 Project Overview

This project demonstrates an **end-to-end Excel-based reporting system** designed to handle **raw global survey data**, apply **data quality controls**, perform **validated analysis**, and deliver **executive-ready insights**.

The solution follows **enterprise analytics best practices**, including:

* Raw data preservation
* Centralized validation rules
* Data quality tracking and logging
* Audit-friendly reporting
* Interactive dashboarding

---

## 🧠 Business Problem

Global survey data often comes from multiple regions and sources, leading to:

* Inconsistent formatting
* Missing or invalid values
* Unreliable metrics if data quality is not controlled

Leadership requires:

* Trustworthy metrics
* Transparent data quality handling
* Simple, interactive reporting views

This project solves that by introducing a **structured validation and reporting workflow**.

---

## 🏗️ Solution Architecture

```
Raw_Data
   ↓
Data_Validation (Control Tables)
   ↓
Clean_Data (Validation Flags & Standardization)
   ↓
Data_Quality_Checks & Data_Quality_Log
   ↓
Pivot Analysis
   ↓
Executive Summary & Interactive Dashboard
```

---

## 📁 Workbook Structure

| Sheet Name                 | Purpose                                              |
| -------------------------- | ---------------------------------------------------- |
| **01_Raw_Data**            | Original survey data (unchanged, audit-safe)         |
| **02_Data_Validation**     | Master lists and validation rules                    |
| **03_Clean_Data**          | Validation flags, standardized fields, record status |
| **04_Data_Quality_Checks** | Summary metrics for data quality                     |
| **05_Pivot_Analysis**      | Analytical pivot tables                              |
| **06_Executive_Summary**   | One-page leadership reporting view                   |
| **07_Data_Quality_Log**    | Logged data issues, impact, and resolutions          |
| **08_Dashboard**           | Interactive Excel dashboard with slicers             |

---

## 🧪 Data Validation & Quality Controls

Validation rules were applied using centralized control tables:

* **Region validation**
* **Quarter validation**
* **Response value range (1–5)**
* **Record-level status flag (Clean / Issue)**

Raw data was **never overwritten**.
All issues were **flagged, measured, and documented**.

---

## 📝 Data Quality Logging

A dedicated **Data Quality Log** was created to track:

* Issue type
* Affected quarter
* Business impact
* Resolution actions

This ensures **traceability, transparency, and audit readiness**.

---

## 📈 Analysis Performed

Analysis was conducted **only on validated (Clean) records**, including:

* Average response score by region
* Compliance risk distribution (High vs Low Risk)
* Quarter-wise response trends (single-year dataset)

---

## 📊 Executive Summary & Dashboard

### Executive Summary

* Key KPIs at the top
* Clear regional and risk visuals
* Explicit data quality disclosure

### Dashboard

* Interactive slicers (Region, Quarter)
* Limited visuals for clarity (3 charts max)
* KPI-driven design

---

## 🔑 Key Metrics Included

* Total survey responses
* Average response score
* % High-risk responses
* % data quality issues identified

---

## 🛠️ Tools & Skills Used

* Microsoft Excel
* Data validation & control tables
* Pivot tables & pivot charts
* KPI design
* Dashboard design
* Data quality management
* Business reporting & documentation

---

## 🎯 Key Learnings

* Importance of preserving raw data
* Value of explicit data quality reporting
* How to design leadership-friendly dashboards
* Applying real-world analytics governance practices

---

## 🚀 Future Enhancements

* Multi-year data for YoY trend analysis
* Power BI version of the dashboard
* Automated ingestion using SQL
* Advanced data standardization mappings

---

## 📌 Author

**Lakshmi Lahari**
Aspiring Data Analyst | Excel • SQL • Power BI • Data Quality & Reporting

---
