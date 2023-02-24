# Intership projects  

### The Commons XR -> [jump](#jump1)  
### Sleep Number -> [jump](#jump2)  

<span id="jump1"></span>
# 1. The Commons XR :: 01/2023 - current
This is a briefly introduction of what I did duiring my second internship at The Commons XR (2023 spring).  
I drawn some diagrams to explain my results.  

## A. Used server-side-rendering to improving website performance
▪ Created React components in Typescript with Chakra UI based on Figma design from UI/UX team.  
▪ Utilized Next and Node to do some Server-Side Rendering to improve almost 50% performance.  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/CSR.png)
<h4 align="center">Client side rendering make FCP faster but FMP is slow</h4>  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/SSR.png)
<h4 align="center">Server side rendering make FMP & TTI faster but FCP is slow</h4>  

## B. Implemented express-seesion to record users
▪ Used express-session and Redis to track users, rewrite URL to pass session ID if cookie is disabled.

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/login.png)
<h4 align="center">When user login, store session in Redis</h4>  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/call.png)
<h4 align="center">When check whether user is loged, check sessionID in Redis</h4>  

## C. Set a secure enviroment for development in Azure
▪ Managed codes in Azure DevOps to work with others and analyze data by Azure Synapse Analytics.

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/azure.png)  

<span id="jump2"></span>
# 2. Sleep Number :: 05/2022 - 08/2022
This is a briefly introduction of what I did duiring my first internship at Sleep Number(2022 summer).  
I drawn two diagrams to explain my results.  

## A. Built a data automation pipeline from IoT devices to AWS
▪ Used Spring Cloud and Kafka to build a Data Platform capture 1 billion bio-data a day.  
▪ Built a CI/CD Pipeline to process Parquet and Protocol Buffer files from Kafka using Pandas.  
▪ Optimized AWS Lambda function with multiprocessing that make 30% Cost Reduction in pipeline.  
▪ Exerted SQL to select and store data to DynamoDB and S3 which triggered by AWS EventBridge.  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/SN/sleep-number-df.png)

## B. Wrote a script which can provisioning over 1 million IoT device in AWS
▪ Implemented Flask and Python to write Scripts in Linux to build Automation which make devices registered in AWS automatically through AWS Cognito and IAM.  
▪ Migrated and provisioned over 1 million devices to AWS IoT Core to collaborate with AWS services.  

### Step 1: Install Provisional Cliam
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/SN/sleep%20number%20A.png)

### Step 2: Register Thing
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/SN/sleep%20number%20B.png)

<h4 align="center">Make this device as a cloud resource in AWS IoT core</h4>  

### Step 3: Get Credentials
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/SN/sleep%20number%20C.png)

<h4 align="center">Interact with other AWS resources using this Assume Role</h4>  


