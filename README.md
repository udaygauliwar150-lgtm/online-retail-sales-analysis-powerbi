 📊 Online Retail Sales Dashboard | Power BI

## 📌 Project Overview

This project is an interactive Power BI dashboard developed using the Online Retail dataset to analyze sales performance, customer behavior, product performance, and geographical sales distribution.

The dashboard enables users to explore business performance through interactive KPIs, charts, and slicers, making it easier to identify trends and support data-driven decision-making.

---

## 🎯 Business Objectives

- Monitor overall sales performance
- Analyze monthly sales trends
- Identify top-performing products
- Identify high-value customers
- Compare sales across different countries
- Analyze UK and International market performance

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel
- GitHub

---

## 📂 Dataset

**Dataset:** Online Retail Dataset

The dataset contains transactional retail sales data, including invoices, products, customers, quantities, prices, invoice dates, and countries.

---

## 🧹 Data Cleaning & Preparation

The following data preparation steps were performed before building the dashboard:

- Removed duplicate records
- Removed cancelled transactions
- Removed rows with missing product descriptions
- Handled missing Customer IDs
- Created Sales column (Quantity × Unit Price)
- Created Year, Month, Month Number, Quarter and Day columns
- Created Market Type (UK / International)
- Prepared data for interactive filtering and analysis

---

## 📊 Dashboard Features

### KPI Cards

- 💰 Total Revenue
- 📦 Total Orders
- 👥 Total Customers
- 🛒 Total Quantity Sold
- 💳 Average Order Value

### Visualizations

- 📈 Monthly Sales Trend
- 🏆 Top 10 Products by Revenue
- 👤 Top 10 Customers by Revenue
- 🌍 Top Countries by Revenue

### Interactive Filters

- Month
- Customer Type
- Market Type (UK / International)

---

## 💡 Key Insights

## 💡 Key Insights

- 🌍 **United Kingdom** generated the highest overall revenue, making it the dominant market in the dataset.
- 🗓️ When **UK sales are included**, **November** recorded the highest sales revenue, indicating strong year-end demand.
- 🌐 When **UK sales are excluded** (International market only), **October** recorded the highest sales revenue, showing a different seasonal trend in international markets.
- 📦 **[DOTCOM POSTAGE]** generated the highest revenue among all products.
- 👤 **Customer ID [14646]** generated the highest revenue among all customers.
- 📈 A small number of customers contributed a significant share of the total revenue, highlighting the importance of high-value customers.
- 📊 The interactive slicers allow users to compare sales trends by **Month**, **C**, and **Market Type (UK vs. International)** for deeper business analysis.

---

## 📷 Dashboard Preview
<img width="1307" height="732" alt="dashboard-overview" src="https://github.com/user-attachments/assets/e876bc40-ba1f-446e-9e20-791df47ef4a6" />
```

---

## 📁 Repository Structure

```
Online-Retail-Sales-Dashboard/
│
├── Online Retail Sales Dashboard.pbix
├── Online Retail Dataset.csv
├── README.md
└── images/
    ├── dashboard-international.png
    ├── dashboard-month-filter.png
    └── dashboard-overview.png
```
---

## 👨‍💻 Author

**Uday Gauliwar**

Aspiring Data Analyst

### Skills Demonstrated

- Data Cleaning
- Data Modeling
- Power Query
- DAX
- Dashboard Design
- Data Visualization
- Business Analysis

---

⭐ If you found this project useful, consider starring the repository.
