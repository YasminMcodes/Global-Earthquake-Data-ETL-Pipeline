# Global-Earthquake-Data-ETL-Pipeline


This project is a Python-based ETL (Extract, Transform, Load) pipeline that collects real-time earthquake data from the USGS (United States Geological Survey) Earthquake API. It processes and filters significant earthquakes (above a defined magnitude threshold) and enriches the data with country information based on geographic coordinates.
Features

    Extracts live earthquake data from a reliable public API

    Transforms raw geojson data into a structured tabular format

    Enriches data by reverse-geocoding latitude and longitude to identify the country

    Filters significant earthquakes (e.g., magnitude ≥ 4.5)

    Saves the cleaned and enriched data to a CSV file for further analysis or reporting

Use Cases

    Geospatial data processing and enrichment

    Real-time data ingestion and transformation

    Preparing datasets for visualization, alerting systems, or analytics dashboards
