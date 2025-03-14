# Lakehouse Nexus: An Azure Data Journey

![Untitled Diagram](https://github.com/user-attachments/assets/c511f7b7-6bfb-4cd5-baf0-75aa3cacb096)


### Overview
Lakehouse Nexus is an end-to-end data pipeline built using Azure’s Medallion Architecture (Bronze, Silver, and Gold layers). This project showcases a scalable and efficient data engineering workflow that transforms raw data into meaningful insights using Azure Data Factory, Databricks, Synapse, and Power BI.

### Architecture Overview 🏗️
🔹 Bronze Layer (Raw Data Ingestion):

Data is collected from an HTTP API using Azure Data Factory (ADF).
Stored in Azure Data Lake Gen2 as raw data.
🔹 Silver Layer (Data Transformation):

Azure Databricks processes and cleans the raw data.
Transformations include data filtering, deduplication, and normalization.
Refined data is stored back into Azure Data Lake Gen2.
🔹 Gold Layer (Data Serving & Analytics):

Azure Synapse pulls transformed data from Data Lake and creates serving tables using SQL.
Data is optimized for reporting and business insights.
🔹 Reporting & Visualization:

Power BI connects to Synapse to generate interactive dashboards.
### Technology Stack 🛠️
✅ Azure Data Factory – Data ingestion from HTTP API.
✅ Azure Data Lake Gen2 – Storage for raw and transformed data.
✅ Azure Databricks – Data transformation and processing.
✅ Azure Synapse Analytics – Data warehouse and serving layer.
✅ Power BI – Visualization and reporting.
✅ SQL – Data transformation in the Gold layer.
