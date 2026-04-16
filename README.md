# 🛒 Olist E-Commerce Analytics Dashboard

![Tableau](https://img.shields.io/badge/Tableau-Public-E97627?logo=tableau&logoColor=white)
![Dataset](https://img.shields.io/badge/Dataset-Olist%20E--Commerce-blue)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Overview

An interactive Business Intelligence dashboard analyzing 100,000+ orders from the Brazilian Olist e-commerce platform. Built in Tableau Public using a multi-table relational data model across six integrated datasets.

This project answers a key business question:

> **Where is revenue generated, how is it growing, and what drives customer purchasing behavior?**

---

## 🔗 Live Dashboard

👉 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/OlistE-CommerceAnalyticsDashboard_17761434741750/OlistE-CommerceAnalyticsDashboard)

---

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Orders | 65,536 |
| Total Revenue | $16,008,872 |
| Average Order Value | $154.10 |
| Total Customers | 99,441 |

---

## 💡 Key Business Insights

- **Health & Beauty generates the highest revenue ($1.3M)**, driven by high purchase frequency and low order value
- **Computers lead in average order value ($1,098)**, reflecting low volume but high-ticket purchases
- **Revenue increased ~10x from 2016 to 2018**, indicating rapid platform growth
- **Credit cards account for 75%+ of payments**, dominating all other methods
- **São Paulo (SP) contributes ~40% of total orders**, showing strong geographic concentration
- **96.9% of orders are successfully delivered**, indicating efficient fulfillment operations
- **Clear customer segmentation emerges**: high-frequency low-value vs low-frequency high-value buyers

---

## 🗂️ Data Model

Six relational datasets integrated in Tableau:

```
olist_orders_dataset.csv
├── olist_order_items_dataset.csv
│       └── olist_products_dataset.csv
│               └── product_category_name_translation.csv
├── olist_customers_dataset.csv
└── olist_order_payments_dataset.csv
```

---

## 🔍 Dashboard Components

**KPI Overview:**
- Total Orders | Total Revenue | Avg Order Value | Total Customers

**Visualizations:**
- Monthly Revenue Trend — growth analysis (2016–2018)
- Top 10 Categories by Revenue — performance ranking
- Average Order Value by Category — pricing insights (treemap)
- Top 10 Customer States — geographic distribution
- Revenue by Payment Type — payment behavior
- Order Status Breakdown — operational performance

**Interactivity:**
- Dynamic filtering across all visuals (category, state, payment type, order status)

---

## 🛠️ Tools & Skills

- **Tableau Public** — dashboard design, relationships, calculated fields
- **Data Modeling** — multi-table joins using relational keys
- **Business Intelligence** — KPI design, interactivity, storytelling
- **Data Cleaning** — null handling, transformations, type corrections

---

## 📁 Dataset

- **Source:** [Kaggle — Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Size:** 100,000+ orders across 6 datasets
- **Period:** 2016–2018
- **Type:** Real-world commercial transaction data

---

## 👤 Author

**Mohammad Rahimi**
Student @ Rochester Institute of Technology — Dubai
[LinkedIn](https://www.linkedin.com/in/mohammad-rahimi-b23163351/) • [GitHub](https://github.com/Nasrawi04)
