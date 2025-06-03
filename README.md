# 📈 Amazon Sales in India Dashboard

This **Tableau** project provides a comprehensive dashboard that visualizes  **Amazon sales data** across various states in India. The dashboard is built to offer actionable insights into **sales performance**, **trends**, and **shipping metrics** using real-world e-commerce data

---

## 📁 Repository Contents

- **Amazon Sales in India Dashboard.twb**  
  Tableau workbook file containing all dashboards, worksheets, and calculated fields.
- **Amazon Sales in India Dashboard.twb**  
  Tableau workbook file containing all dashboards, worksheets, and calculated fields.

---

## 📊 Dashboard Overview

The workbook includes multiple dashboards categorized into the following analytical areas:

### 1. 🌐 Geospatial Analysis
- **Map of Quantity by State**:  
  A choropleth map showing the quantity of items shipped across Indian states.

### 2. 📅 Temporal and Category-Based Trends
- **Bar Chart – Quantity by Week and Category**  
- **Line Chart – Amount by Week and Category**

### 3. 📦 Product-Level Analysis
- **Bar Chart – Quantity by Size and Category**  
- **Bar Chart – Top 12 States by Quantity and Category - Ship Service Level**

### 4. 🚚 Logistics and Fulfilment
- **Bar Chart – Quantity by Status and Category**  
- **Donut Chart – Quantity by Courier Status and Category**  
- **Square Chart – Quantity by Sales Channel and Category**  
- **Square Chart – B2B Sales Quantity**

---

## 🧮 Data Dictionary

### 📐 Dimensions
- `Index`, `Order ID`, `Date`, `Status`, `Fulfilment`, `Sales Channel`, `Ship-Service-Level`, `Style`, `SKU`, `Category`, `Size`, `ASIN`, `Courier Status`, `Ship-City`, `Ship-State`, `Ship-Postal-Code`, `Ship-Country`, `Promotion-Ids`, `B2B`, `Fulfilled-By`

### 📊 Measures
- `Qty`, `Currency`, `Amount`

### 🧠 Calculated Fields
- `Currency1`: Standardized currency field  
- `Total Quantity`, `Total Amount`, `Total Sizes`, `Total Categories`, `Total Product`: Aggregated metrics used in KPIs

---

## 🛠️ Requirements

- **Software**: [Tableau Desktop](https://www.tableau.com/products/desktop)  
  _Recommended Version: 2021.4 or later_

- **Data Source**:  
  Ensure that the local data file used in the Tableau workbook is available and connected when prompted.

---

## 🚀 Deployment Instructions

### ✅ Local Deployment

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/amazon-sales-dashboard.git
