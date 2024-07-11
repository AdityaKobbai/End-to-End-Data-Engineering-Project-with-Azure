# End-to-End Data Engineering Project with Azure

## Azure Data Pipeline Project

This project demonstrates the end-to-end data pipelining process using various Azure services, including Azure Data Factory, Azure Databricks, Azure Data Lake Storage Gen2, and Azure Synapse Analytics. The purpose of this project is to showcase the ability to handle the entire data pipelining ecosystem effectively.

## Project Overview

The project involves the following steps:
1. **Creation of Storage Account and Resource Group**: Setting up the necessary Azure resources to store and process data.
2. **Data Ingestion**: Pulling data from HTTP data sources into Azure Data Factory.
3. **Data Organization**: Creating two folders (`raw_data` and `transformed_data`) in Azure Data Lake Storage Gen2.
4. **Data Loading**: Loading raw data into the `raw_data` folder.
5. **Data Transformation**: Using Azure Databricks with the PySpark framework to transform the data.
6. **Storing Transformed Data**: Loading the transformed data into the `transformed_data` folder.
7. **Exploratory Data Analysis (EDA)**: Loading the transformed data into Azure Synapse Analytics for EDA.

<img width="734" alt="Screenshot 2024-07-10 at 5 42 43 PM" src="https://github.com/AdityaKobbai/End-to-End-Data-Engineering-Project-with-Azure/assets/47831290/43e09ce1-a3c7-41fc-8281-43c051107213">

<img width="1273" alt="resources_all" src="https://github.com/AdityaKobbai/End-to-End-Data-Engineering-Project-with-Azure/assets/47831290/1afce7ea-b3a1-4c7c-95be-8c5787c45696">


By executing these steps, the project aims to demonstrate the comprehensive handling of a data pipeline using Azure services.

## Project Steps in Detail

### 1. Creation of Storage Account and Resource Group
- Set up a storage account and a resource group in Azure.
- Create containers to store the data.
<img width="1280" alt="Container1" src="https://github.com/AdityaKobbai/End-to-End-Data-Engineering-Project-with-Azure/assets/47831290/f2209133-8378-46c4-bea3-99922056f5e7">

### 2. Data Ingestion
- Use Azure Data Factory to pull data from HTTP data sources.
- Store the ingested data in the `raw_data` folder in Azure Data Lake Storage Gen2.

### 3. Data Organization
- Create two folders in the storage container: `raw_data` and `transformed_data`.
- Ensure the raw data is correctly placed in the `raw_data` folder.

<img width="1269" alt="Container" src="https://github.com/AdityaKobbai/End-to-End-Data-Engineering-Project-with-Azure/assets/47831290/36f6d2eb-5121-46c7-88f4-015b7eda48d9">

### 4. Data Loading
- Load the raw data into the `raw_data` folder in Azure Data Lake Storage Gen2.

### 5. Data Transformation
- Utilize Azure Databricks and PySpark to transform the raw data.
- The transformation steps are outlined in the provided Jupyter Notebook (`transformation.ipynb`).

<img width="1269" alt="tranformer_data" src="https://github.com/AdityaKobbai/End-to-End-Data-Engineering-Project-with-Azure/assets/47831290/737fe6c9-4e6c-4b59-858c-d2f5e87b6c5a">

### 6. Storing Transformed Data
- Load the transformed data into the `transformed_data` folder in the storage container.

### 7. Exploratory Data Analysis (EDA)
- Use Azure Synapse Analytics to perform EDA on the transformed data.
- Analyze the data to gain insights and validate the transformation process.

## Project Files

- **transformation.ipynb**: Jupyter Notebook containing the PySpark code used for data transformation.

## Conclusion

This project highlights the capability to manage an entire data pipeline using Azure services. Each step, from data ingestion to transformation and analysis, is designed to demonstrate proficiency in handling complex data workflows in a cloud environment.
