# Product_Return_Analysis_PostgreSQL_PowerBI
Product Return Analysis Dashboard using Power BI to analyze return rates, warehouse performance, return reasons, categories, and monthly trends for actionable business insights.
# Product Return Analysis Dashboard

## 📊 Project Overview

The **Product Return Analysis Dashboard** is an interactive Power BI dashboard designed to analyze product returns and identify key factors contributing to returned orders.

The dashboard provides a clear view of return performance across **warehouses, product categories, return reasons, and months**, helping businesses identify return patterns and areas that require attention.

---

## 🎯 Objectives

- Monitor total product orders and returned orders.
- Calculate the overall product return rate.
- Analyze return performance across different warehouses.
- Identify the most common reasons for product returns.
- Analyze return trends by month.
- Compare return performance across product categories.
- Identify areas where return rates can be reduced.

---

## 📌 Key KPIs

The dashboard includes the following key performance indicators:

- **Total Product Orders:** 411
- **Total Returned Orders:** 204
- **Return Rate:** 49.64%

---

## 📈 Dashboard Insights

### Return Rate by Warehouse

The dashboard compares return performance across three warehouses:

| Warehouse | Returned Orders | Return Rate |
|-----------|-----------------|-------------|
| Mumbai | 77 | 37.75% |
| Delhi | 75 | 36.76% |
| Bangalore | 52 | 25.49% |

Mumbai has the highest number of returned orders, while Bangalore has the lowest return rate among the three warehouses.

### Reasons for Product Returns

The major return reasons identified in the dashboard are:

| Return Reason | Returned Orders |
|---------------|-----------------|
| Size Issue | 75 |
| Damaged in Transit | 34 |
| Quality Defect | 34 |
| Changed Mind | 32 |
| Wrong Item | 29 |

**Size issues** are the leading reason for product returns, making them a major area for potential improvement.

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Data Cleaning**
- **Data Transformation**
- **Data Visualization**
- **KPI Analysis**
- **Business Intelligence**

---

## 🔍 Dashboard Features

- Interactive KPI cards
- Warehouse-wise return analysis
- Return reason analysis
- Category filter
- Monthly filter
- Return rate calculation
- Interactive visualizations
- Business-focused performance reporting

---

## 💡 Business Insights

The analysis highlights several areas that can help reduce product returns:

1. **Size issues are the biggest return driver**, suggesting that better size guides, product measurements, and fit information could help reduce returns.

2. **Mumbai has the highest number of returned orders**, making it an important warehouse for further investigation.

3. **Damaged products during transit** represent another significant return reason, indicating a need to review packaging and logistics processes.

4. Monitoring return performance by **category and month** can help identify recurring return patterns and operational issues.

---

## 📷 Dashboard Preview

![Product Return Analysis Dashboard](dashboard.png)

---

## 📂 Project Structure

```text
Product-Return-Analysis/
│
├── Dashboard/
│   └── Product_Return_Analysis.pbix
│
├── Dataset/
│   └── dataset.csv
│
├── Images/
│   └── dashboard.png
│
└── README.md
