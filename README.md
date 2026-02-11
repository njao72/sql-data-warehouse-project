# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a porfolio project highlights industry best practices is data engineering and analytics

---
## 🚀 Project Requirements

### Building the Data Warehouse(Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision making

#### Specifications
- **Data Sources** :Import data from two source systems (ERP and CRM) provided as CSV files
- **Data Quality** :Cleanse and resolve data quality issues prior to analysis
- **Integration** :Combine both sources inyo a single, user-friendly data model designed for analytical queries
-  **Scope** : Focus on the latest dataset only; historizattion of data is not required
-   **Documentaion** : Provide clear documentation to the data model to support both business stakeholders and analytics teams

---------------------

## Data Architechture
The data architechture follows the medallion heirachy which includes bronze,silver and gold layer
----<img width="1291" height="821" alt="ETL flow diagram" src="https://github.com/user-attachments/assets/6a30224b-0fc1-41d7-b6b7-d83d63809285" />
1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

### BI: Analytics & Reporting(Data Analytics)

#### Objective
Develop SQL-based analytics to deliver insights into:
- **Customer Behaviour**
-  **Product Performance**
-  **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making

---

##### 📌 About Me

Hi, I’m James Njao, a Data Science student at Strathmore University with a strong interest in data analytics and data warehousing. This repository focuses on building and working with SQL-based data warehouse solutions to support efficient data storage, transformation, and analytical querying for data-driven decision-making.




