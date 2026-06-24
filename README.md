# Delivery Route Optimizer with Real-Time Constraints

An Azure Databricks-based smart logistics system for optimizing multi-vehicle delivery routes using real-time traffic data via the Google Maps API.

## Features
- Multi-vehicle route optimization (Trucks, Vans, Cars, Motorcycles)
- Priority-based delivery classification (EXPRESS, STANDARD, ECONOMY)
- Real-time distance matrix calculation via Google Maps Distance Matrix API
- Apache Spark distributed processing on Databricks
- Interactive dashboard with Plotly visualizations
- Weight and volume constraints per vehicle type

## Tech Stack
- **Platform:** Azure Databricks / Apache Spark
- **Language:** Python (PySpark)
- **APIs:** Google Maps Directions & Distance Matrix
- **Visualization:** Plotly, Matplotlib

## Setup
1. Import the notebook into your Databricks workspace
2. Store your Google Maps API key in Databricks Secrets: Workspace → Admin → Secrets → GOOGLE_MAPS_API_KEY
3. 3. Run notebooks in order: Setup → Maps Client → Optimizer → Dashboard

## Project Structure
├── delivery_route_optimizer.ipynb   # Main Databricks notebook

├── Delivery_Route_Optimizer.pptx    # Project presentation

└── README.md

## Presentation
See `Delivery_Route_Optimizer.pptx` for system architecture, data model, and optimization logic overview.
