# traffic-streaming-dashboard
# Real-Time Traffic Congestion Dashboard

A real-time data engineering project that simulates traffic data and builds a live dashboard using Azure Event Hub, Databricks, Delta Lake, and Power BI.

## Architecture
Simulated Data → Azure Event Hub → Databricks Streaming (PySpark) → ADLS (Bronze → Silver → Gold) → Power BI

## Folders
- /data-simulator
- /notebooks
- /eventhub-setup
- /powerbi-dashboard
