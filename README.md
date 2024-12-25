# Data Engineering on Microsoft Azure

This project demonstrates the implementation of a robust data pipeline on Microsoft Azure to process and analyze the Olympic dataset. It leverages Azure Data Factory, Azure Data Lake Storage Gen2, and Azure Databricks to ensure efficient data extraction, transformation, and storage.

## Overview

The pipeline performs the following key tasks:

1. **Data Extraction**: Utilized Azure Data Factory to extract the Olympic dataset from GitHub and store it in the raw folder of Azure Data Lake Storage Gen2.
2. **Data Transformation**: Mounted Azure Data Lake Storage Gen2 in Azure Databricks to perform data transformations and aggregations using PySpark, saving the results back in the transformed folder, increasing data processing efficiency by 25%.
3. **Pipeline Monitoring**: Leveraged Azure Data Factory Monitoring and Logging to track pipeline performance, identify bottlenecks, and troubleshoot issues using logs and execution history.

## Components

- **Azure Data Factory**: Designed and configured pipelines with activities like Copy Activity and Data Flow, reducing processing time by 30%. Scheduled and monitored these pipelines to ensure smooth ETL processes.
- **Azure Data Lake Storage Gen2**: Stored raw and transformed datasets for efficient management and analysis.
- **Azure Databricks**: Performed data transformations and aggregations using PySpark to enhance data processing efficiency.

## Dataset

The Olympic dataset used in this project is available at: [2021 Olympics in Tokyo Dataset](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo).

## Getting Started

### Prerequisites

- Azure account
- Azure Data Factory instance
- Azure Data Lake Storage Gen2 account
- Azure Databricks workspace

### Steps to Set Up

1. **Set Up Azure Data Lake Storage Gen2**:
   - Create a storage account and enable Data Lake Storage Gen2.
   - Organize folders for raw and transformed data.

2. **Create and Configure Azure Data Factory Pipelines**:
   - Use Azure Data Factory to extract the Olympic dataset from GitHub.
   - Configure activities like Copy Activity and Data Flow for efficient data extraction and transformation.

3. **Perform Data Transformations in Azure Databricks**:
   - Mount Azure Data Lake Storage Gen2 in Databricks.
   - Use PySpark to transform and aggregate the data, saving the results back to the transformed folder in Data Lake Storage.

4. **Monitor and Optimize Pipelines**:
   - Use Azure Data Factory’s Monitoring and Logging capabilities to ensure smooth pipeline execution and troubleshoot any issues.
