# Uber Data Analytics | Modern Data Engineering with GCP

## Overview
This project showcases a modern data engineering pipeline for analyzing Uber trip data using tools from the Google Cloud Platform (GCP). By integrating Mage.ai for pipeline orchestration, BigQuery for warehousing, Looker Studio for dashboarding, and Cloud Storage for staging data, the project demonstrates a scalable and cloud-native approach to real-time analytics.

## Goals
- Build a modern ETL pipeline using Mage.ai for seamless data movement.
- Transform and load data into BigQuery for efficient querying and analysis.
- Leverage Looker Studio to visualize trip trends and business metrics.
- Use GCP Cloud Storage to manage raw and processed data throughout the pipeline.
- Deploy on GCP Compute Engine to simulate production-like pipeline orchestration.

## Tech & Services Used
- Mage.ai – Modern, open-source tool for building and managing data pipelines.
- Python – Used to extract, transform, and load data.
- SQL – Used for querying and transformations in BigQuery.
- Google Cloud Platform (GCP)
- BigQuery – Data warehousing and analytics engine.
- Cloud Storage – Cloud-based object storage.
- Compute Engine – Virtual machine hosting for pipeline execution.
- Looker Studio – Visualization and dashboarding tool for business insights.

## Dataset
The dataset comes from the NYC Taxi & Limousine Commission (TLC) and contains detailed trip records for yellow and green taxis. It includes pickup and drop-off timestamps, trip distances, fare components, rate types, payment methods, and passenger counts. This rich dataset allows for time-series analysis, geospatial insights, and demand pattern exploration across New York City.

Link: https://github.com/darshilparmar/uber-data-engineering-mage-project/blob/main/data/uber_data.csv

## Data Model
![image](https://github.com/user-attachments/assets/82694234-5a7c-49fd-8fe6-0d2733a8c06c)

## Project Architecture
![image](https://github.com/user-attachments/assets/8abb8bff-0865-40d3-be72-a81647f7e800)


