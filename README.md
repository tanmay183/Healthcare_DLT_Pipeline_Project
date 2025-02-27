# Healthcare_DLT_Pipeline_Project

## What is this?
This project is a **Healthcare Data Processing Pipeline** using **Databricks Delta Live Tables (DLT) and GCP** to automate and manage healthcare data ingestion and transformation.

## What do we do in it?
- Ingest raw healthcare data into **Delta Live Tables (DLT)**.
- Process and clean the data for downstream analytics.
- Load transformed data into a **target Delta table**.

## How to Run
1. Upload healthcare data to the designated source location in **DBFS**.
2. Run `feed_raw_tables.ipynb` to load and stage raw data.
3. Run `healthcare_dlt_processing.ipynb` to process and store transformed data in Delta tables.

