# 📊 E-Commerce KPIs & Sales Dashboard | Advanced Excel

> An end-to-end Excel analytics project analysing 500 e-commerce transactions across 8 cities — covering revenue, delivery performance, and coupon effectiveness through interactive KPI dashboards.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel (Advanced)** — Pivot Tables, VLOOKUP, IF, COUNTIFS, SUMIFS
- **Dashboard Design** — KPI cards, charts, slicers, conditional formatting
- **Data Cleaning** — Handling date formats, derived columns, delivery status flags

---

## 🎯 Objective

To analyse transactional e-commerce data and build an interactive dashboard that answers key business questions:
- Which cities generate the most revenue?
- How effective are different discount coupon codes?
- What percentage of deliveries are late — and where?
- What drives the gap between estimated and actual delivery days?

---

## 📁 Dataset Overview

| Column | Description |
|--------|-------------|
| `Customer_ID` | Unique customer identifier (100 unique customers) |
| `Order_ID` | Unique order identifier |
| `Order_Date` | Date the order was placed |
| `City` | Customer city (8 cities across the US) |
| `Price` | Unit price of the product |
| `Quantity` | Number of units ordered |
| `Coupon_Code` | Discount coupon applied (FLAT8, FLAT10, FLAT15, FLAT20, DEL0) |
| `Delivery_Charge` | Shipping fee charged |
| `Days_to_Deliver` | Actual days taken for delivery |
| `Estimated_Days_to_Deliver` | Expected delivery days at order time |
| `IsLateDelivery` | Delivery status: `Late`, `Intime`, or `BeforeTime` |
| `Final_Amount` | Revenue after discount and delivery charge |

- **Total Rows:** 500 transactions
- **Customers:** 100 unique customers
- **Cities:** Phoenix, Houston, New York, Los Angeles, Miami, Chicago, San Francisco, Dallas

---

## 🔍 Key Steps

1. **Data Cleaning** — Standardised date columns, created `Full_Name` and `Email_Domain` derived columns, flagged late deliveries using `IsLateDelivery`
2. **KPI Calculation** — Total revenue, late delivery rate, average order value, discount impact using SUMIFS and COUNTIFS
3. **Pivot Analysis** — Revenue by city, coupon usage, delivery performance breakdown
4. **Dashboard Design** — Built interactive dashboard with slicers for city and coupon filter

---

## 📈 Key Insights

- **Total Revenue: ₹3,49,724** across 500 orders from 100 customers
- **Houston is the top revenue city** at ₹60,581 (17.3% of total), followed by San Francisco (₹50,133) and Los Angeles (₹48,033)
- **Miami has the lowest revenue** at ₹25,015 — indicating lower order volume or lower average order value
- **42% of deliveries were late** — a significant fulfilment concern that directly impacts customer satisfaction
- **FLAT8 coupon drove the highest revenue** (₹80,846) despite offering the smallest discount, suggesting customers respond well to even small incentives
- **FLAT15 generated the least revenue** among discount codes (₹57,942), possibly because it attracts lower-value orders or fewer users
- **DEL0 (free delivery) contributed ₹78,702** — second highest, showing delivery cost is a key conversion lever

---

## 📸 Dashboard Preview

![Dashboard Preview]<img width="1906" height="1015" alt="E-commerce KPIs dashboard" src="https://github.com/user-attachments/assets/a9bdaa00-6ac2-46df-ba5e-895e4fdb172f" />

<img width="1914" height="1017" alt="Visual_analysis(1)" src="https://github.com/user-attachments/assets/7bcc8944-f8e4-43a0-b56c-a3fdf96f18d0" />

<img width="1917" height="1016" alt="Visual_analysis(2)" src="https://github.com/user-attachments/assets/66fd5dee-9b00-4c59-b216-8646b9f00eb6" />

<img width="1920" height="1080" alt="Visual_analysis(3)" src="https://github.com/user-attachments/assets/48f88703-b39e-406b-b160-bc961a74cef0" />

---

## 🚀 How to Use

1. Download the file `E-Commerce_KPIs_Dashboard.xlsx`
2. Open in **Microsoft Excel 2016 or later** (required for full slicer/pivot functionality)
3. Navigate to the **Dashboard** sheet to view the interactive KPI dashboard
4. Use the slicers to filter by **City** or **Coupon Code**
5. The **data** sheet contains the raw 500-row dataset

---

## 📂 Project Structure

```
ecommerce-kpi-dashboard/
├── E-Commerce_KPIs_Dashboard.xlsx   ← Main Excel file (data + dashboard)
├── images/
│   └── dashboard.png                ← Screenshot of the dashboard
└── README.md
```

---

## 💡 What I Learned

- Building multi-layer KPI dashboards with dynamic slicers in Excel
- Using SUMIFS and COUNTIFS to generate city-wise and coupon-wise summaries
- Interpreting delivery performance metrics to surface actionable operations insights
- Communicating data findings in a clean, non-technical dashboard format

---

## 🙋 About Me

Made by **[Abhishek Jain](https://github.com/abhishekjain2004)**  
Aspiring Data Analyst | PG in Data Science & Analytics with Gen AI @ Imarticus Learning  
📧 abhishek2004.jain@gmail.com · [LinkedIn]www.linkedin.com/in/abhishek-jain-297014277
