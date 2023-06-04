# Spotify End-To-End Data Engineering Project
### Description
In this Project, I build an ETL (Extract, Transform, Load) pipeline using the Spotify API on AWS. The pipeline retrieve data from the Spotify API, transform it to a desired format, and load it into an AWS data store 

### Architecture
![Architecture Diagrame](https://github.com/LochaniAkarte/spotify-end-to-end-data-engineering-Project/blob/main/Architechture%20Diagram.png)

### About Dataset/API
This API contain Information about music artist, album and songs

### Services Used
1. **S3 (Simple Storage Service):** Amazon S3 (Simple Storage Service) is a highly scalable object storage service that can store and retrieve any amount of data from anywhere on the web, It is commonly used to store and distribute large media files, data backups, and static website files.

2. **AWS Lambda:** AWS Lambda is a serverless computing service that lets you run your code without managing servers. you can use Lambda to run code in response to events like changes in S3, DynamoDB or other AWS services.

3. **Clound Watch:** Amazon CloundWatch is a monitoring service for AWS resources and the application you run on them. you can use CloundWatch to collect and track metrics, collect and monitor log files, and set alarms.

4. **Glue Crawler:** AWS Glue Crawler is a fully managed service that automatically crawls your data sources, identifiesdata formats, and infers schemas to create an AWS Glue Data Catalog.

5. **Data Catalog:** AWS Glue Data Catalog is a fully managed metadata respository that  make it easy to discover and manage data in AWS. you can use the Glue Data Catalog with other AWS services, such as Athena.

6. **Amazon Athena:** Amazon Athena is an interactive query service that make it easy ro analyze data in Amazon S3 using standard SQL. you can use Athena to analyze data in your Glue Data Catalog pr in other S3 buckets.


