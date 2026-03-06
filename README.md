# 📊 Business Insights 360 – Power BI Analytics Dashboard

A comprehensive **Business Intelligence solution built using Power BI** to analyze company performance across Finance, Sales, Marketing, Supply Chain, and Executive perspectives.

---

# 🧩 Problem Statement

Atliq Hardware is a rapidly growing global company operating across multiple markets. As the company expanded, leadership faced several analytical challenges:

* Sales and financial data were distributed across multiple systems.
* Executives lacked a **centralized analytics platform** for decision-making.
* It was difficult to identify **top-performing products and customers**.
* Forecast accuracy and operational performance were hard to monitor.
* Business teams relied on static reports instead of interactive insights.

Because of these challenges, answering key business questions became difficult:

* Which markets generate the most revenue?
* Which products contribute the highest profit?
* Which customers drive business growth?
* How accurate are sales forecasts?
* What operational costs impact profitability?

To address these issues, a **centralized Business Intelligence dashboard** was developed.

---

# 🎯 Project Objective

The goal of this project is to build an **interactive Power BI analytics dashboard** that enables stakeholders to monitor business performance across different departments.

The dashboard provides insights into:

* Financial performance
* Sales and customer analytics
* Marketing effectiveness
* Supply chain forecasting accuracy
* Executive-level KPIs

This allows leadership to make **data-driven strategic decisions**.

---

# 📦 Dataset Overview

The dataset represents operational data for **Atliq Hardware** including sales transactions, customer information, product details, and financial metrics.

Key business entities include:

* Customers
* Products
* Markets
* Sales transactions
* Forecast data
* Operational costs
* Financial performance metrics

⚠️ The dataset used in this project is part of the **Codebasics Business Intelligence course** and cannot be publicly distributed.

---

# 🧹 Data Cleaning & Transformation

Data preparation was performed using **Power Query**.

Key data transformation steps included:

* Removing duplicate records
* Handling missing and null values
* Standardizing product and customer naming conventions
* Correcting inconsistent date formats
* Creating hierarchical relationships for markets and products
* Fixing incorrect data types
* Creating calculated columns for analytical logic

These steps ensured **data accuracy, consistency, and reliability** before building the analytical model.

---

# 🧠 Data Model

The dashboard is built using a **Multi-Fact Star Schema data model** to support scalable analytics and optimized query performance.

Fact tables store transactional data, while dimension tables provide descriptive attributes used for filtering and analysis.

### Fact Tables

* fact_sales_monthly
* fact_forecast_monthly
* fact_actuals_estimates
* freight_cost
* manufacturing_cost
* post_invoice_deductions
* operational_expenses
* targets
* marketshare

### Dimension Tables

* dim_customer
* dim_product
* dim_market
* dim_date
* category
* market view list

### Supporting Calculation Tables

Additional tables were created to enable advanced analytical features such as:

* Dynamic Profit & Loss statements
* Parameter-driven analysis
* Benchmark comparisons
* KPI calculations

Examples include:

* P&L Rows
* P&L Columns
* Key Measures
* Report Refresh Date
* Target Gap Tolerance
* Parameter tables

---

# 📐 Data Model Diagram

![Data Model](../images/data_model.png)

---

# 📊 Dashboard Preview

Below is a preview of the Business Insights 360 dashboard.

![Dashboard Preview](images/dashboard_preview.png)

---

# 📄 Full Dashboard Views

The complete dashboard containing **all analytical views** can be accessed below.

[Download Full Dashboard Views](views/BI360_All_Views.pdf)

The dashboard includes the following analytical pages:

* Home View
* Finance View
* Sales View
* Marketing View
* Supply Chain View
* Executive View

---

# 🔍 Key Insights

The dashboard enables identification of several important business insights:

* A small percentage of customers contribute a majority of revenue.
* Certain product segments generate significantly higher margins.
* Forecast accuracy varies across markets.
* Operational costs strongly influence net profit margins.

These insights allow leadership to **identify growth opportunities and operational inefficiencies**.

---

# ✅ Business Solution

The Business Insights 360 dashboard provides a **centralized analytics platform** that enables decision makers to:

* Monitor company performance in real time
* Identify profitable products and markets
* Track operational efficiency
* Improve forecasting accuracy
* Make faster and more informed business decisions

---

# 🛠 Tools & Technologies Used

* Power BI
* DAX (Data Analysis Expressions)
* Power Query
* Data Modeling
* Business Intelligence Design

---

# 🌐 Live Dashboard

The interactive Power BI dashboard can be accessed here:

https://app.powerbi.com/view?r=eyJrIjoiNjExOWQwZmYtOGE4ZC00NDIzLWJiYjYtNTU4ZWE1Mjc3MGM5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

---

# 📁 Repository Structure

```
Business-Insights-360-PowerBI
│
├── images
│   ├── data_model.png
│   └── dashboard_preview.png
│
├── views
│   └── BI360_All_Views.pdf
│
└── README.md
```

---

# 👨‍💻 Author

**Shubhayan Kundu**

Aspiring Data Analyst
Power BI | Data Analytics | Business Intelligence
