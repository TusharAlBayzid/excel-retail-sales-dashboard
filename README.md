# 📊 Retail Performance & Interactive Analytics Dashboard

An end-to-end data analytics and interactive dashboard solution created using **Microsoft Excel**. This project consolidates, cleans, and analyzes multi-retailer dataset metrics (Costco, Target, Walgreens, and Walmart) to derive actionable business insights through interactive data visualization.

---

## 🌐 Project Overview & Objectives

The goal of this assignment is to transform disparate datasets from multiple retail partners into a unified analytics hub. By leveraging **Pivot Tables**, **Pivot Charts**, and **Dynamic Slicers**, this dashboard enables stakeholders to compare regional performance, sales distribution, and brand popularity effortlessly.

---

## 🛠️ Tech Stack & Key Tools Used

* **Tool:** Microsoft Excel
* **Features:**
  * Multi-sheet Data Consolidation
  * Data Hygiene & Cleaning (Duplicate removal, Data Types & Formatting)
  * Advanced Pivot Tables (Aggregation & Grouping)
  * Interactive Slicers & Dynamic Report Connections
  * Modern Dashboard Layout & UX Design

---

## 🔄 Project Workflow & Implementation

### Step 1: Data Consolidation & Master Integration
* Merged four individual Excel files (`Costco`, `Target`, `Walgreens`, and `Walmart`) into a single structured workbook.
* Created a consolidated **`Master_Data`** sheet storing the complete transactional dataset with a unified header schema.

### Step 2: Data Cleaning & Preprocessing
* **Duplicate Elimination:** Executed deduplication routines to ensure data accuracy.
* **Standardization:** Formatted `Order Date` and `Payment Date` into uniform `Short Date` formats.
* **Currency Alignment:** Configured `Price per Unit` into currency `$ (USD)` for accurate valuation.

### Step 3: Analytical Modeling via Pivot Tables
Built four targeted **Pivot Tables** on the `Pivot_Tables` sheet to evaluate specific business KPIs:
1. **Sales Performance by Retailer:** Evaluated total volume sold per retail partner.
2. **Regional Distribution Analysis:** Grouped sales data by region and state to identify key growth areas.
3. **Beverage Brand Popularity:** Measured product performance across leading beverage brands.
4. **Time-Series Sales Trend:** Grouped order dates monthly/quarterly to analyze sales trajectory over time.

### Step 4: Interactive Dashboard & UI Design
* Built a clean, grid-less **`Dashboard`** tab.
* Converted analytical tables into interactive **Pivot Charts** (Bar/Column, Line, Donut charts).
* Implemented interactive **Slicers** connected across all Pivot Tables to enable one-click real-time data filtering by Retailer, Region, and Date range.

---

## 🚀 Key Insights Uncovered

* **Top Performing Retailer:** Identified primary revenue-generating retail chains based on unit sales volume.
* **Geographic Trends:** Highlighted high-performing regions to optimize distribution strategies.
* **Product Insights:** Mapped customer preference trends across beverage brands to support inventory management.

---

## 📁 Repository Structure

```text
├── Final_Retailer_Dashboard.xlsx   # Main Excel File (Master Data, Pivot Tables, Dashboard)
├── Screenshots/                    # Dashboard preview images
└── README.md                       # Documentation
