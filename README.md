# Automated-Financial-Intelligence-Platform
### Project Overview
This project implements an automated end-to-end ETL pipeline designed to ingest, transform, and visualize global exchange rate data. The system provides a robust framework for financial monitoring, leveraging modern data engineering practices to ensure data integrity, scalability, and actionable insights.

### Core Functionalities
- Automated Data Ingestion: Scheduled extraction of exchange rates for 170+ global currencies via the CurrencyFreaks REST API.

- Workflow Orchestration: Managed end-to-end data pipelines using Apache Airflow to handle task dependencies, retries, and error logging.

- Containerized Infrastructure: Deployment of the entire stack using Docker and Docker Compose for environment consistency and scalability.

- Data Modeling: Implementation of a Star Schema in PostgreSQL to optimize analytical queries and time-series trend tracking.

- Advanced Visualization: Integration with Tableau to provide executive-level dashboards for volatility analysis and market trends.

- Proactive Monitoring: Real-time execution status and data quality alerts delivered via Telegram Bot API.
