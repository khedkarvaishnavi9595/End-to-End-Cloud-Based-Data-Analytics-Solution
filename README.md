# End-to-End Cloud-Based Data Analytics Solution

## Project Overview
This project implements an automated cloud data analytics pipeline using AWS Free Tier services. The solution automates the flow of employee data from ingestion to visualization, eliminating manual reporting through serverless architecture and real-time database integration.

## Architecture
The pipeline follows a modern cloud data stack pattern:
1.  **Data Ingestion**: Raw data files are uploaded to Amazon S3.
2.  **Processing**: An S3 event trigger executes an AWS Lambda function.
3.  **Storage**: The Lambda function processes and loads the data into an Amazon RDS (MySQL) instance.
4.  **Visualization**: Power BI connects to RDS via a live connection for real-time reporting.

## Tech Stack
* **Cloud Provider**: AWS (S3, Lambda, RDS)
* **Database**: MySQL
* **Languages**: SQL, Python (Boto3 for AWS SDK)
* **BI Tool**: Power BI

## Key Features
* **Serverless ETL**: Built a fully automated ingestion workflow where AWS Lambda handles data processing without the need for managing servers.
* **Scalable Data Warehousing**: Designed an optimized MySQL schema on Amazon RDS to support high-performance analytics queries and business KPIs.
* **Automated Transformations**: Implemented SQL-based logic to clean and prepare data for downstream reporting.
* **Real-time Insights**: Established a live connection between the cloud database and Power BI, replacing traditional static reports with interactive dashboards.

## Impact and Benefits
* **Automation**: Reduced manual data entry and reporting effort by 100% through automated pipelines.
* **Data Integrity**: Minimized human error by implementing standardized processing logic within Lambda and SQL.
* **Scalability**: Leveraged cloud-native services that can scale with increasing data volumes.


