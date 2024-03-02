# ETL-SALES-DATA-PIPELINE

This project implements an end-to-end data pipeline on Microsoft Azure to extract sales data from an on-premise SQL Server, transform it using Azure Databricks, and load the clean data into Azure Synapse Analytics. Power BI reports are then created to visualize various Key Performance Indicators (KPIs) derived from the data in Azure Synapse Analytics.

## Overview

The ETL-SALES-DATA-PIPELINE project comprises the following main components:

1. **Data Extraction**: 
   - Data is extracted from the on-premise SQL Server using Azure Data Factory (ADF).
   - Extracted data is stored in Azure Blob Storage for further processing.

2. **Data Transformation**:
   - Azure Databricks is used to transform the raw data.
   - Data is cleaned, aggregated, and enriched as necessary to prepare it for analytics.

3. **Data Loading**:
   - Cleaned and transformed data is loaded into Azure Synapse Analytics (formerly known as Azure SQL Data Warehouse).
   - Data is organized into appropriate tables and schemas for efficient querying.

4. **Reporting**:
   - Power BI reports are created on top of the data in Azure Synapse Analytics.
   - Reports visualize various KPIs, such as sales performance, trends, and forecasts.

## Setup Instructions

To set up and run the ETL-SALES-DATA-PIPELINE project, follow these steps:

1. **Azure Resources Setup**:
   - Set up Azure Blob Storage, Azure Data Factory, Azure Databricks, and Azure Synapse Analytics in your Azure subscription.
   - Configure access permissions and credentials for each Azure service as required.

2. **Data Extraction**:
   - Configure Azure Data Factory to connect to the on-premise SQL Server and extract the required data.
   - Define pipelines and activities to orchestrate the data extraction process.

3. **Data Transformation**:
   - Set up an Azure Databricks workspace.
   - Develop and execute notebooks in Azure Databricks to transform the extracted data.
   - Ensure that the transformed data meets the desired quality and structure.

4. **Data Loading**:
   - Create tables in Azure Synapse Analytics to store the transformed data.
   - Use Azure Data Factory to load the cleaned data from Azure Blob Storage into Azure Synapse Analytics tables.

5. **Reporting**:
   - Develop Power BI reports based on the data available in Azure Synapse Analytics.
   - Design visualizations and dashboards to showcase the relevant KPIs and insights.

6. **Monitoring and Maintenance**:
   - Monitor the data pipeline for any issues or bottlenecks.
   - Schedule regular maintenance tasks, such as data refreshes and system updates.

## Contributors

- [Your Name](https://github.com/yourusername)

