# ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio
## This project is about building an end to end ETL data pipeline with Postgres database as the staging area, data is converted into Fact and Dimension Tables and loaded into Mage an open source modern data engineering data pipeline tool for transforming and integrating data, Bigquery as the data warehouse and Lockerstudio for visualization and analysis.

### GETTING STARTED
### Firstly docker volume and network was created to mount docker files of Postgres, Pgadmin and Mage.ai. The docker files were run and pandas was used to load data into the database [Note: Try using Spark SQL or Spark dataframe to load a very large set of data] Chunk by chunk. The Postgres database servers as the staging area for the dataset. 
### Staging Area
![staging-area](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/82a23ffa-dc23-4fb1-83b1-b8af3ec6015a)

Dataset was converted into Fact and dimension tables , Merged and loaded into Mage.ai tool for transforming and integrating data.
### Data loaded into Mage
![pre-transformaton](https://github.com/liltims77/ETL-Data-Pipeline-with-PostgresDB-Mage-Bigquery-and-Lockerstudio/assets/41475769/e1077b28-e9ea-4de4-b7b0-110b7ed2bb76)




