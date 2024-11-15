# uber-data-engineering-and-analysis

## Introduction

The goal of this project is to analyze Uber data to uncover insights on tipping patterns, trip frequency, and fare dynamics. This analysis was conducted using a variety of tools and technologies, including : GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, SQL and Looker Studio.

## Architecture 
<img src="architecture.jpg">

## Technology Used
- Programming Language - Python,SQL

Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/

## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Dataset Used : https://github.com/vikrant8988/uber-data-engineering-and-analysis/blob/main/data/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="data_model.jpeg">

## Key Insights :-

-# Uber Data Analysis



## Key Insights

- **Payment Type and Tips**: Highest average tips were made by:
  - **Cash**, followed by **Credit Card**
  
- **Top Pickup Locations (by Trip Frequency)**:
  - **International Toy Center, New York**
  - **Francis Lewis Boulevard, New York** (converted from latitude/longitude)

- **Top Passenger Counts**:
  - **1 passenger**: 65,493 trips
  - **2 passengers**: 13,709 trips

- **Average Fare by Hour**:
  - **4 AM**: $16
  - **2 PM**: $15

