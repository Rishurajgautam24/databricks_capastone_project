# Capstone Project: Real-time Crime Rate Prediction and Analysis
Project Overview
 - Participants will build a real-time analytics pipeline to predict and analyze crime rates in major cities using historical crime data. The project will leverage Databricks for data processing, Spark for real-time streaming, Databricks SQL for analytics, and MLflow for machine learning model management.
   Data Source
   - Dataset: Use the "US Crime Rates" dataset available from the City of Chicago's
   - Data Portal. This dataset includes details such as the date, type of crime, location,
and arrest records.
  - Additional Data: Weather data from the NOAA which can be used to analyze the
impact of weather conditions on crime rates.
# Key Phases of the Project
- Data Ingestion and Storage
- Ingest real-time and historical crime data using Databricks Auto-loader.
- Store data in Delta Lake to leverage ACID transactions and efficient data querying.
 
2. Data Processing and Transformation
- Cleanse and preprocess data using PySpark.
- Develop a Bronze/Silver/Gold layer architecture for processed data.
- Implement streaming data pipelines to ingest real-time crime data.
3. Analytics and Business Intelligence
- Use Databricks SQL to create queries and dashboards for analyzing crime trends and patterns.
- Integrate external tools for enhanced visualization (e.g., Tableau or PowerBI embedded in Databricks notebooks).
