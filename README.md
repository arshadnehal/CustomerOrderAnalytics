# CustomerOrderAnalytics
Developed an end to end ETL Pipeline for processing the data and calculating and storing the number of orders and amount spent by each customer.

* Utilized Azure Data Factory to trigger pipeline execution on storage events.
* Implemented Databricks Notebook with Spark code for efficient data processing and validation checks.
* Established Azure SQL DB for maintaining lookup tables and storing the result.
* Parameterized approach for dynamically reading filenames, ensuring flexibility.
* Ensured secure storage account key access through Azure Key Vault.
* Pipeline will be trigger whenever there is new file added to the ADLS Gen2.
