# Databricks ETL Sales Pipeline Project

## 📌 Project Overview
This repository contains a collection of **Databricks ETL workflows** developed using **PySpark and Apache Spark**, focused on building a **Daily Sales Data Pipeline**.

The project demonstrates key modern Data Engineering concepts including:

- Batch ETL processing
- Medallion Architecture (Bronze → Silver → Gold)
- Streaming ingestion using Databricks Auto Loader
- Delta Live Tables (DLT) pipelines
- Databricks notebook exports for documentation and review

This work was designed as an interview-style portfolio project showcasing Databricks capabilities.

---

## 🚀 Key Topics Covered

###  Daily Sales ETL Workflow
Building a structured ETL pipeline for daily retail sales processing.

###  Medallion Architecture Implementation
Data layered into:

- **Bronze Layer**: Raw ingestion  
- **Silver Layer**: Cleaned and validated data  
- **Gold Layer**: Aggregated analytics-ready tables  

###  Streaming File Ingestion with Auto Loader
Demonstrates ingestion of streaming data using:

- Structured Streaming  
- Auto Loader  
- ADLS Gen2 integration

###  Delta Live Tables (DLT)
Shows how to build managed ETL pipelines using Databricks Delta Live Tables.

###  Data Table Creation & Manipulation
Covers table creation, transformations, and Spark SQL operations.

