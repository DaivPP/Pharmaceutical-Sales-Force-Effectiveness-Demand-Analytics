# Pharmaceutical Sales Force Effectiveness & Demand Analytics

## Overview

This project is a healthcare commercial analytics and business intelligence solution designed to analyze global pharmaceutical sales trends from 2020–2025. The objective of the project is to identify high-growth regions, product demand patterns, inventory risks, and operational insights that can support strategic decision-making for pharmaceutical businesses.

The project combines:

* Python-based data analytics
* KPI engineering
* Strategic segmentation
* Operational risk analysis
* Interactive Power BI dashboards

The analytics workflow was designed to simulate real-world pharmaceutical commercial analytics and consulting-style reporting.

---

# Business Problem

Pharmaceutical organizations operate in highly dynamic markets influenced by:

* seasonal demand fluctuations
* pandemic-driven demand spikes
* inventory pressure
* product volatility
* regional growth differences

The objective of this project is to:

* identify high-performing regions
* evaluate pharmaceutical demand trends
* analyze product-level revenue contribution
* monitor operational inventory risks
* support data-driven commercial strategy decisions

---

# Dataset Description

## Dataset

Global Pharmacy Sales Dataset (2020–2025)

## Dataset Characteristics

* ~178,000 sales records
* Multi-region pharmaceutical sales coverage
* Product category segmentation
* Inventory and expiry-related operational metrics
* COVID-period demand indicators
* Time-series sales trends

## Key Features

| Feature               | Description               |
| --------------------- | ------------------------- |
| date                  | Transaction date          |
| region                | Global sales region       |
| country               | Country name              |
| category              | Pharmaceutical category   |
| medicine              | Product/medicine name     |
| age_group             | Customer age segment      |
| units_sold            | Quantity sold             |
| unit_price            | Product price             |
| stock_level           | Inventory stock level     |
| expiry_days_remaining | Remaining expiry duration |
| covid_flag            | COVID-period indicator    |

---

# Project Workflow

## 1. Data Understanding & Cleaning

* Data inspection
* Duplicate removal
* Data type validation
* Revenue feature engineering

## 2. Exploratory Data Analysis (EDA)

* Revenue trend analysis
* Regional performance analysis
* Category contribution analysis
* COVID impact analysis
* Age-group demand analysis

## 3. Advanced Business Analytics

* Revenue growth analysis
* Demand volatility analysis
* Regional performance scoring
* Strategic segmentation
* KPI engineering

## 4. Dashboard Development

* Executive dashboard
* Regional analytics dashboard
* Product strategy dashboard
* Operational risk dashboard

---

# Key Analytics Performed

## Revenue Analytics

* Total revenue analysis
* Revenue contribution by region
* Revenue contribution by category
* Top-performing medicines

## Growth Analytics

* Regional growth trend analysis
* Post-pandemic demand normalization analysis
* Strategic territory performance evaluation

## Product & Category Strategy

* Product demand volatility analysis
* Strategic product segmentation
* Revenue vs volatility analysis
* Product prioritization insights

## Operational Risk Analytics

* Inventory stock analysis
* Expiry risk monitoring
* COVID operational impact analysis
* Inventory risk matrix development

---

# Dashboard Pages

## 1. Executive Overview

Features:

* Revenue KPIs
* Monthly revenue trends
* Regional revenue contribution
* Product category analysis
* Executive business insights

## 2. Regional Performance Analytics

Features:

* Regional growth trends
* Performance index ranking
* Strategic region segmentation
* Revenue share analysis
* Commercial prioritization insights

## 3. Product & Category Strategy

Features:

* Product category revenue analysis
* Demand volatility analytics
* Top medicines analysis
* Strategic product matrix
* Product strategy recommendations

## 4. Inventory & Operational Risk Analytics

Features:

* Stock level analysis
* Expiry risk analysis
* COVID demand impact
* Inventory risk matrix
* Operational optimization insights

---

# Key Business Insights

* Pharmaceutical demand experienced significant acceleration during the COVID-19 period (2020–2021).
* Demand normalization became visible beginning in 2022 across most global regions.
* Antipyretic and cough/cold medicines generated the highest commercial contribution.
* Vitamin-related products demonstrated the highest demand volatility.
* Older age groups represented major pharmaceutical demand contributors.
* Regional performance variability highlighted the importance of adaptive commercial strategies.
* Inventory lifecycle monitoring is critical for minimizing operational risk exposure.

---

# Technologies Used

## Programming & Analytics

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Business Intelligence

* Power BI

## Data Processing

* CSV
* Jupyter Notebook

---

# Project Structure

```text
Pharma-Sales-Effectiveness-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_business_analytics_and_kpis.ipynb
│   ├── 04_segmentation_and_strategy.ipynb
│   └── 05_executive_dashboard_prep.ipynb
│
├── dashboard/
│   ├── pharma_sales_analytics_dashboard.pbix
│   └── csv_exports/
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

# Dashboard Screenshots

## Executive Overview

<img width="1418" height="797" alt="executive_dashboard" src="https://github.com/user-attachments/assets/6abbc1c4-d37b-432c-88f8-bbe1a48bfb2e" />

## Regional Performance Analytics

<img width="1421" height="795" alt="regional_analytics" src="https://github.com/user-attachments/assets/240945bc-7958-4da9-94ed-dd6b4e82ddfa" />


## Product & Category Strategy

<img width="1413" height="792" alt="product_strategy" src="https://github.com/user-attachments/assets/f1ab8be1-3c36-458d-b530-b5bda3ddad4b" />

## Inventory & Operational Risk Analytics

<img width="1423" height="792" alt="operational_risk" src="https://github.com/user-attachments/assets/cf4737ba-f9a2-454e-a57b-30d85378d8a6" />


---

# Strategic Recommendations

## Commercial Strategy

* Prioritize high-growth regions for increased commercial investment.
* Maintain long-term focus on stable high-revenue regions.

## Product Strategy

* High-volatility medicine categories require adaptive forecasting and inventory strategies.
* Stable high-revenue categories should receive sustained commercial focus.

## Operational Strategy

* Improve inventory lifecycle monitoring to reduce expiry-related risks.
* Strengthen operational planning for demand spikes during healthcare emergencies.

---

# Future Improvements

Potential future enhancements include:

* Time-series forecasting using Prophet/LSTM models
* Demand anomaly detection
* Advanced customer segmentation
* Interactive deployment using Streamlit
* SQL-based backend integration
* Real-time dashboard pipelines

---

# Conclusion

This project demonstrates how healthcare commercial analytics can be used to transform pharmaceutical sales data into actionable strategic insights.

The solution combines:

* business intelligence
* data analytics
* operational monitoring
* strategic segmentation
* interactive dashboard storytelling

to support data-driven pharmaceutical decision-making.
