# work-project-diagram
This is a briefly introduction of what I did in the Sleep Number. I draw two diagrams to explain the structure.  

1. Used Spring Cloud, Spring Boot and Kafka to build a Data Platform capture 1 billion bio-data a day.  
2. Built a CI/CD Pipeline to process Parquet and Protocol Buffer files from Kafka using Pandas.  
3. Optimized AWS Lambda function with multiprocessing that make 30% Cost Reduction in pipeline.  
4. Exerted SQL to select and store data to DynamoDB and S3 which triggered by AWS EventBridge.  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%201.png)

1. Implemented Flask and Python to write Scripts in Linux to build Automation which make devices registered in AWS automatically through AWS Cognito and IAM.  
2. Migrated and provisioned over 1 million devices to AWS IoT Core to collaborate with AWS services.  

# A. Install Provisional Cliam
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20A)

# B. Register Thing
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20B)

<h2 align="center">Make this device as a cloud resource in AWS IoT core</h2>

# C. Get Credentials
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20C.png)

<h2 align="center">Interact with other AWS resources using this Assume Role</h2>


