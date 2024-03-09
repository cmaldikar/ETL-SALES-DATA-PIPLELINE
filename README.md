# ETL-SALES-DATA-PIPELINE

This project implements an end-to-end data pipeline on Microsoft Azure to extract sales data from an on-premise SQL Server, transform it using Azure Databricks, and load the clean data into Azure Synapse Analytics. Power BI reports are then created to visualize various Key Performance Indicators (KPIs) derived from the data in Azure Synapse Analytics.

## Overview

The ETL-SALES-DATA-PIPELINE project comprises the following main components:

### Data Extraction:

- Data is extracted from the on-premise SQL Server using Azure Data Factory (ADF).
- Extracted data is stored in Azure Blob Storage for further processing.

### Data Transformation:

- Azure Databricks is used to transform the raw data.
- Data is cleaned, aggregated, and enriched as necessary to prepare it for analytics.

### Data Loading:

- Cleaned and transformed data is loaded into Azure Synapse Analytics.
- Data is organized into appropriate tables and schemas for efficient querying.

### Reporting:

- Power BI reports are created on top of the data in Azure Synapse Analytics.
- Reports visualize various KPIs, such as sales performance, trends, and forecasts.

## Architecture

![Architecture Diagram](/DE-Architecture.png)

## Setup Instructions

To set up and run the ETL-SALES-DATA-PIPELINE project, follow these steps:

### Azure Resources Setup:

- Set up Azure Blob Storage, Azure Data Factory, Azure Databricks, and Azure Synapse Analytics in your Azure subscription.
- Configure access permissions and credentials for each Azure service as required.

### Data Extraction:

- Configure Azure Data Factory to connect to the on-premise SQL Server and extract the required data.
- Define pipelines and activities to orchestrate the data extraction process.

### Data Transformation:

- Set up an Azure Databricks workspace.
- Develop and execute notebooks in Azure Databricks to transform the extracted data.
- Ensure that the transformed data meets the desired quality and structure.

### Data Loading:

- Create tables in Azure Synapse Analytics to store the transformed data.
- Use Azure Data Factory to load the cleaned data from Azure Blob Storage into Azure Synapse Analytics tables.

### Reporting:

- Develop Power BI reports based on the data available in Azure Synapse Analytics.
- Design visualizations and dashboards to showcase the relevant KPIs and insights.

### Monitoring and Maintenance:

- Monitor the data pipeline for any issues or bottlenecks.
- Schedule regular maintenance tasks, such as data refreshes and system updates.

## Visualization

![Sales Data Visualization](/POWERBI/SALES%20DATA%20DASHBOARD.jpg)
