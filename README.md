# NYC Taxi - Data Engineering Project | Python, Mage ETL, GCP, BigQuery, Looker

## Introduction
This project demonstrates an end-to-end pipeline to extract, transform, load, and then visualize and analyze the NYC Taxi Trips dataset. 
Stack used: GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, Looker Studio

## Overall Architecture 
<img src="taxi_schema_architecture.jpg">

## Tech Stack Used
Programming Language - Python

Google Cloud Platform - Storage, Dashboarding
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

Data Pipeline Tool - https://www.mage.ai/

## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 
More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="taxi_data_model.jpeg">

## Pipeline

<div>
  <img src="Mage ETL Pipeline.png" alt="Mage ETL Pipeline" width="200" height="300">
  <img src="Mage ETL Pipeline v2.png" alt="Mage ETL Pipeline v2" width="600" height="300">
</div>

## Looker Dashboard
Open the dashboard [here](https://lookerstudio.google.com/reporting/c592dfcf-751f-4f86-b9a9-3ab77d0832e5).
<div>
  <img src="Looker Dashboard.png" alt="Looker Dashboard">
</div>





<!-- ## Pipeline
<img align="left" width="200" height="300" src="Mage ETL Pipeline.png">
<img align="right" width="600" height="300" src="Mage ETL Pipeline v2.png">


## Looker Dashboard
Open the dashboard [here](https://lookerstudio.google.com/reporting/c592dfcf-751f-4f86-b9a9-3ab77d0832e5).
<img src="Looker Dashboard.png"> -->
