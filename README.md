# SQL Data Warehouse Project Using Medallion Architecture
This project uses SQL to build a modern data warehouse including choosing & designing data architecture, ETL, modelling and Analytics.

# Building Data Warehouse (Data Engineering)

## Data warehouse specifications

Developed a modern data warehouse using SQL Server to consolidate sales data enabling analytical reporting and informed decision making.
Specifications\
•	Data Sources: Imports data from two source systems (ERP and CRM) provided as CSV files.\
•	Data Quality: Cleansing and data quality issues are resolved prior to analysis\
•	Integration: sources are combined into a single, user-friendly data model designed for analytical queries.\
•	Scope: Focus is on the latest dataset only; Historization of data is not required\
•	Documentation: Provides clear documentation of the data model to support both business stakeholders and analytics team.

## Tech stack

- SQL
- SQL server management studio(SSMS)
- SQL server express
- Notion
- DRAWIO


## Project Architecture

![Architecure](./docs/data_architecture.png)

**Bronze Layer:** Stores raw data as-is from the source systems. Data is sourced from CSV Files into SQL Server Database.

**Silver Layer:** This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.

**Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.
