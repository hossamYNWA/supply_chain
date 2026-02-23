# 📊 Supply Chain Analytics Dashboard

An interactive business intelligence dashboard built in **Excel** providing comprehensive insights into **order management**, **delivery performance**, and **profitability analysis** for supply chain operations.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dashboard Views](#dashboard-views)
- [Key Metrics](#key-metrics)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Screenshots](#screenshots)
- [Author](#author)

---

## 📖 Overview

This Excel-based dashboard consolidates critical supply chain data into three main analytical views, enabling data-driven decision-making for:
- **Delivery Performance Monitoring** - Track on-time delivery rates and identify bottlenecks
- **Profit Analysis** - Analyze margins by category, supplier, and time period
- **Order Management** - Monitor order status, volume trends, and supplier performance

The visualizations help stakeholders quickly identify trends, anomalies, and opportunities for operational improvement.

---

## ✨ Features

- **Real-time KPI Tracking** - Monitor total orders, profit, delivery times, and compliance rates
- **Multi-dimensional Analysis** - Slice data by supplier, category, month, and delivery status
- **Interactive Visualizations** - Bar charts, line graphs, pie charts, and trend analysis
- **Supplier Performance Tracking** - Compare delivery quality and profitability across suppliers
- **Time-series Analysis** - Track monthly trends in orders, deliveries, and profits
- **Defect Analysis** - Monitor defective units per supplier for quality control
- **Automated Calculations** - Built-in formulas for margins, compliance rates, and averages

---

## 📊 Dashboard Views

### 1. **Delivery Analysis**
   - On-time delivery rate tracking (26%)
   - Average delivery days (11 days)
   - Late orders trend by month
   - Delivery quality per supplier
   - Defective units analysis

### 2. **Profit Analysis**
   - Total profit tracking ($9,501)
   - Average margin by category (26%)
   - Cost vs retail price comparison
   - Profit distribution by supplier
   - Monthly profit trends
   - Compliance percentage (82%)

### 3. **Orders Analysis**
   - Total orders overview (777 orders)
   - Order status breakdown (72% delivered, 10% cancelled, 9% partially delivered, 8% pending)
   - Orders per supplier comparison
   - Monthly order volume trends
   - Category-wise order status
   - Compliance rate (97%)

---

## 📈 Key Metrics

| Metric | Value |
|--------|-------|
| **Total Orders** | 777 |
| **Total Profit** | $9,501 |
| **Average Delivery Days** | 11 days |
| **On-time Delivery Rate** | 26% |
| **Average Margin** | 26% |
| **Compliance Rate** | 82-97% |

---

## 🛠 Technologies Used

- **Platform**: Microsoft Excel
- **Excel Version**: Excel 2016 or later
- **Features Used**:
  - Pivot Tables & Pivot Charts
  - Advanced Formulas (SUMIFS, AVERAGEIFS, COUNTIFS, etc.)
  - Conditional Formatting
  - Slicers & Timeline Filters
  - Dynamic Named Ranges
  - Data Validation
  - Chart Objects (Bar, Line, Pie, Combo charts)

---

## 📖 Usage

### Navigation:
- **Switch between dashboards** using the sheet tabs at the bottom:
  - `Delivery Analysis`
  - `Profit Analysis`
  - `Orders Analysis`
  - `Pivot tables`
  - `Data` (raw data sheet)

### Key Questions This Dashboard Answers:
- Which suppliers have the best/worst delivery performance?
- What are the most profitable product categories?
- How do order volumes fluctuate throughout the year?
- What percentage of orders are delivered on time?
- Which months show peak order activity?
- Which suppliers have the highest defective units?

---

## 📁 Data Sources

The dashboard integrates data from multiple tables:

### Data Structure:
- it was a one large tabe containig these columns: (PO_ID | Supplier | Order_Date | Delivery_Date |Item_Category | Order_Status | Quantity | Unit_Price | Negotiated_Price | Defective_Units | Compliance)
- then I added 4 more columns to improve the analysis process (profit | margin | delivery time	| delivery quality)
- 
---

## 📸 Screenshots

The dashboard includes three main views:

### Delivery Analysis Dashboard
- Shows delivery quality metrics, late orders trends, and supplier performance
- Visualizes defective units and average delivery days per supplier

### Profit Analysis Dashboard  
- Displays profitability by category, supplier, and monthly trends
- Compares cost price vs retail price across categories

### Orders Analysis Dashboard
- Tracks order volume, status distribution, and delivery timelines
- Shows orders per supplier and category-wise breakdown

---

## 🔍 Insights & Findings

### Key Observations:
- **Delta Logistics** has the highest defective units (154.94) requiring quality review
- **Packaging** category shows the highest margin (28%)
- **March** and **August** are peak order months
- **On-time delivery rate** (26%) needs significant improvement
- **Epsilon Group** and **Delta Logistics** are top suppliers by order volume
- **Electronics** has the lowest margin (24%) despite high retail prices

## 👤 Author

**Hossam Badawy**

- LinkedIn: [connect with me](www.linkedin.com/in/hossam-badawy)
- Email: [contact me](hossam.mousa779@gmail.com)
