# Databricks Lakehouse Project

## Overview

This project demonstrates the development of a data lakehouse using **Databricks, PySpark, and Delta Lake**. It follows the medallion architecture to organize data into Bronze, Silver, and Gold layers, progressing from raw data ingestion to cleaned, transformed, and analytics-ready data.

The goal of this project is to apply data engineering concepts and build practical experience with modern data engineering tools and workflows.

## Architecture

The project follows the medallion architecture, consisting of three layers:

- **Bronze Layer:** Ingests raw source data and stores it in Delta tables for downstream processing.
- **Silver Layer:** Cleans, standardizes, and transforms data to improve data quality and consistency.
- **Gold Layer:** Organizes transformed data into business-ready datasets for reporting and analytics.

## Technologies Used

- **Databricks** — Cloud-based data engineering platform
- **PySpark** — Data processing and transformation using Python
- **Delta Lake** — Reliable data storage and table management
- **SQL** — Data querying and transformation, where applicable
- **Git and GitHub** — Version control and project documentation

## Data Sources

The project uses CSV source files, including CRM data, to demonstrate data ingestion, transformation, and integration across the lakehouse layers.

## Project Workflow

1. Ingest source data into the Bronze layer.
2. Store raw data in Delta tables.
3. Clean and standardize data in the Silver layer.
4. Transform and organize data in the Gold layer.
5. Prepare datasets for downstream analytics and reporting.

## Skills Demonstrated

- Data ingestion and ETL/ELT processes
- PySpark data transformations
- Medallion architecture
- Delta Lake fundamentals
- Data cleaning and standardization
- Data modeling and lakehouse design
- Git and GitHub version control

## Repository Structure

```text
.
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
├── datasets/
├── README.md
└── .gitignore
```

## Project Status

This project is being developed incrementally as I build and expand the lakehouse pipeline and apply additional data engineering concepts.
