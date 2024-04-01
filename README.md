# Bank Transaction CO2 Analysis Project

## Overview
This repository contains the code and documentation for a CO2 data analysis project focused on bank transaction data. The project was implemented using Databricks.

## Key Features
- **Data Ingestion:** The project assumes that new bank transaction data is added to the Databricks File System (DBFS) each month. The code is designed to automatically retrieve the very last file in the DBFS directory for processing.
- **Data Cleaning:** The project begins with data cleaning tasks to ensure the accuracy and consistency of the bank transaction data.
- **Snowflake Schema:** The cleaned data is transformed into a Snowflake schema, enabling efficient querying and analysis.
- **CO2 Emission Calculation:** Using the transformed data, CO2 emissions are calculated based on transferred data.
- **Basic Visualizations:** Several basic visualizations are created to illustrate key insights and trends derived from the analyzed data.

## Technologies Used
- **Databricks:** Used as the primary platform for data processing and analysis.
- **Python:** Utilized for data cleaning, transformation, and calculation tas
