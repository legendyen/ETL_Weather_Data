# Weather_Data_Classifier

**Part1: ETL weather data**

Extract weather forcast data from Central Weather Bureau and load into MySQL database.

**Motivation**

1. Extract- use simple API to scap weather forcast data in json fomrat.
2. Transform- use python Datetime module to transform string into datetime for fucture time interval calculation.
3. Load- define schema for database (e.g. column datatype) and use pymysql to connect to cursor.

**Data Source**

[Central Weather Bureau](https://opendata.cwb.gov.tw/dataset/forecast/F-C0032-001)

![image](https://github.com/legendyen/ETL_Weather_Data/assets/20420765/ebf2e025-0c03-46c1-ac04-72e005830142)



**Database Schema Diagram**
![image](https://github.com/legendyen/ETL_Weather_Data/assets/20420765/39a1f016-c726-46fe-8f00-cb44f8da7eb2)

**Part2: Use K-nearest neighbor to predict weather**

Predict weather by using k-nearest neighbor to perform simple classification.

**Motivation**

1. Understand the relationship between number of K neighbor and accuracy.
2. Understand the reason of test-train split for training classifier model.
3. Implement the model to predict new, unseen data.

**Result**
1. Decision boudary for k-NN model
![image](https://github.com/legendyen/Weather_Data_Classifier/assets/20420765/b438edd0-8184-4da4-863b-2eb7a0be41fb)

2. Trade-off betwenn value of k neighbor and accuracy

