# 📊 YouTube Trending ETL Pipeline using AWS & Python

This project demonstrates a scalable, serverless ETL (Extract, Transform, Load) pipeline built using **AWS services** and **Python** to process and analyze YouTube trending video data from Kaggle. The pipeline automates ingestion, transformation, and visualization of video statistics to gain insights into trending patterns across categories and regions.

---

## 🚀 Project Overview

- **Data Source**: Kaggle YouTube Trending Video Dataset (CSV + JSON)
- **Goal**: Automate ETL using AWS tools and visualize data to uncover trends in video engagement
- **Pipeline Highlights**:
  - Store raw data in Amazon S3
  - Transform and clean data with AWS Glue (Spark + Python)
  - Trigger transformations using AWS Lambda and Data Wrangler
  - Catalog datasets with AWS Glue Crawlers
  - Query transformed data using AWS Athena
  - Visualize KPIs in Amazon QuickSight dashboards

---

## 🛠️ Tech Stack

- **Languages**: Python 3, SQL
- **AWS Services**:
  - S3 – Data lake storage (raw, cleansed, analytics)
  - Glue – ETL jobs, data crawlers, Glue Catalog
  - Lambda – Serverless orchestration and transformation
  - Athena – Serverless SQL queries on S3 data
  - QuickSight – BI dashboards and visual analysis
  - IAM – Secure role-based access

---

## 📁 Project Structure

```bash
├── data/
│   ├── JPvideos.csv
│   └── JP_category_id.json
├── lambda/
│   └── etl_function.py
├── glue/
│   ├── crawler_config.json
│   └── spark_etl_job.py
├── notebooks/
│   └── exploratory_data_analysis.ipynb
├── visuals/
│   └── dashboard_screenshot.png
└── README.md

---


## 🧠 Learning Outcomes

Hands-on experience with AWS-based ETL architecture

Real-world data engineering with serverless components

Efficient data lake management using Parquet and Athena

Interactive BI reporting and KPI visualization

📎 Dataset
Kaggle – Trending YouTube Video Statistics https://www.kaggle.com/datasets/datasnaek/youtube-new
