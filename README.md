# BigQuery-dbt

The structures and steps for building the data warehouse are outlined below. I use BigQuery for data storage and dbt as the transformation tool.

1. Data Sources (csv files)

↓ Extract Load

2. Data Lake (BigQuery)

↓ Load

3. Staging Layer (BigQuery)
   * See files under ae_bootcamp/models/staging

↓ Transform (dbt)

1. Dimensional Data Warehouse Layer (BigQuery)
   * See files under ae_bootcamp/models/warehouse

↓ Transform

1. Reporting Layer (OBT)
