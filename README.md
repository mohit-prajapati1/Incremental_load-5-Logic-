#Incremental loading in Apache Spark / Databricks means loading only new or changed records instead of reprocessing the full dataset every run.
# Incremental_load-5-Logic-
This is commonly done using:  Watermark / timestamp column CDC (Change Data Capture) Merge (Upsert) with Delta Lake Auto Loader Streaming incremental ingestion
