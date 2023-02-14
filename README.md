# Sleep Number - intership project introduction
This is a briefly introduction of what I did duiring my first internship at Sleep Number(2022 summer).  
I draw two diagrams to explain the structure.  

## A. Built a data automation pipeline from IoT devices to AWS
1. Used Spring Cloud, Spring Boot and Kafka to build a Data Platform capture 1 billion bio-data a day.  
2. Built a CI/CD Pipeline to process Parquet and Protocol Buffer files from Kafka using Pandas.  
3. Optimized AWS Lambda function with multiprocessing that make 30% Cost Reduction in pipeline.  
4. Exerted SQL to select and store data to DynamoDB and S3 which triggered by AWS EventBridge.  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%201.png)

## B. Wrote a script which can provisioning over 1 million IoT device in AWS
1. Implemented Flask and Python to write Scripts in Linux to build Automation which make devices registered in AWS automatically through AWS Cognito and IAM.  
2. Migrated and provisioned over 1 million devices to AWS IoT Core to collaborate with AWS services.  

### Step 1: Install Provisional Cliam
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20A.png)

### Step 2: Register Thing
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20B.png)

<h4 align="center">Make this device as a cloud resource in AWS IoT core</h4>  

### Step 3: Get Credentials
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/sleep%20number%20C.png)

<h4 align="center">Interact with other AWS resources using this Assume Role</h4>  


