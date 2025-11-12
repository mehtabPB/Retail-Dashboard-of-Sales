# 🟡 Power BI Sales Performance Dashboard

> **Visualize. Analyze. Optimize.**  
> A dynamic Power BI dashboard that provides an interactive view of sales, profits, and customer insights — all in one place.

---

## 📊 Overview

This Power BI dashboard delivers a comprehensive snapshot of business performance, helping users monitor key metrics such as:

- 🧍‍♂️ **Number of Customers**
- 📦 **Products Sold**
- 💰 **Profit Generated**
- 🏙️ **Sales by City, Month, and Category**
- 🧮 **Profitability by Product**
- 👑 **Top 5 Customers by Revenue**

The report integrates multiple data sources with clean relationships for seamless analysis.

## 🌟 Sneak Peek

### Dashboard Preview  

<img width="1334" height="749" alt="Screenshot 2025-11-09 193421" src="https://github.com/user-attachments/assets/12f1a9dc-b623-4c0d-a342-0ff2fbb2a1c8" />


---

## 🧠 Data Model

The data model follows a **star schema**:

| Table | Description | Key Columns | Relationships |
|-------|--------------|--------------|----------------|
| **PowerBI_Test_Data(Sales)** | Transaction-level sales data | `CustomerID`, `ProductID`, `Date` | Many-to-One → `Products`, `Customers` |
| **PowerBI_Test_Data(Products)** | Product catalog with cost & category details | `ProductID` | One-to-Many ← `Sales` |
| **PowerBI_Test_Data(Customers)** | Customer demographics | `CustomerID` | One-to-Many ← `Sales` |

🧩 **Relationships Visual:**

---

## 🪄 Key Insights

| Metric | Insight |
|--------|----------|
| **Total Customers** | 55 |
| **Total Products Sold** | 12K |
| **Total Profit** | ₹19.35M |
| **Top Product by Revenue** | Printer (₹21M) |
| **Top Customer by Revenue** | Customer_53 (₹6.09M) |

---

## 📈 Dashboard Highlights

### 1. **Revenue by Product**
A horizontal bar chart showing product-level revenue — instantly revealing top performers.

### 2. **Profit Analysis**
A detailed product-wise breakdown with total sales, cost, and profit margins.

### 3. **Sales Trend by Month**
Line chart visualizing monthly fluctuations in total sales.

### 4. **Category Breakdown**
Pie chart illustrating product distribution across major categories like *Accessories, Computers, Networking, and Mobile.*

### 5. **Top Customers**
Table showcasing the top 5 revenue-generating customers.

---

## 🧩 Filters & Slicers

Interact with the dashboard using:
- 📅 **Date range slicer**
- 🗓️ **Year & Quarter selector**
- 🏙️ **City filter**
- 🗓️ **Month dropdown**

These filters make the report flexible and user-friendly — great for deep dives and trend spotting.

---

## ⚙️ Tech Stack

| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Data modeling & visualization |
| **DAX** | Calculations and measures |
| **Excel/CSV Sources** | Raw data import |
| **Power Query** | Data transformation |

---

## 🚀 How to Use

1. Open `Sales_Dashboard.pbix` in **Power BI Desktop**.
2. Refresh the data connections if prompted.
3. Explore visuals using the interactive slicers.
4. Hover over charts for tooltips and details.

---

## 🎨 Design Philosophy

Clean. Minimal. Insightful.  
The dashboard is built with **warm yellow accents** for visibility and **rounded cards** for a modern look.

---


---

## 💡 Author

**Created by:** Mehtab  

📧 *Power BI | Data Analytics | Visualization Enthusiast*  

---

## 🏁 Conclusion

This dashboard transforms raw sales data into **actionable insights**.  
Track your KPIs, optimize performance, and empower decision-making — all in one interactive report.  

> “Data is the new oil, but visualization is the refinery.” 🔥


