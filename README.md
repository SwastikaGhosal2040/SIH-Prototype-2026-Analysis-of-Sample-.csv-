# SIH Prototype 2026 — Analysis of Sample Dataset

## Sentinel — Operational Readiness Analytics

This repository contains the **data analysis and dashboard prototype** developed as part of the Sentinel project for **Smart India Hackathon (SIH) 2026**.

The objective of this prototype is to analyze personnel information and physiological parameters and present meaningful operational insights through an interactive **Looker Studio dashboard**.

The current version uses a sample CSV dataset to demonstrate the analytics layer of the proposed Sentinel system.

---

## 📌 Project Overview

**Sentinel** is envisioned as an intelligent operational readiness and welfare monitoring system.

The system focuses on analyzing personnel and physiological information such as:

- Heart Rate
- Heart Rate Variability (HRV)
- Galvanic Skin Response (GSR)
- Blood Oxygen Saturation (SpO₂)
- Skin Temperature
- Personnel Status
- Unit
- Platoon

The current repository represents the **prototype analytics stage** of the project.

The dashboard transforms the raw sample data into interactive visualizations that can help identify:

- Personnel distribution
- Operational status
- Unit-wise physiological patterns
- Platoon-wise HRV variations
- Physiological averages
- Relationships between biometric parameters

---

# 📊 Dashboard

The project currently contains **two dashboard pages** developed using **Google Looker Studio**.

## Page 1 — Operational Overview

The first page provides a high-level overview of personnel and operational distribution.

### Key Performance Indicators

- **Total Personnel**
- **Active Personnel**
- **Deployed Personnel**
- **Medical Status**
- **Average Heart Rate**
- **Average SpO₂**

### Visualizations

- Personnel by Unit
- Personnel Status
- Average Heart Rate by Unit
- Average HRV by Unit
- SpO₂ by Unit
- Personnel Distribution

### Filters

The dashboard can be filtered using:

- **Unit**
- **Status**
- **Platoon**

---

## Page 2 — Physiological Analytics

The second page focuses on deeper physiological analysis.

### Key Performance Indicators

- **Average Heart Rate**
- **Average HRV**
- **Average GSR**
- **Average Skin Temperature**
- **Average SpO₂**

### Visualizations

- HRV by Unit
- HRV Heatmap
- Unit-Wise Physiology Summary
- Heart Rate vs HRV

### Physiological Analysis

The dashboard compares physiological measurements across different units and platoons.

The **HRV Heatmap** uses:

- Rows → Unit
- Columns → Platoon
- Metric → Average HRV

The **Unit-Wise Physiology** table summarizes:

- Heart Rate
- HRV
- GSR
- SpO₂
- Skin Temperature

for each unit.

---

# 📁 Repository Structure

```text
SIH-Prototype-2026-Analysis-of-Sample-.csv-
│
├── Dashboard_Images/
│   ├── Page_1_Operational_Overview
│   └── Page_2_Physiological_Analytics
│
├── DataStudio_work_link/
│   └── Looker Studio dashboard link/reference
│
├── Sample Dataset/
│   └── sample_data.csv
│
└── README.md
