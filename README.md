


# 📊 Sales Data Warehouse & Analytics Project

## 📖 Overview

This project focuses on building a **modern data warehouse** using SQL Server to transform raw business data into meaningful insights. It follows the **Medallion Architecture (Bronze, Silver, Gold layers)** to ensure a structured and scalable data pipeline.

The system ingests raw data from multiple sources (ERP and CRM), performs data cleaning and transformation, and organizes it into an optimized data model for analytical querying and reporting.

---

## 🏗️ Data Architecture

The project is designed using a layered architecture:

* **Bronze Layer**
  Stores raw data ingested from CSV files into SQL Server without any modifications.

* **Silver Layer**
  Performs data cleansing, standardization, and integration of multiple data sources.

* **Gold Layer**
  Contains business-ready data modeled using a **star schema** (fact and dimension tables) for efficient analytics.

---

## ⚙️ Key Components

### 🔹 ETL Pipeline

* Extracts data from CSV files (ERP & CRM systems)
* Transforms data through cleaning and standardization
* Loads processed data into structured warehouse tables

### 🔹 Data Modeling

* Designed using **Fact and Dimension tables**
* Optimized for analytical queries and reporting

### 🔹 Analytics & Reporting

* SQL-based analysis to generate insights on:

  * Customer behavior
  * Product performance
  * Sales trends

---

## 🎯 Objectives

* Consolidate data from multiple sources into a single system
* Improve data quality for reliable analysis
* Enable efficient querying using structured data models
* Support business decision-making through data insights

---

## 🛠️ Tools & Technologies

* **SQL Server Express** – Database
* **SSMS (SQL Server Management Studio)** – Querying & management
* **CSV Files** – Data source
* **Draw.io** – Architecture & data modeling diagrams
* **GitHub** – Version control

---

## 📌 Project Scope

* Focus on processing the **latest available dataset**
* No historization or time-based versioning implemented
* Manual data ingestion and pipeline execution

---

## 🚀 Outcome

This project demonstrates the end-to-end workflow of:

* Building a data warehouse
* Designing ETL pipelines
* Structuring data for analytics
* Generating business insights using SQL

---

## 📈 Use Cases

* Sales performance analysis
* Customer segmentation
* Product demand tracking
* Trend analysis for decision-making

---

## 🔗 Repository Contents

* SQL scripts for ETL and data modeling
* Dataset (CSV files)
* Architecture and schema diagrams
* Documentation of workflow and steps

---

## 🧠 Conclusion

This project showcases how raw data can be transformed into structured, analysis-ready information using a data warehouse approach. It highlights core concepts of **data engineering and data analytics**, making it suitable for learning and demonstrating practical skills in real-world scenarios.

