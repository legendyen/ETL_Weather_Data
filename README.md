# ETL_Weather_Data

**Project Description**

Extract weather forcast data from Central Weather Bureau and load into MySQL database.

**Motivation**

1. Extract- use simple API to scap weather forcast data in json fomrat.
2. Transform- use python Datetime module to transform string into datetime for fucture time interval calculation.
3. Load- define schema for database (e.g. column datatype) and use pymysql to connect to cursor.

**Data Source**

[Central Weather Bureau](https://www.cwb.gov.tw/eng/)

![image](https://github.com/legendyen/ETL_Weather_Data/assets/20420765/ebf2e025-0c03-46c1-ac04-72e005830142)



**Database Schema Diagram**
![image](https://github.com/legendyen/ETL_Weather_Data/assets/20420765/39a1f016-c726-46fe-8f00-cb44f8da7eb2)
