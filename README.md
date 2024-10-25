Travel City Real-Time Data Streaming Pipeline
Overview
This project is a real-time data streaming pipeline designed to simulate data ingestion from multiple sources such as GPS, vehicle, traffic, and weather data. It captures travel data as it moves between cities, allowing for in-depth analysis of dynamic, location-based metrics. The pipeline is built for scalability and robustness, leveraging real-time processing tools to handle high volumes of data efficiently.

Features
Data Ingestion: Simulates ingestion of GPS, vehicle, traffic, and weather information, generating real-time travel data with longitude and latitude.
Real-Time Processing: Utilizes streaming frameworks to process and transform data on the fly, ensuring minimal latency.
Data Storage and Querying: Stores processed data in a cloud-based data lake and data warehouse, supporting both structured storage and complex SQL queries.
AWS Integration: Manages AWS services, including S3 for data storage, Glue Data Catalog for metadata management, and Redshift for data warehousing.

