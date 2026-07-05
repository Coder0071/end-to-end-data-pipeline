# End-to-End Data Pipeline: Weather ETL System

An automated ETL pipeline that ingests real-time weather data from a public API, 
processes and stores it in a relational database, and surfaces insights through 
interactive dashboards.

## Architecture

OpenWeather API → Python (Extract & Transform) → MySQL (Load) → Power BI / Flask (Serve)

## Tech Stack

- **Language:** Python
- **Data Source:** OpenWeather API
- **Database:** MySQL
- **Backend:** Flask
- **Visualization:** Power BI, Chart.js
- **Scheduling:** [add: cron / Task Scheduler / Airflow — whichever you used]

## Features

- Automated extraction of live weather data via REST API calls
- Data cleaning and transformation layer (handling nulls, unit conversion, 
  timestamp normalization)
- Structured MySQL schema for historical weather data storage
- Regional dashboard built in Flask with HTML/CSS for lightweight web access
- Power BI reporting layer with a library of 60+ custom DAX measures for 
  trend analysis, anomaly detection, and regional comparisons
- Enterprise-style interactive dashboard built with Chart.js for real-time 
  visual monitoring


