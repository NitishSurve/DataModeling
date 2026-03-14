# DataModeling
Experimenting with Data Modeling

📊 Data Modeling Pipeline (Medallion Architecture)

This project implements a data transformation pipeline using the Medallion Architecture: Bronze → Silver → Gold. It processes raw transactional data and gradually transforms it into clean, structured, and analytics-ready datasets.

🏗️ Architecture
Source → Bronze → Silver → Gold
                ↓
              SCDs
🔹 Layers

📥 Source
Raw operational data containing order, customer, and product information.

🥉 Bronze
Stores raw ingested data with minimal transformations for traceability.

🥈 Silver
Applies data cleaning, deduplication, and standardization to produce reliable datasets.

🥇 Gold
Creates business-ready tables and aggregations optimized for analytics and reporting.

🕒 SCDs (Slowly Changing Dimensions)
Tracks historical changes in dimension data (e.g., customer or product updates).

⚙️ Concepts Demonstrated

Data warehouse modeling

Medallion architecture

Data transformation pipelines

Slowly Changing Dimensions (SCD)

SQL-based data processing
