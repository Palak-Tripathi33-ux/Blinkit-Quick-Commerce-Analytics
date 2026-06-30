# 🛒 Blinkit Grocery Sales & Performance Analytics (Power BI Dashboard)

## Project Overview

This repository contains a comprehensive data analytics project that evaluates sales performance, customer preferences, and outlet metrics for **Blinkit**.

Utilizing an end-to-end Power BI pipeline, this project transforms over **8,500+** raw operational transaction records into an interactive executive-level tracking dashboard.

The analysis evaluates key commercial variables — including product category performance, store-size margins, item fat content trends, and geographic revenue distributions — bridging business administration strategy with modern business intelligence (BI).

---

## Dashboard Preview

![Blinkit Sales Analytics Dashboard](images/dashboard.jpeg)

---

## Business Objective

The primary business objective is to diagnose channel-wide sales trends to identify efficiency opportunities, optimize inventory distribution, and improve fulfillment channels. Specifically, the analysis aims to:

* Evaluate top-line performance metrics across gross sales, transaction volumes, and average customer cart values.

* Assess the commercial impact of product characteristics (e.g., Fat Content) and consumer fulfillment rates.

* Pinpoint how physical retail attributes — such as outlet tier size, geographic location, and establishment age — directly influence store profitability.

---

## Technical Stack & Tools Used

* **Business Intelligence Platform:** Microsoft Power BI Desktop

* **Data Engineering & ETL:** Power Query (data cleaning, type casting, text normalization)

* **Analytical Calculations:** DAX (Data Analysis Expressions) for explicit dynamic time-intelligence measures

* **UI/UX Design & Structure:** Custom theme layout, card structuring, visual grid alignment

---

## Dashboard Features & Architecture

The single-page diagnostic dashboard delivers dynamic, real-time filtering and analysis through:

* **Interactive Global Slicers:** Instant, dashboard-wide filtration across Outlet Location Tier, Outlet Size, and Item Type.

* **Core KPI Metric Matrix:** High-level summary cards displaying Total Sales, Average Sales per transaction, Total Items Sold, and Average Customer Rating.

* **Demographic & Product Segmentation:** Visual matrices cross-referencing health preferences (Low Fat vs. Regular) against category volumes.

* **Structural Store Benchmarking:** Comparative charts mapping sales velocity across establishment years, tiers, and footprint size.

---

## Key Analytical Insights

### 1. Top-Line Commercial Health

* **Gross Revenue:** Generated total revenue of **$1.20M** across all listed operations.

* **Transaction Volume:** Processed a total of **8,523** independent line items.

* **Customer Ticket Size:** Maintained an Average Sales value of **$141** per transaction.

* **Consumer Satisfaction:** Sustained a consistent baseline customer rating of **3.9 / 5.0** across all fulfillment categories.

---

### 2. Product Profile & Material Dynamics

* **Health Preference Velocity:** Low-fat inventory variants remain the primary volume driver, generating **$776.3K** in total sales, compared to **$425.4K** for regular items.

* **Category Revenue Leaders:** **Fruits and Vegetables ($178K)** and **Snack Foods ($178K)** operate as the store's primary revenue anchors, followed closely by **Household ($136K)** and **Frozen Foods ($122K)**. Minor categories like **Seafood ($10K)** represent niche market segments.

---

### 3. Footprint & Regional Store Benchmarking

* **Geographic Matrix Dominance:** **Tier 3** locations emerge as the highest revenue engine, commanding **$472.1K** of aggregate sales, followed by **Tier 2** at **$393.2K**, and **Tier 1** at **$336.4K**.

* **Footprint Efficiency:** Medium-sized outlets operate with superior capital efficiency, capturing **$507.9K** in sales. Small-format stores outperform large footprints (**$444.8K vs. $249.0K**), highlighting an optimization gap in larger physical spaces.

* **Establishment Trend:** Outlets opened in **2018** mark a clear performance peak, reaching roughly **$205K** in sales, while other establishment years sit in a more typical **$78K–$133K** range.

---

## Challenges Faced & Technical Resolutions

### 1. Granular Label Overlap in High-Density Categories

* **The Challenge:** Plotting revenue metrics across **16** independent item types in standard vertical bar charts resulted in truncated strings, messy axes, and poor visual readability.

* **Resolution:** Re-architected the layout by swapping vertical bars for a horizontal bar chart, sorted in descending order. This restored label clarity and enabled clean execution for executive review.

### 2. Normalizing Inconsistent Categorical Dimensions

* **The Challenge:** The raw dataset contained duplicate values caused by variant string casing (e.g., "Low Fat," "low fat," and "LF" representing the same metric).

* **Resolution:** Used the Power Query transformation editor to perform text sanitization, standardizing inputs into uniform categories ("Low Fat" or "Regular") to prevent broken data counts.

---

## Learning Outcomes & Personal Contributions

### My Efforts and Contributions

* Handled the entire business intelligence process: from raw data ingestion, structural validation, and schema design, to metric calculation and layout architecture.

* Structured custom DAX expressions to compute core sales cards independently, avoiding reliance on implicit default aggregations.

* Designed the layout grid, intentionally balancing visual hierarchy by grouping top-line summaries at the upper focal points and granular outlet breakdowns along the base.

### Competencies & Gained Skills

* **ETL & Data Modeling:** Developed practical data cleaning skills in Power Query, handling data type adjustments and optimizing table structures.

* **DAX Formulas:** Gained confidence applying calculation expressions to build scalable business metrics.

* **UI/UX Data Layouts:** Mastered dashboard layout standards, learning to use space, clear alignment, and cohesive colors to convey insights at a glance.

* **Strategic Translation:** Developed the ability to map raw operational figures back to practical retail choices, such as adjusting stock models based on store-size metrics.

---

## Skills Demonstrated

`Business Intelligence (BI)` • `Data Modeling & ETL` • `DAX Calculation` • `Retail & Revenue Analytics` • `Dashboard UI/UX Design` • `Market Segmentation` • `Commercial Problem Solving`

---

## Conclusion

This performance analysis demonstrates that Blinkit's most efficient growth vector lies in expanding **Medium-sized, Tier 3** retail footprints, while focusing inventory planning heavily on **Low-Fat** variant profiles within the **Fruits, Vegetables, and Snack Food** classes.

As an aspiring Data Analyst with a business background, this portfolio project shows my ability to use specialized BI frameworks to extract practical commercial insights and support executive planning.

---

**Project Developed By:** Palak Tripathi | BBA Student | Aspiring Data & Business Analyst

🤝 **Let's Connect:** Always open to discussing business analytics models and collaborative data projects — feel free to reach out via [LinkedIn](https://www.linkedin.com/in/palak-tripathi-37a56234a/)!
