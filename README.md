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
Take a deep breath! It is completely fine. When dealing with GitHub, folder structures, and documentation all at once, things can get overwhelming fast. Let's hit the reset button and take this **one tiny, stress-free step at a time**.

We are absolutely going to include those growth-oriented business insights because that is exactly what turns a standard dashboard into a high-value data analytics portfolio.

Here is your exact, step-by-step checklist. Don't look at the whole list at once—just do **Step 1** right now.

---

## 🛠️ Step 1: Create a Brand New GitHub Repository

1. Open your browser and go to **GitHub.com**.
2. Click the green **"New"** button on the left (or the **`+`** icon in the top right corner and select **New repository**).
3. **Repository Name:** Type `blinkit-sales-intelligence` (keep it all lowercase with dashes).
4. **Description:** Copy and paste this short sentence: *An enterprise-grade Power BI dashboard analyzing $1.2M in grocery sales data to optimize channel performance and product visibility.*
5. **Public/Private:** Keep it **Public** so interviewers can see it.
6. **Initialize this repository with:** Check the box that says **"Add a README file"**.
7. Scroll to the bottom and click the green **"Create repository"** button.

---

## 📂 Step 2: Create Your Folders and Upload Your Files

Now that your repository exists on GitHub, let’s organize your files beautifully.

### Uploading your Excel Data:

1. At the top right of your repository page, click **Add file** ➡️ **Create new file**.
2. In the file name box, type: `data-raw/placeholder.txt` *(GitHub won't let you create an empty folder, so creating a dummy file inside it automatically builds the folder!)*.
3. Scroll to the bottom and click **Commit changes**.
4. Now, click on the **`data-raw`** folder you just created.
5. Click **Add file** ➡️ **Upload files**.
6. Drag and drop your **`BlinkIT Grocery Data (1).xlsx`** file right there.
7. Scroll down and click the green **Commit changes** button.

### Uploading your Power BI Dashboard:

1. Go back to your main repository page (click the repository name at the top left).
2. Click **Add file** ➡️ **Create new file**.
3. In the file name box, type: `dashboards/placeholder.txt` and click **Commit changes**.
4. Click on your new **`dashboards`** folder.
5. Click **Add file** ➡️ **Upload files**.
6. Drag and drop your finished **`.pbix`** Power BI file here.
7. Scroll down and click **Commit changes**.

---

## 📝 Step 3: Update Your README File

This is your final step. We are going to fill your main page with the exact requirements from your screenshots, real calculated metrics, and corporate growth strategies.

1. Go back to your main repository page.
2. Look for the **`README.md`** file listed in the center and click on it.
3. Click the **pencil icon (Edit this file)** in the top right corner of the file box.
4. **Select everything inside the file, delete it, and paste this exact block below:**

```markdown
# Blinkit Sales & Channel Performance Intelligence Dashboard 🛒📊

## 🏢 1. Business Case & Core Objectives
This repository contains an end-to-end data analytics project simulating a corporate assignment for **Blinkit**. The goal is to conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution to identify key operational insights and concrete opportunities for business growth.

### 🎯 Key Performance Indicators (KPIs) Met:
1. **Total Sales:** Tracks overall revenue generated from all items sold across the network.
2. **Average Sales:** Measures pricing efficiency and average revenue generated per transaction.
3. **Number of Items:** Monitors total volume and variety of stock-keeping units (SKUs) moving through fulfillment centers.
4. **Average Rating:** Measures customer satisfaction and service delivery health.

---

## 📁 2. Project Architecture
To maintain professional data engineering practices, the repository is organized cleanly into operational data layers and delivery dashboards:

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

---

## 🔧 3. Data Transformation & ETL Pipeline (Power Query)

Rather than executing manual edits in Excel, a scalable, fully automated ETL pipeline was built directly inside **Power BI's Power Query Editor**. This guarantees that as new weekly transaction batches drop into the `data-raw` folder, the data cleans itself automatically.

### 🛠️ Key Cleaning Tasks Executed:

* **Master Data Harmonization:** Resolved severe text inconsistencies in the `Item Fat Content` field. Fragmented entries (`low fat`, `LF`, and `reg`) were mapped and standardized into two clean corporate categories: **`Low Fat`** and **`Regular`**.
* **Data Schema Enforcement:** Audited missing values in structural dimensions like `Outlet Size` and locked down explicit data types (Currency, Decimal, Text) to ensure fast rendering speeds and zero summary metric skew.

---

## 📊 4. Real Metrics & Executive Insights

By connecting the visuals to our cleaned data tables, the following exact metrics and operational trends were uncovered:

### 📈 Master Business Baseline

* **Total Gross Revenue:** `$1,201,681.49` ($1.20M)
* **Average Transaction Size:** `$140.99`
* **Total Inventory Breadth:** `8,523 items`
* **Network Customer Rating:** `3.97 out of 5.00`

### 🏪 Channel Metrics (Sales by Outlet Type)

* **Supermarket Type 1:** `$787,549.89` *(Core revenue driver)*
* **Grocery Store:** `$151,939.15`
* **Supermarket Type 2:** `$131,477.78`
* **Supermarket Type 3:** `$130,714.67`

---

## 💡 5. Strategic Growth Recommendations for Blinkit Leadership

Based on the dashboard analytics, the following strategic actions are recommended to accelerate growth and optimize efficiency:

* **Aggressively Double-Down on Low-Fat Inventory:** Cleaned data reveals that **Low-Fat items generated `$776.31K**` in sales compared to only `$425.36K` from Regular options. Blinkit should expand partnerships with health-conscious brands and increase dark-store warehouse floor allocations for Low-Fat items by 15-20% to meet clear consumer demand.
* **Standardize on the 'Supermarket Type 1' Footprint:** Supermarket Type 1 formats generate over **65% of the total network revenue** ($787.5K). Legacy grocery store setups are significantly less efficient. Future capital investment (CapEx) should be strictly allocated to establishing new localized urban dark-stores modeled after the Type 1 structure.
* **Leverage High-Volume Categories for Cross-Selling:** *Fruits & Vegetables* and *Snack Foods* are the highest revenue pillars, pulling in over $175K each. Blinkit's app algorithm should cross-merchandise lower-volume, high-margin categories (like *Health & Hygiene* or *Canned Goods*) directly on the checkout pages of these high-traffic product blocks to increase the average order value beyond the current $140.99 baseline.

---

## 🚀 6. How to Run and Interact With This Project

1. Clone or download this repository locally.
2. Open the file inside `/data-raw` to inspect the underlying table schemas.
3. Open the file inside `/dashboards` using **Power BI Desktop** to view the live models, use interactive slicers (Fat content, Outlet Size, Geography), and examine the backend Power Query cleaning steps.
4. Once you paste it, scroll down to the bottom of the page and click the green **"Commit changes"** button.

### That's it! 
Take it one step at a time. Let me know if you hit a problem on any of these specific steps, and we can sort it out instantly!

```
