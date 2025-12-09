# Azure Retail Batch Pipeline

This repository contains an end-to-end Azure batch data engineering project for an e-commerce / retail scenario.

## Technologies

- Azure Data Factory
- Azure Databricks
- Azure Data Lake Storage Gen2
- Azure Synapse Analytics (Serverless SQL)
- Delta Lake

## Project overview

- Ingest daily e-commerce orders, customers, and products data into Azure Data Lake.
- Transform data using a medallion architecture (Bronze, Silver, Gold) in Databricks.
- Implement SCD Type 2 for the customer dimension using Delta Lake.
- Expose curated data to Synapse Serverless SQL for analytics.

More details coming soon.

