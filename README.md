# Azure-Synapse-Analytics
# NYC Taxi Insights: Scalable Data Analytics with Azure Synapse

## Project Overview
This project leverages **Azure Synapse Analytics** to process, analyze, and report on New York City Taxi trip data. The goal is to create a scalable data engineering solution that integrates various Azure services for ETL (Extract, Transform, Load) processes, allowing for efficient data analysis and visualization. The project provides insights into taxi trip patterns, payment behaviors, and demand distribution across boroughs and time.

## Key Features
- **Data Ingestion**: Ingest NYC taxi trip data from Azure Data Lake Storage Gen2.
- **Data Transformation**: Process and transform data using Azure Synapse SQL Pools and Spark Pools.
- **External Tables**: Create external tables for raw and aggregated data layers (bronze, silver, and gold).
- **Data Quality Checks**: Perform validations on critical fields such as `LocationID` and `total_amount` to ensure data integrity.
- **Data Analysis**: Analyze taxi trip duration, payment types, and geographic distribution by borough.
- **Campaign Targeting**: Provide data insights to support marketing campaigns based on payment behavior and demand trends.
- **Visualization**: Integrate with Power BI for interactive data reporting and insights.


## Technologies Used
- **Azure Synapse Analytics**: Dedicated SQL Pools, Serverless SQL Pools, Spark Pools.
- **Azure Data Lake Storage Gen2**: Scalable storage for raw and processed data.
- **Power BI**: For visualization and reporting.
- **Parquet**: Data format for efficient storage and processing.
