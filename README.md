# Project Overview

This project demonstrates how to build a scalable, cloud-based data pipeline using **AWS Glue**, **Amazon S3**, **dbt**, and **Snowflake**. We extract data from an external API using AWS Glue, store it in S3, and then use dbt to load, model, and transform the data within Snowflake. The pipeline follows a structured multi-layer architecture—**raw**, **transform**, and **mart**—to ensure clean, reliable, and analysis-ready datasets.

## Key Features

- Automated data extraction via **AWS Glue**
- Cloud storage using **Amazon S3**
- Seamless data loading and transformation with **dbt**
- Data modeling in **Snowflake** across raw, transform, and mart layers
- Secure integration between **AWS** and **Snowflake**
- Hands-on experience with modern **ETL best practices**

## Workflow Summary

1. **Configure IAM roles** for AWS Glue and Snowflake access
2. **Extract API data** with AWS Glue and store it in Amazon S3
3. **Set up Snowflake Storage Integration** to access S3
4. **Create dbt Cloud account** via Snowflake Partner Connect
5. **Build dbt models** for raw → transform → mart layers
6. **Deploy models** to generate production-ready tables in Snowflake


## Usage Examples

- **Business Intelligence**: Query modeled data from the `mart` layer in tools like Tableau or Power BI
- **Data Validation**: Use the `transform` layer to flag missing or inconsistent records
- **Data Science**: Access structured Snowflake data in Jupyter notebooks or ML workflows
- **Auditing**: Trace business metrics back through dbt model layers to the original API source
