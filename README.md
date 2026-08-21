# 📊 Sales Operations Analytics: Interview-Grade Excel Assessment

![Excel Project Banner](https://img.shields.io/badge/Excel-Sales%20Operations%20Analytics-green?style=for-the-badge&logo=microsoft-excel)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![Marks](https://img.shields.io/badge/Score-100%25-blue?style=for-the-badge)

A comprehensive, real-world data analytics assessment simulating a role on the analytics team of a fast-growing multi-category retailer operating across 6 Indian cities. This project tackles messy raw data, complex business requirements, and advanced reporting scenarios to evaluate technical Excel proficiency.

---

## 🎯 The Scenario

As a newly joined data analyst, the head of sales provided **5 raw data files** to answer 30 critical business questions ahead of a leadership review. The data is intentionally messy—containing duplicates, missing references, inconsistent casing, invalid records, and discontinued SKUs—requiring robust data cleaning and diagnostic strategies.

---

## 📂 Dataset Overview

The project leverages a multi-sheet workbook containing operational data:

| Sheet Name | Approximate Rows | Key Columns / Fields | Description / Relationships |
| :--- | :--- | :--- | :--- |
| **Orders** | ~2,000 | `order_id`, `order_date`, `customer_id`, `product_id`, `sales_rep_id`, `quantity`, `unit_price`, `discount_pct`, `final_amount`, `payment_status`, `ship_city` | Central transaction log linking all entities. |
| **Customers** | 300 | `customer_id` (PK), `customer_name`, `age`, `city`, `segment`, `signup_date` | Customer demographic records. |
| **Products** | 60 | `product_id` (PK), `product_name`, `category`, `unit_cost`, `unit_price`, `is_active` | Catalog information including active/discontinued SKUs. |
| **Sales_Reps** | 30 | `rep_id` (PK), `rep_name`, `region`, `hire_date`, `team_lead_id` | Sales team hierarchy and regional mappings. |
| **Targets** | 30 × 12 | `rep_id` (PK), Jan-24 through Dec-24 monthly targets | Monthly sales performance goals per representative. |

---

## 🏗️ Assessment Structure & Marks Distribution

The challenge is split into 5 core sections covering 30 questions (100 Marks total):

* **Q1: Lookup Functions (25 Marks)** — Mastered `VLOOKUP`, `INDEX-MATCH`, and chained multi-level lookups.
* **Q2: Data Cleaning & Diagnostics (20 Marks)** — Handled data quality issues, anomalies, and dirty text values.
* **Q3: Conditional Aggregation (25 Marks)** — Built logic using `SUMIFS`, `COUNTIFS`, and nested `IF` statements.
* **Q4: Pivot Tables (20 Marks)** — Designed 2D pivots, percentage-of-total calculations, and calculated fields.
* **Q5: Advanced Analysis (10 Marks)** — Handled dynamic ranking, running totals, and multi-condition metrics.

---

## 🚀 Key Technical Takeaways

* **Dynamic Recalculation:** Prioritized flexible formulas over hardcoded inputs so sheets update automatically if source data changes.
* **Data Hygiene Practices:** Implemented rigorous validation checks to isolate null references, duplicate entries, and outliers before analysis.
* **Executive-Ready Reporting:** Structured final metrics cleanly into designated answer grids optimized for stakeholder review.

---

## 🛠️ How to Use This Repository

1. Clone the repository: `git clone https://github.com/your-username/excel-sales-operations-analytics.git`
2. Open `Excel_Minor_Project.xlsx` in Microsoft Excel or Google Sheets.
3. Review the `README` sheet for prompt instructions and navigate through the structured tabs (`Q1_Lookups` to `Q5_Advanced`).
