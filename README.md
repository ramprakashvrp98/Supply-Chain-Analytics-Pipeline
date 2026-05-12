# 📦 Supply Chain Analytics Pipeline using Snowflake & Power BI

## 📊 Project Overview

This project builds an end-to-end cloud analytics pipeline using AWS S3, Snowflake, SQL, and Power BI to analyze supply chain operations, shipping performance, product profitability, and revenue trends across 180K+ records.

The project demonstrates modern analytics engineering workflows including cloud-based ingestion, data transformation, KPI reporting, task automation, and interactive dashboard development.

---

## 🏗️ Project Architecture

```text
Kaggle CSV Dataset
   |
   v
Amazon S3 Bucket
   |
   v
Snowflake Storage Integration
   |
   v
Snowflake External Stage
   |
   v
Raw Data Layer
   |
   v
Clean Transformation Layer
   |
   v
Analytics Views
   |
   v
KPI Queries
   |
   v
Power BI Dashboard
```
---

## 🛠️ Tools & Technologies Used

- Snowflake
- AWS S3
- SQL
- Power BI
- Snowflake Tasks
- External Stages
- Storage Integrations
- Window Functions
- KPI Reporting

---

## ⚙️ Key Features

- Built cloud-based ingestion pipeline from AWS S3 into Snowflake
- Configured Snowflake storage integrations and external stages
- Developed clean transformation layer using datatype conversions and validation workflows
- Created analytics views for shipping performance and revenue analysis
- Built KPI reporting queries using SQL aggregations and window functions
- Developed interactive Power BI dashboards with slicers and conditional formatting
- Automated refresh workflows using Snowflake Tasks

---

## 📈 Key Business Insights

- First Class shipping showed the highest late delivery percentage
- Standard Class handled the highest shipment volume
- Revenue peaked during Q3 2017
- Shipping performance varied significantly across shipping modes
- Top product categories contributed a significant share of total revenue

---

## 📊 Dashboard Features

- KPI Cards
- Revenue & Profit Trend Analysis
- Shipping Delay Analysis
- Category Revenue Analysis
- Interactive Slicers
- Conditional Formatting
- Operational KPI Monitoring

---

## 📂 SQL Workflow Structure

/sql
    01_setup.sql
    02_file_format.sql
    03_storage_integration.sql
    04_raw_table.sql
    05_copy_into.sql
    06_clean_layer.sql
    07_analytics_views.sql
    08_kpi_queries.sql
    09_task_automation.sql

---

## 🚀 Future Improvements

- Implement Streams + MERGE for incremental loading
- Add Snowpipe automation
- Integrate dbt transformation workflows
- Expand dashboard with forecasting analysis

---

## 👤 Author

Ram Prakash Venkatesh
