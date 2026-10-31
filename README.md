# CityPulse – Smart City Environmental Intelligence

## Project Overview

CityPulse is a Data Engineering project that collects, processes, stores, and analyzes air quality and weather data for five Indian cities.

Cities:
- Nagpur
- Mumbai
- Pune
- Delhi
- Bengaluru

## Project Objectives

1. Collect environmental data using public APIs.
2. Store raw API responses in the Bronze layer.
3. Clean and transform data into the Silver layer.
4. Load structured data into PostgreSQL.
5. Perform analytics using SQL.
6. Build a Flask and Plotly dashboard.
7. Automate and monitor the data pipeline.

## Data Sources

- Open-Meteo Air Quality API
- Open-Meteo Weather API

Note: Some API values may be model-based estimates or forecasts, not direct physical sensor measurements.

## Technology Stack

- Python
- Pandas
- Requests
- PostgreSQL
- SQL
- JSON, CSV, Parquet
- Flask and Plotly
- Linux
- Git and GitHub
- AWS S3, EC2 and CloudWatch (planned)
- Pytest

## Architecture

Open-Meteo APIs → Python Ingestion → Bronze → Silver → PostgreSQL → SQL Analytics → Dashboard

## Project Goal

Build an end-to-end Data Engineering project demonstrating data ingestion, transformation, storage, analytics, automation, testing, and cloud deployment.

## Development Status

Currently setting up the local development environment. Pipeline implementation is the next stage.
