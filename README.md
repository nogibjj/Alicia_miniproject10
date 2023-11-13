# PySpark Data Processing
The project utilize PySpark for ETL on a big dataset. The main objectives are to incorporate a Spark SQL query and execute a data transformation. I use cereal's dataset to peform these operatons.
## Format code
Format code: `make format`
Lint code: `make lint`
Test code: `make test`
## Process
1. extract the dataset via `extract`
2. start a spark session via `start_spark`
3. load the dataset via `load_data`
4. find some descriptive statistics via `descibe`
5. query the dataset via `query`
6. do some more transformation on the sample dataset via `example_transform`
7. finally end spark session via `end_spark`
## git action passed
![image](<Screenshot 2023-11-12 at 9.28.13 PM.png>)
## Spark log
![image](<Screenshot 2023-11-12 at 9.30.01 PM.png>)