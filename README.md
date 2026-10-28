# 📊 Bank of Punjab (BOP) - Service Quality & Operational Analytics Dashboard

An end-to-end executive Power BI dashboard designed to unify multi-source operational streams, monitor branch service quality, track call audit performance, and evaluate compliance metrics across **330+ bank branches**.

---

## 🖼️ Dashboard Preview

![Main Analytics Dashboard](Main_Analytics.png)
![QA Audit Analytics Dashboard](QA_Audit_Analytics.png)
![Floor Management Dashboard](Floor_Management.png)

---

## 🚀 Project Overview

Managing retail branch performance requires tracking multiple independent operational datasets. This project consolidates four core operational pillars into a single, high-level executive master suite:

1. **Main Analytics (MTD Executive View):** High-level summary displaying overall MTD QA Audit %, Call Audit %, Within TAT, Beyond TAT, Total Complaints, and Floor Compliance %.
2. **QA Audit Analytics:** Granular evaluation of physical branch visits, SQA officer performance, MTD grades (Excellent to Poor), top/bottom performing branches, and regional score trends.
3. **Floor Management:** Detailed tracking of branch-wise compliance rankings, risk level gauges, non-compliance observations, and audit distribution by register status.
4. **Call Audit & Complaints:** Centralized customer contact quality and grievance tracking across Conventional, TAQWA, and KHAAS banking segments.

---

## 🛠️ Key Technical Features & Architecture

* **Data Modeling & Relationships:** Built clean 1-to-Many relationships and master mapping tables across multi-source operational tables (`Master_QA_Data`, `Master Call Audit`, `Master_Floor_Management`, and `Master_Complaints`) to resolve Many-to-Many bottlenecks.
* **Segment & Timeline Slicers:** Dynamic interactive controls allowing bank executives to instantly cross-filter all visuals by business segments (**Conventional vs. TAQWA**) and specific reporting months.
* **Advanced DAX Calculations:** Developed custom DAX measures to compute Month-to-Date (MTD) quality averages, variance scores, actual percentage distributions, and compliance rates.
* **Data Cleansing & ETL (Power Query):** Streamlined data ingestion pipelines in Power Query to remove million-row blank data overhead, optimizing report load speeds and responsiveness.

---

## 📈 Executive Visualizations Included

* **Top Executive KPI Bar:** Instant visibility into core metrics including MTD QA Audit %, Call Audit %, TAT compliance rates, total complaints, and overall floor compliance %.
* **Risk Level & MTD Gauges:** Semicircular gauge visual displays tracking non-compliance risk levels and quality target thresholds.
* **Regional & Branch Leaderboards:** Ranked horizontal bar charts and structured matrix tables highlighting top-performing regions and branch compliance rankings.
* **Breakdown & Trend Analysis:** Donut charts, tree maps, and monthly trend lines illustrating segment distribution (Conventional vs. TAQWA) and SQA officer audit volumes.

---

## 🧰 Tech Stack & Tools

* **BI Tool:** Power BI Desktop (`.pbix`)
* **Data Transformation:** Power Query, Excel ETL
* **Data Modeling:** Star Schema Design, DAX (Data Analysis Expressions)
* **Domain:** Banking Operations, Service Quality Analytics
