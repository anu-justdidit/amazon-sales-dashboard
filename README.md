# amazon-sales-dashboard
Power BI dashboard connected to Databricks. Sales analysis with DAX measures.

# 🛒 Amazon Sales Dashboard - Power BI

## 📊 Project Overview

An interactive Power BI dashboard analyzing Amazon product sales data. This project demonstrates end-to-end data analytics skills including data cleaning, DAX measures, and interactive visualizations.

**Key Results:**
- Total Sales: ₹8.2M
- Average Price: ₹5,440
- High-Rated Products (4-5⭐): ₹4.5M

---

## 📈 Dashboard Preview

![Dashboard Overview](screenshots/dashboard_main.png)

---

## 🎯 Key Metrics

| Metric | Value | Insight |
|--------|-------|---------|
| **Total Sales** | ₹8.2M | Overall revenue across all categories |
| **Average Price** | ₹5,440 | Average product price point |
| **High Rated Sales** | ₹4.5M | Revenue from 4-5⭐ products |
| **Low Rated Sales** | ₹0* | No products below 4⭐ in dataset |

*\*Note: All products in this dataset are rated 4 stars or higher*

---

## 📊 Dashboard Visuals

| Visual | Purpose | Insights |
|--------|---------|----------|
| **Total Sales by Category** | Compare revenue across categories | Electronics leads with ₹3.2M |
| **Average Price by Category** | Identify price positioning | Electronics: ₹65K vs Clothing: ₹3.5K |
| **High vs Low Rated Sales** | Rating impact on revenue | High-rated drive 100% of sales |
| **KPI Cards** | At-a-glance metrics | Real-time performance tracking |

---

## 🛠️ Technical Stack

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & visualization |
| **DAX** | Advanced calculations & measures |
| **Power Query** | Data cleaning & transformation |
| **Databricks Community Edition** | Data source & SQL endpoint |
| **GitHub** | Version control & portfolio hosting |

---

## 🧮 DAX Measures Created

### Core Measures
```dax
// Total Sales
Total Sales = SUM('amazon'[actual_price])

// Average Price
Average Price = AVERAGE('amazon'[actual_price])
