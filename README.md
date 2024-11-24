# Data Engineering on Microsoft Azure

This project involves the creation of a data pipeline in Azure that extracts, transforms, and analyzes Olympic data. The pipeline utilizes Azure Data Lake Storage, Azure Data Factory and Azure Databricks to ensure efficient processing and storage of the data.

* Dataset used: https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo

## Overview

The pipeline performs the following key tasks:

1. **Data Extraction**: Extract Olympic data from Azure Data Lake Storage Gen2.
2. **Data Transformations & Analysis**: Use Azure Databricks to perform comprehensive Transformations and Analysis on the Olympic dataset.
3. **Data Storage**: Store clean, structured data back in Azure Data Lake Storage for further analysis.
   
## Components

- **Azure Data Factory**: Orchestrates the data extraction and organization process.
- **Azure Data Lake Storage Gen2**: Serves as the storage solution for raw and transformed data.
- **Azure Databricks**: Handles data transformations, ensuring the dataset is clean and structured and performs Analysis.

## Getting Started

### Prerequisites

- Azure account
- Azure Data Factory instance
- Azure Data Lake Storage Gen2 account
- Azure Databricks workspace

### Steps to Set Up

1. **Set Up Azure Data Lake Storage Gen2**:
   - Create a storage account and enable Data Lake Storage Gen2.

2. **Create an Azure Data Factory Pipeline**:
   - Set up a pipeline to extract data from the Azure Data Lake Storage and organize it into raw and transformed folders.

3. **Configure Azure Databricks**:
   - Create a Databricks notebook to perform data transformations on the Olympic dataset.
   - Save the transformed data back to Azure Data Lake Storage.
