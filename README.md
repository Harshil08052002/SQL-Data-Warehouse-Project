# Data Warehouse and Analytics Project 

Welcome to the **Data Warehouse and Analytics Project** Repository!
This project demonstrates a comprehansice data are houseing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

**Data Architecture**
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold Layers:
![image alt](https://github.com/Harshil08052002/SQL-Data-Warehouse-Project/blob/c4b83fac7f083a8a12be0c2fe2272c913d15d22b/DWH%20Project%20Diagram.jpg)
1. Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.


---

## Project Overview
This project involve
1. Data Architecture: Designing a Modern Warehouse using Medallion Aechitecture Bronze, Silver, and Gold Layer.
2. ELT Pipeline: Extracting, transforming, and Loading data from source system into the warehouse.
3. Data Modeling: Developing fact and dimension tables optimized for analytical queries.
4. Analyticas & Reporting: Creating SQL-based reports and dashboards for actionable insights. 

---

## 🚀Project Requirments

### Building the Data Warehouse (Data Engineering)

### objective
Develop a modern data warehouse usinf SQL server to consolidate sales data, enabling analytical reporting and informed decision-making.

### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
-**Data Quality**: Cleanse and resolve data quality issues prior to analysis.
-**Integration**: Combine both sources into a single, user-friendy data model designed for analytical queries.
-**Scope**: Focus on the latest dataset only; historization of data is not required. 
-**Documentation**: Provided clear documentation on the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
-**Product Performance**
-**Sales Trends** 

These insights empower stakeholders with key business metrics, enabling strategic decision-making. 


## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---








