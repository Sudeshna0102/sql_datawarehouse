# 🏗️ SQL Data Warehouse Project

## 📌 Objective

This project builds a **SQL-based data warehouse** that consolidates data from multiple sources into a structured and analysis-ready format.

The warehouse is designed to support **data analysis, reporting, and the generation of meaningful business insights** for decision-making.

---

## 🏛️ Architecture

The data warehouse follows the **Medallion Architecture** and consists of three layers:

### 🥉 Bronze Layer

Stores raw data extracted from the source CSV files with minimal transformation, preserving the original source data.

### 🥈 Silver Layer

Cleans, standardizes, and transforms the raw data from the Bronze layer. This stage handles data quality issues and prepares the data for integration and further analysis.

### 🥇 Gold Layer

Transforms the cleaned data into business-ready **fact and dimension tables**, creating a structured dimensional model for reporting and analysis.

### 🔄 Data Flow

**ERP & CRM CSV Files → Bronze Layer → Silver Layer → Gold Layer → Reporting & Analysis**

---

## 📋 Project Scope

### 🏗️ Data Architecture

Design and implementation of a modern data warehouse using the **Medallion Architecture**, consisting of Bronze, Silver, and Gold layers, with each layer serving a dedicated purpose in the data pipeline.

### 🔄 ETL

Data is extracted from two CSV-based source systems, **ERP and CRM**, transformed through data-cleaning and standardization processes, and loaded into the data warehouse.

### ⭐ Data Modeling

The transformed data is organized into **fact and dimension tables** to create an analysis-ready dimensional model that supports efficient reporting and business analysis.

---

## 🛠️ Technologies Used

| Technology       | Purpose                                                            |
| ---------------- | ------------------------------------------------------------------ |
| **MySQL**        | Data warehouse development, ETL transformations, and data modeling |
| **SQL**          | Data cleaning, transformation, integration, and analysis           |
| **Git & GitHub** | Version control and project documentation                          |

---

## 🎯 Key Skills Demonstrated

* Data Warehouse Development
* ETL (Extract, Transform, Load)
* Data Cleaning & Transformation
* Data Integration
* Medallion Architecture
* Dimensional Data Modeling
* Fact & Dimension Table Design
* SQL Querying
* Data Quality Management


## 📂 Repository Structure

```text
SQL-Data-Warehouse/
│
├── 📁 datasets/
│   ├── CUST_AZ12.csv
│   ├── LOC_A101.csv
│   ├── PX_CAT_G1V2.csv
│   ├── cust_info.csv
│   ├── prd_info.csv
│   └── sales_details.csv
│
├── 📁 docs/
│   ├── Data_Archetecture.pdf
│   ├── Data_flow.pdf
│   ├── Data_integration.pdf
│   └── Data_modelling.pdf
│
├── 📁 script/
│   ├── 📁 Bronze/
│   ├── 📁 Silver/
│   ├── 📁 Golden/
│   └── DataWarehouse_initiate
│
├── 📁 test/
│
├── Data_integration.pdf
├── LICENSE
└── README.md
```

### 📁 Folder Overview

| Folder             | Description                                                                                                 |
| ------------------ | ----------------------------------------------------------------------------------------------------------- |
| **datasets/**      | Contains the source ERP and CRM CSV datasets used for the project.                                          |
| **docs/**          | Contains documentation and diagrams for the data architecture, data flow, data integration, and data model. |
| **script/Bronze/** | Contains SQL scripts for loading raw source data into the Bronze layer.                                     |
| **script/Silver/** | Contains SQL scripts for cleaning, standardizing, and transforming the data.                                |
| **script/Golden/** | Contains SQL scripts for creating analysis-ready fact and dimension tables.                                 |
| **test/**          | Contains SQL scripts used for data quality checks and validation.                                           |

