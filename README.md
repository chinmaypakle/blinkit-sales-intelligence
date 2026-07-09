# Blinkit Sales & Channel Performance Intelligence Dashboard.

## 1. Business Case & Core Objectives.
This repository contains an end-to-end data analytics project simulating a corporate assignment for **Blinkit**. The goal is to conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, andinventory distribution to identify key operational insights and concrete opportunities for business growth.

### Key Performance Indicators (KPIs) Met:-
1.**Total Sales:** Tracks overall revenue  generated from all item sold across the network.
2.**Average Sales:** Measure pricing efficiency and average revenue generated per transaction.
3.**Number of Items:** Monitors total volume and variety of stock-keeping units(SKUs) moving through fulillment centers.
4.**Average Rating:** MEasures customer satisfaction and servicedelivery health.
---

## 2. Project Architecture
To maintain professional data engineering practices, the reposotory is organized cleanly into data layers and delivery dashboards:

```text
blinkit-sales-intelligence/
│
├── 📂 data-raw/
│   └── BlinkIT Grocery Data (1).xlsx    <- Foundational transactional data (8,523 rows)
│
├── 📂 dashboards/
│   └── Blinkit_Project.pbix              <- Completed Interactive Power BI Application
│
└── 📄 README.md                         <- Professional Documentation (This file)

```
## 3. Data Transformation&ETL pipeline( Power Query).
Rather than executing manual edits in Excel,a scalable,fully automated ETL pipeline was built directly insaide **POwer BI's Power Query Editor**.This guarantess that as new weekly transaction batches drop into the data-raw folder,the data cleans itself automatically.

## Key cleaning tasks Executed:
1. Resolved server text inconsistencies in the **Item Fat Content** field. Fragmented enteries(low fat,LF and reg) were mapped and standardized into two clean coroprate categories: Low Fat and Regular.
2. Audited missing values in structural dimensions like **Outlet Size** and locked down explicit data types( cureency, Decimal,Text) to ensure fast rendering speeds and zero summary metric skew.

## 4.Real Metrics & Executive Insights
By connectiing the visuals to our cleaned data tables,the following exact metrics and opperational trends were uncovered:

# Master Business Baseline
**Total Gross Revenue:** $1,201,681.49 ($1.20M)
**Average Transaction Size:** $140.99
**Total invetory Breadth:** 8,523 items
**Network Customer Rating:** 3.97 out of 5.00

# Channel Metrics ( Sales by Outlet Type)
**Supermatket Type 1:** $787,549.89
**Grocery Store:** $151,939.15
**Supermarket Type 2:** $131,477.78
**Supermarket Type3:** $130,714.67

## 5.Strategic Growth Recommendations for Blinkit Leadership
Based on the dashboard analytics, the following strategic actions are recommended to accelerate growth and optimize efficiency:

***Aggressively Double-Down on Low-Fat Inventory:*** Cleaned data reveals that Low-Fat items generated $776.31K in sales compared to only $425.36K from Regular options. Blinkit should expand partnerships with health-conscious brands and increase dark-store warehouse floor allocations for Low-Fat items by 15-20% to meet clear consumer demand.

***Standardize on the 'Supermarket Type 1' Footprint:*** Supermarket Type 1 formats generate over 65% of the total network revenue ($787.5K). Legacy grocery store setups are significantly less efficient. Future capital investment (CapEx) should be strictly allocated to establishing new localized urban dark-stores modeled after the Type 1 structure.

***Leverage High-Volume Categories for Cross-Selling:*** Fruits & Vegetables and Snack Foods are the highest revenue pillars, pulling in over $175K each. Blinkit's app algorithm should cross-merchandise lower-volume, high-margin categories (like Health & Hygiene or Canned Goods) directly on the checkout pages of these high-traffic product blocks to increase the average order value beyond the current $140.99 baseline.

### 6.How to run and interact with This Project

1.Clone or download this repository locally.
2.Open the file inside '/data-raw' to inspect the underlying table schemas.
3.Open the file inside ' /dashboards ' using Power BI Desktop to view the live models, use interactive slicers (Fat content, Outlet Size, Geography), and examine the backend Power Query cleaning steps.
4.Once you paste it, scroll down to the bottom of the page and click the green **"Commit changes"** button.

---

### That's it! 
Take it one step at a time. Let me know if you hit a problem on any of these specific steps, and we can sort it out instantly!
