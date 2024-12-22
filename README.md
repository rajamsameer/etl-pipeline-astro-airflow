# ETL Pipeline with Astro and Apache Airflow  

This project demonstrates a fully automated ETL (Extract, Transform, Load) pipeline using Apache Airflow and Astronomer. The pipeline extracts weather data from **Open-Meteo.com**, transforms it using Python, and loads the processed data into a PostgreSQL database. This project is based on a tutorial by YouTuber **Krish Naik**.  

## Key Features  
- **Extract**: Fetch weather data from Open-Meteo.com API.  
- **Transform**: Clean and process data using Python.  
- **Load**: Store transformed data into a PostgreSQL database.  
- **Orchestration**: Schedule and monitor tasks using Apache Airflow DAGs.  

## About Astronomer  
[Astronomer](https://www.astronomer.io/) is a modern platform for deploying, monitoring, and scaling Apache Airflow workflows. It simplifies the setup of Airflow environments, enabling seamless local development, testing, and cloud deployments. This project uses Astronomer to manage the Airflow instance, ensuring an efficient and scalable ETL pipeline.  

## Project Structure  
- `dags/`: Contains Airflow DAGs for the ETL pipeline.  
- `plugins/`: Custom operators and helpers for Airflow.  
- `data/`: Sample datasets used in the pipeline.  
- `docker-compose.yaml`: Local environment setup for Airflow.  

## Prerequisites  
- Python 3.x  
- Docker and Docker Compose  
- Astronomer CLI (for deploying Airflow)  

## Usage  
- Run the pipeline by triggering the DAG from the Airflow UI.  
- Monitor progress and logs in the Airflow UI.    

## Tutorial  
This project is based on a tutorial by **Krish Naik**, a popular YouTuber known for his data science and machine learning tutorials. Check out his YouTube channel for more tutorials: [Krish Naik YouTube Channel](https://www.youtube.com/c/KrishNaik).  

## Contact  
For questions or suggestions, contact [rajamsameer423@gmail.com].  
