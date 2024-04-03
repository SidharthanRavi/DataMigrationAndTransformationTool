# DataMigrationAndTransformationTool

To extract the data from a zip file that is available at a URL and load it into Amazon S3 and Amazon RDS (NoSQL), following are the steps performed: 
Use the requests library to download the zip file from the URL.
Use the zipfile module to extract the data from the zip file.
Use the boto3 library or PySpark to store the data in Amazon S3.
Use the pandas library and sqlalchemy or PySpark to load the data from S3 into Amazon RDS (NoSQL).
