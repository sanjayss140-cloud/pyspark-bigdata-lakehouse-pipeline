# PySpark Distributed Big Data Processing Pipeline

An end-to-end Big Data Engineering pipeline built using Apache Spark (PySpark) to ingest raw, malformed transaction logs, execute structural data cleansing, and output performance-optimized cloud storage structures.

## Core Architecture Features:
- **Distributed Ingestion:** Handles large-scale incoming datasets using Spark DataFrames.
- **Data Cleansing Layer:** Filters structural anomalies (null values) and updates dirty pricing flags dynamically using optimized distributed constraints.
- **Storage Optimization:** Implements the Lakehouse architecture pattern by writing output structures to columnar compressed Parquet formats, partitioned dynamically by execution date to eliminate downstream data warehouse query costs.
- **Orchestration Modeling:** Tasks structured systematically to mirror scalable Apache Airflow workflow DAG steps.
