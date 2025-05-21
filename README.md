# 📦 SQL Data Warehouse Project

This project involves building a SQL-based data warehouse from scratch to support analytical queries on structured business data. The objective is to demonstrate data integration, transformation, and dimensional modeling using a star schema approach.

---

## 📌 Project Overview

The data warehouse is designed to consolidate and store historical business data to enable efficient reporting and decision-making. Using the ETL (Extract, Transform, Load) process, raw operational data is transformed and loaded into well-structured fact and dimension tables for analysis.

---

## 🧰 Tools & Technologies

- **SQL Server** – Relational database for storing and querying structured data  
- **SSMS (SQL Server Management Studio)** – Interface for development and testing  
- **Star Schema** – Dimensional modeling technique  
- **Excel** – (Optional) Used for initial data inspection and preprocessing  

---

## 🗃️ Data Model

The data warehouse uses a star schema optimized for analytical workloads. The model includes:

### Fact Table
- `fact_sales` – Stores transactional sales records

### Dimension Tables
- `dim_customer` – Contains customer details  
- `dim_product` – Contains product information  
- `dim_date` – Contains date hierarchy (day, month, year)  
- `dim_store` – Contains store or regional data  

---

---

## 🚀 How to Run the Project

1. Open **SQL Server Management Studio (SSMS)** and connect to your SQL Server instance  
2. Run `create_tables.sql` to create the database schema  
3. Run `insert_data.sql` to populate the tables with transformed data  
4. (Optional) Run `etl_process.sql` to simulate the end-to-end ETL process  
5. Query the tables to generate analytical insights  

---

## 📊 Example Analytical Queries

- Total monthly sales by product category  
- Top customers ranked by total purchase value  
- Sales performance trends over time  
- Regional sales comparisons  

---

## ✅ Outcomes

- Gained hands-on experience in data warehousing concepts  
- Built and queried a star schema model  
- Implemented an ETL process using SQL  
- Enabled data analysis from raw transactional records  

---


