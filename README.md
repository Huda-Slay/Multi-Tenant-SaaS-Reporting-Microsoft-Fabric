# Multi-Tenant SaaS Reporting Platform | Microsoft Fabric

## Project Overview

This project focuses on building a metadata-driven data ingestion and processing platform using Microsoft Fabric.

The solution integrates multiple REST API endpoints, automates data ingestion using configuration-driven processing, and organises data through the Medallion Architecture.

## Technologies Used

- Microsoft Fabric
- Python
- PySpark
- REST APIs
- Delta Lake
- Fabric Lakehouse
- Fabric Data Pipelines

## Project Architecture

### 1. API Data Ingestion
- Integrated multiple REST API endpoints.
- Used configuration-driven API endpoint management.
- Implemented API-based data extraction using Python.

### 2. Bronze Layer
- Ingested and stored raw API responses.
- Maintained source data in the Bronze layer.
- Used Delta Lake for data storage.

### 3. Silver Layer
- Processed and cleaned raw data using PySpark.
- Applied duplicate removal and data transformation.
- Stored structured data as Delta tables.

### 4. Gold Layer
- Organised processed data for analytical consumption.
- Prepared refined datasets for downstream reporting.

## Key Engineering Concepts

- Metadata-driven data ingestion
- REST API integration
- Python-based ETL
- PySpark transformations
- Medallion Architecture
- Delta Lake
- Data Pipeline orchestration

## Project Workflow

1. Configure API endpoints and metadata.
2. Extract data from multiple REST APIs using Python.
3. Ingest raw data into the Bronze layer.
4. Clean and transform data using PySpark.
5. Store processed data in the Silver layer.
6. Prepare refined datasets in the Gold layer.

## Repository Structure

```text
Multi-Tenant-SaaS-Reporting/
│
├── README.md
├── notebooks/
├── pipeline/
├── data/
└── screenshots/
```

## Key Learnings

- Working with REST API integrations.
- Building metadata-driven ingestion workflows.
- Performing ETL operations using Python and PySpark.
- Implementing Medallion Architecture in Microsoft Fabric.
- Working with Delta Lake and Lakehouse storage.
- Understanding automated data pipeline workflows.

---

**Project Domain:** Data Engineering  
**Platform:** Microsoft Fabric  
**Focus:** Python | PySpark | REST APIs | Delta Lake | ETL | Data Pipelines
