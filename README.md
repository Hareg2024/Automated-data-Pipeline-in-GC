# Automated-data-Pipeline-in-GC
The purpose of this project is to demonstrate a simple technique to creating an automated data pipeline to load data from a local drive or a Google Cloud bucket into Bigquery for further analysis.This repository provides a step-by-step strategy. In addition, the code and dashboard are included.    

# Overview: 
## Tech: Python, Google  cloud storage, Google cloud Functions, BigQuery , Looker 
Web Portal: Built with Python Flask to allow users to upload sales data files.
Storage: Uploaded files are stored in a GCS bucket.
Cloud Function: Automatically triggered when a file is uploaded to the GCS bucket, extracts data from the file, and loads it into BigQuery.
ETL Process: Extract, Transform, Load process implemented to handle data from raw upload to processed state.
Reporting: Summary views and dashboards in Looker Studio for key metrics, with filtering and drill-down capabilities.
![image](https://github.com/user-attachments/assets/42b88f6c-b0ac-417c-9fd3-0419021ea1c4)

