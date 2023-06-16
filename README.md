# ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio
## This project is about building an end to end ETL data pipeline with Postgres database as the staging area, data is converted into Fact and Dimension Tables and loaded into Mage an open source modern data engineering data pipeline tool for transforming and integrating data, Bigquery as the data warehouse and Lockerstudio for visualization and analysis.

### GETTING STARTED
### Firstly docker volume and network was created to mount docker files of Postgres, Pgadmin and Mage.ai. The docker files were run and pandas was used to load data into the database [Note: Try using Spark SQL or Spark dataframe to load a very large set of data] Chunk by chunk. The Postgres database servers as the staging area for the dataset. 
### Staging Area
![staging-area](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/82a23ffa-dc23-4fb1-83b1-b8af3ec6015a)
### Fact and Dimension Tables
![Fact-and-dim-tables](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/eeb5654e-8950-4083-9d63-4322c342185a)

Dataset was converted into Fact and dimension tables , Merged and loaded into Mage.ai tool for transforming and integrating data.The data was further transformed with the Mage transformation tool into dictionary as key and values , then loaded into Bigquery.
### Data loaded into Mage
![pre-transformaton](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/e1077b28-e9ea-4de4-b7b0-110b7ed2bb76)
![load-data-in-mage](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/6c6d9144-2cb2-4712-a128-8ce5cde9c89c)
![load-data-into-bigquery](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/69312909-d773-469f-b2cd-4e45df9ff115)
![Mage-data-output](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/b82bbcd8-9154-4a6e-8836-7749eb096ef4)
### Further Transformation into Dictionary as Key and Value
![to-dict](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/a6b603a8-893d-412a-b0bc-dd7a520ba671)
![to-dict-2](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/a346e779-85df-40bd-b560-70ec228fbddb)
Data was loaded into BigQuery for Joins and aggregation to be used for analysis and Visualization





