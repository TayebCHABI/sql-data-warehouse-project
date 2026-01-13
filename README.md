# Data Warehouse and Analytics Project
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights.

# Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:

<img width="1544" height="797" alt="data_architecture" src="https://github.com/user-attachments/assets/79d42746-332b-4c4c-b37d-6e787dac8d9d" />

**Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.

**Silver Layer:** This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.

**Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.

This project involves:

**Data Architecture:** Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.

**ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.

**Data Modeling:** Developing fact and dimension tables optimized for analytical queries.

**Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.
