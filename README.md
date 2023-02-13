# work-project-diagram
This is a briefly introduction of what I did in the Sleep Number. I draw two diagrams to explain the structure.

§	Used Spring Cloud, Spring Boot and Kafka to build a Data Platform capture 1 billion bio-data a day.
§	Built a CI/CD Pipeline to process Parquet and Protocol Buffer files from Kafka using Pandas.
§	Optimized AWS Lambda function with multiprocessing that make 30% Cost Reduction in pipeline.
§	Exerted SQL to select and store data to DynamoDB and S3 which triggered by AWS EventBridge.

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%201.png)

§	Implemented Flask and Python to write Scripts in Linux to build Automation which make devices registered in AWS automatically through AWS Cognito and IAM.
§	Migrated and provisioned over 1 million devices to AWS IoT Core to collaborate with AWS services.

# A. Install Provisional Cliam
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20A)

# B. Register Thing
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20B)

## Make this device as a cloud resource in AWS IoT core

# C. Get Credentials
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20C.png)

## Interact with other AWS resources using this Assume Role


