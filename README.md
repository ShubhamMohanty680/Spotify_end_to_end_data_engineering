# Spotify_End_To_End_Data_Engineering Project


### Introduction
It is a project build using ETL(Extract, Transform, Load) pipeline using Spotify API on AWS. The pipeline will retrieve data from Spotify API, transform it to a desired format, and load into AWS S3(Data Storage).

### Architecture
![Architecture Diagram](https://github.com/user-attachments/assets/504350dd-973c-4a4c-8459-d008eb0edb31)

### Services Used
1. **AWS S3(Simple Storage Service):** AWS S3 is a highly saclable object storage service used for storing and retrieving any amount of data from anywhere using web. It is commonly used to store and distribute large files.
   
2. **AWS Lambda:** AWS Lambda is a serverless computing service that lets you run code without managing servers.
   
3. **Cloud Watch:** AWS Cloudwatch is a monitoring service for AWS Resources and the applications you run on them. It is used to collect and tracks metrics, collect and monitor log files and set alarms.

4. **AWS Data Catalog:** AWS Data Catalog is a centralized metadata repository for all your data assets across various data sources. 

5. **AWS GLue Crawler:**  AWS Data Catalog consists of AWS Glue Crawler which crawls the data sources and identifies data formats, infer schemas and create AWS Glue Data Catalog.

6. **AWS Athena:**  Amazon Athena is a interactive query service that makes it easy to analyze data stored in S3 using standard SQL. It is also used to analyze stored in Glue Data Catalog.

7.  **Snowflake:** Snowflake is a cloud-based data warehouse platform that allows users to store, analyze, and exchange data securely.

8. **PowerBI:** Snowflake is a cloud-based data warehousing service that allows you to store and analyze all your data in one place. It scales independently of storage and computing, making it a flexible and cost-effective solution for businesses of all sizes.



### Dashboard
![Architecture Diagram](https://github.com/user-attachments/assets/e8b4d9e6-2fb9-4cd5-8212-2e38802198d7)



