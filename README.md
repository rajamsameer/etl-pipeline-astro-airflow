# etl-pipeline-astro-airflow

This project demonstrates a fully automated ETL (Extract, Transform, Load) pipeline using Apache Airflow and Astronomer. The pipeline extracts weather data from **Open-Meteo.com**, transforms it using Python, and loads the processed data into a PostgreSQL database.  

## Key Features  
- **Extract**: Fetch weather data from Open-Meteo.com API.  
- **Transform**: Clean and process data using Python.  
- **Load**: Store transformed data into a PostgreSQL database.  
- **Orchestration**: Schedule and monitor tasks using Apache Airflow DAGs. 
