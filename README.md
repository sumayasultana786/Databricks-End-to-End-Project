This is a healthcare project with various subsets of source data (Hospital, Patient, Group, Subgroup, Diagnosis, Insurance subscribers, etc). 

Objectives - 
1. Ingest data to Blob from local files and claims data from Cosmos for Mongo DB.
2. Clean data in Databricks notebooks using python and load them into staging area (check for null, duplicates, drop duplicates, drop irrelevant columns etc)
3. Pick cleaned data from staging area and transform it in ADF dataflow (Join, Select for various combinations)
4. Post the transformed data to Azure SQL server. 
