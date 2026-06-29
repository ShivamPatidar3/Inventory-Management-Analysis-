# 📦 Inventory and Supply Chain Management Analysis

A Power BI dashboard for end-to-end visibility into inventory performance, supply chain efficiency, and regional distribution metrics.

---

## 📊 Dashboard Overview

This report provides a single-page, interactive view of key supply chain KPIs across product categories (Accessories, Clothing, Electronics, Furniture) and regions (East, North, South, West).

![Dashboard Preview](Inventory%20Management/dashboard%20img.png)

**File:** `Inventory and supply chain management.pbix`  
**Tool:** Microsoft Power BI Desktop  
**Pages:** 1


**File:** `Inventory and supply chain management.pbix`  
**Tool:** Microsoft Power BI Desktop  
**Pages:** 1
**File:** `Inventory and supply chain management.pbix`
**Tool:** Microsoft Power BI Desktop
**Pages:** 1

---

## 📌 Key Metrics (KPI Cards)

| Metric | Value |
|---|---|
| Warehouse Utilization | 34.08% |
| Days to Sale Inventory | 15.56 days |
| Inventory Turnover Ratio | 23.47 |

---

## 📈 Visuals Included

### 1. Warehouse Utilization (Gauge)
- Displays current utilization (34.08) on a scale of 0–100
- Helps identify over/under-utilization of storage capacity

### 2. Sum of Transportation Cost by Region and Category (Clustered Bar Chart)
- Breaks down transportation spend across North, West, East, and South regions
- Segmented by Accessories and Clothing categories
- Cost shown in ₹ (Indian Rupees)

### 3. Sum of Units Sold by Year (Area Chart)
- Tracks yearly sales volume trends from 2020 to 2024
- Y-axis scaled from 0K to 200K units

### 4. Average of Lead Time (Days) by Category (Donut Chart)
- Compares average supplier/fulfillment lead times across four categories:
  - Electronics: 16.60 days (26.32%)
  - Accessories: 15.29 days (24.25%)
  - Furniture: 15.68 days (24.86%)
  - Clothing: 15.50 days (24.57%)

### 5. Count of Backorder by Order Status (Bar Chart)
- Shows backorder count split by:
  - Fulfilled: 838
  - Pending: 248
  - Cancelled: 114

### 6. Sum of Inventory Level by Category and Region (100% Stacked Bar Chart)
- Visualizes proportional inventory share per region (East, North, South, West)
- Categories: Clothing, Electronics, Furniture, Accessories

---

## 🗂 Filters

### Region Slicer
Allows filtering all visuals by one or more regions:
- East
- North
- South
- West

---

## 🛠 How to Use

1. Open the `.pbix` file in **Power BI Desktop** (version recommended: latest stable)
2. Connect or refresh your data source if prompted
3. Use the **Region slicer** on the left to filter by geography
4. Hover over any chart for detailed tooltips
5. Click a bar/slice to cross-filter other visuals on the page

---

## 📁 Data Model

The report is built on a dataset that includes the following inferred fields:

| Field | Description |
|---|---|
| Category | Product category (Accessories, Clothing, Electronics, Furniture) |
| Region | Geographic region (East, North, South, West) |
| Transportation Cost | Cost of shipping per order/category |
| Units Sold | Number of units sold per period |
| Lead Time (Days) | Time from order to delivery |
| Order Status | Fulfilled / Pending / Cancelled |
| Inventory Level | Stock on hand per category/region |
| Year | Year dimension for trend analysis |

---

## 📋 Requirements

- Microsoft Power BI Desktop (free download from [powerbi.microsoft.com](https://powerbi.microsoft.com))
- Access to the underlying data source (Excel / SQL Server / CSV / etc.)

---

## 👤 Author

**Mr. Shivam Patidar**

**MANIT BHOPAL(CSE)**

---

## 📝 Notes

- Currency values are in Indian Rupees (₹)
- All metrics are calculated using DAX measures
- The dashboard is designed for a single-page executive summary view
