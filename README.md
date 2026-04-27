# 🛍️ Customer Shopping Behavior Analysis

![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue?style=for-the-badge&logo=postgresql)
![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge&logo=python)
![Power BI](https://img.shields.io/badge/Power_BI-Analysis-orange?style=for-the-badge&logo=powerbi)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-green?style=for-the-badge)

## 📌 Project Overview
This project analyzes retail customer data to uncover trends in purchasing habits, payment preferences, and demographic influences on sales. The goal is to provide actionable insights that help improve marketing strategies and customer retention.

The project demonstrates a complete **end-to-end data analytics workflow**, including:
* **Exploratory Data Analysis (EDA)** using Python
* **Data Transformation** via PostgreSQL
* **Advanced SQL Querying** for business metrics
* **Interactive Dashboard Development** in Power BI

---

## ❓ Business Problem
Retail organizations need to understand what drives customer loyalty and high-value purchases. This project answers:
1.  Which **demographics** (Age, Gender) generate the most revenue?
2.  How does **subscription status** impact purchase frequency?
3.  What are the most preferred **payment methods** and **shipping types**?
4.  How do **seasonal trends** affect shopping behavior?

---

## 📊 Dataset
The dataset contains customer transaction details including:
* **Customer ID & Demographics** (Age, Gender, Location)
* **Transaction Details** (Purchase Amount, Category, Item Purchased)
* **Preferences** (Subscription Status, Shipping Type, Payment Method)
* **Feedback** (Review Rating, Previous Purchases)

---

## 🛠️ Tools and Technologies
| Tool | Purpose |
| :--- | :--- |
| **Python (Pandas)** | Initial EDA, data cleaning, and distribution analysis |
| **PostgreSQL** | Data storage and complex analytical SQL queries |
| **Power BI** | Building interactive dashboards and KPI tracking |
| **Excel** | For data inspection and validation |

---

## 🚀 Project Workflow

### 1️⃣ Data Preparation & EDA
Using **Python**, I performed an initial dive into the dataset to identify patterns.
* Handled missing values and verified data types.
* Analyzed distributions for Age and Purchase Amount.
* Visualized correlations between subscription status and review ratings.

### 2️⃣ SQL Analysis
The cleaned data was imported into **PostgreSQL** to extract deep business insights:
* **Total Revenue** and **Average Purchase Value** calculations.
* **Customer Segmentation** by purchase frequency.
* **Category Performance** across different seasons.

### 3️⃣ Dashboard Development
A dynamic **Power BI** dashboard was created to visualize KPIs:
* **Sales Performance Overview**
* **Demographic Breakdown**
* **Payment & Shipping Preferences**

---

## 🖼️ Dashboard Preview
### Behavioral Overview
![Dashboard 1](dashboards_overview/customer_behaviour_dashboard_preview_1.png)

### Demographic Insights
![Dashboard 2](dashboards_overview/customer_behaviour_dashboard_preview_2.png)

---

## 💡 Key Insights
* **Subscription Power:** Members show a significantly higher purchase frequency than non-members.
* **Dominant Category:** **Clothing** is the top revenue-generating category across all regions.
* **Payment Trends:** Credit cards and Digital Wallets are the preferred choice for high-frequency shoppers.
* **Seasonal Peak:** Sales consistently spike during the **Fall** season.

---

## 📂 Repository Structure
```text
customer-behaviour-analysis
│
├── data
│   └── customer_shopping_behavior.csv
│
├── notebooks
│   └── Customer_shopping_behaviour_EDA.ipynb
│
├── sql
│   └── customer_behaviour_analysis.sql
│  
├── dashboards_overview
│   ├── customer_behaviour_dashboard_preview_1.png
│   └── customer_behaviour_dashboard_preview_2.png
│
├── powerBI
│   └── customer_behaviour_analysis.pbix
│
└── README.md
```

---

## 👤 Author
**Prince-sahani**
