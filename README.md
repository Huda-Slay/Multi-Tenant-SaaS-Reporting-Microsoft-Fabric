# Multi-Tenant SaaS Reporting Platform | Microsoft Fabric

## Project Overview

This project focuses on building a metadata-driven data engineering and reporting platform using Microsoft Fabric.

The solution integrates data from REST APIs, processes it through a structured data pipeline, and organises it using the Medallion Architecture. The processed data is prepared for analytics and reporting.

## Technologies Used

- Microsoft Fabric
- Python
- PySpark
- SQL
- REST APIs
- Delta Lake
- Fabric Lakehouse
- Data Pipelines
- Power BI

## Project Architecture

The project follows a metadata-driven approach and Medallion Architecture.

### 1. Data Ingestion
- Ingests data from REST API endpoints.
- Uses configuration-driven API endpoint management.
- Supports structured data ingestion into Microsoft Fabric.

### 2. Bronze Layer
- Stores ingested raw data.
- Maintains the initial version of source data.
- Uses Delta Lake storage.

### 3. Silver Layer
- Performs data cleaning and transformation using PySpark.
- Handles duplicate records and data quality operations.
- Stores structured and processed data.

### 4. Gold Layer
- Prepares transformed data for analytical use.
- Organises data for reporting and business insights.

## Key Engineering Concepts

- Metadata-driven data ingestion
- REST API integration
- Medallion Architecture
- PySpark transformations
- Delta Lake tables
- Data pipeline orchestration
- SQL-based analytics
- Power BI reporting

## Project Workflow

1. Configure API endpoints and ingestion metadata.
2. Extract data from REST APIs.
3. Load raw data into the Bronze layer.
4. Clean and transform data in the Silver layer.
5. Prepare analytical datasets in the Gold layer.
6. Use the processed data for reporting and analytics.


## Key Learnings

- Building metadata-driven data pipelines.
- Integrating REST APIs with Microsoft Fabric.
- Working with PySpark and Delta Lake.
- Implementing Medallion Architecture.
- Understanding scalable data ingestion and transformation.
- Preparing data for analytics and reporting.

---

**Project Domain:** Data Engineering  
**Platform:** Microsoft Fabric  
**Focus:** REST APIs | Python | PySpark | SQL | Delta Lake | Data Pipelines | Power BI
