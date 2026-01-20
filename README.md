# Sql_Dwh_Project
Building a modern DWH with SQL Server, including ETL processes, Data Modelling &amp; Analytics

# Data Warehouse and Analytics Project
Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

# 🏗️ Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: Data Architecture

<img width="828" height="425" alt="image" src="https://github.com/user-attachments/assets/cbc7f35c-44e6-4618-8e9f-faa92bca53ca" />

  **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
  
  **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
  
  **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

# 📖 Project Overview
### This project involves:

**Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
**ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
**Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
**Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.


# 🚀 Project Requirements
### Building the Data Warehouse (Data Engineering)
#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

### Specifications
**Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files. <br>
**Data Quality**: Cleanse and resolve data quality issues prior to analysis.<br>
**Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.<br>
**Scope**: Focus on the latest dataset only; historization of data is not required.<br>
**Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.<br>
**BI**: Analytics & Reporting (Data Analysis)

## Objective
Develop SQL-based analytics to deliver detailed insights into:

Customer Behavior
Product Performance
Sales Trends
These insights empower stakeholders with key business metrics, enabling strategic decision-making.


## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                      # Raw source data (ERP and CRM datasets)
│
├── docs/                          # Project documentation and architecture artifacts
│   ├── etl.drawio                 # ETL techniques and processing methods (Draw.io)
│   ├── data_architecture.drawio   # Overall data architecture diagram
│   ├── data_catalog.md            # Dataset catalog with fields, descriptions, and metadata
│   ├── data_flow.drawio           # End-to-end data flow diagram
│   ├── data_models.drawio         # Dimensional data models (Star Schema)
│   └── naming-conventions.md      # Naming standards for tables, columns, and files
│
├── scripts/                       # SQL scripts for ETL pipelines and transformations
│   ├── bronze/                    # Raw data ingestion and landing layer
│   ├── silver/                    # Data cleansing, standardization, and transformation
│   └── gold/                      # Curated analytical models and business-ready views
│
├── tests/                         # Data quality checks and validation scripts
│
├── README.md                      # Project overview, setup instructions, and usage guide
├── LICENSE                        # Repository license
├── .gitignore                     # Files and directories excluded from version control
└── requirements.txt               # Project dependencies and environment requirements
