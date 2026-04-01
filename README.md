# ecommerce-sales-performance-and-time-Intelligence-dashboard-PowerBI
This project presents an interactive Power BI dashboard designed to analyze and monitor e-commerce sales performance across products, regions, and time.  The dashboard leverages advanced data modeling and time intelligence techniques to provide actionable insights into business performance.

# 📊 E-Commerce Sales Performance & Time Intelligence Dashboard (Power BI)

## 📌 Project Overview

This project presents an interactive Power BI dashboard designed to analyze and monitor e-commerce sales performance across products, regions, and time.

The dashboard leverages data modeling, time intelligence, and dynamic metric selection to provide actionable insights into business performance and support data-driven decision-making.


## 🎯 Business Questions & Hypotheses

This analysis was designed to answer key business questions:

* How is current Year-to-Date (YTD) performance compared to the previous year (PYTD)?
* Which product categories contribute the most to revenue and profitability?
* Are there underperforming regions despite high sales volume?
* Is business growth driven by increased sales volume or improved profit margins?
* How does Gross Profit (%) trend over time across different product categories?


## 📊 Analytical Objectives

* Track and compare YTD vs PYTD performance
* Identify top-performing and underperforming categories
* Analyze regional sales and profitability trends
* Evaluate efficiency using Gross Profit (%)
* Enable flexible, user-driven analysis through dynamic metric selection


## 🧱 Data Model

A **star schema** data model was implemented for efficient analysis:

* **Fact Table**

  * Sales transactions (Sales, Profit, Quantity, Order Date)

* **Dimension Table**

  * The Dim_Region and Dim_product
  * Dim_Date (custom-built calendar table)

This structure ensures optimal performance and accurate filtering across visuals.


## ⚙️ Key Features

### 🔹 Time Intelligence Analysis

* Year-to-Date (YTD) performance tracking
* Previous Year-to-Date (PYTD) comparison
* Variance analysis (YTD vs PYTD)

A custom filtering logic was implemented to ensure fair comparison between equivalent time periods.


### 🔹 Dynamic Metric Switching

Users can dynamically switch between:

* Sales
* Quantity
* Gross Profit

This allows a single dashboard to support multiple analytical perspectives without redesigning visuals.


### 🔹 Interactive Dashboard

* KPI cards for high-level performance tracking
* Trend analysis over time
* Category and regional breakdowns
* Profitability insights using Gross Profit (%)
* Slicers and filters for drill-down analysis


### 🔹 Dynamic Titles & Context Awareness

Visual titles update automatically based on user selections, improving clarity and storytelling.


## 📈 Key Insights 

* Sales performance varies significantly across product categories, with a few categories driving the majority of revenue
* Certain regions show high sales volume but relatively lower profitability, indicating cost inefficiencies
* Year-over-Year comparison highlights periods of strong growth as well as potential decline trends
* Gross Profit (%) trends reveal fluctuations in profitability across time and categories



## 🛠 Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling (Star Schema)



## 📷 Dashboard Preview

*(Insert screenshots here)*



## ▶️ How to Use

1. Download the `.pbix` file
2. Open using Power BI Desktop
3. Use slicers to explore different metrics and dimensions


## 🎥 Demo Video

👉 *(Video Link)*



## 💡 Key Learning Outcomes

* Applying time intelligence functions for business analysis
* Designing dynamic and interactive dashboards
* Implementing efficient data models (star schema)
* Translating raw data into meaningful business insights





## 🚀 Author

Latifah Usaini Bashir - Data Analyst/Science Enthusiast

---
