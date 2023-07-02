# Sleep Number, San Jose, CA
05/2022 - 08/2022<br />
_Software Engineer Intern_

This is a briefly introduction of what I did duiring my first internship at Sleep Number(2022 summer).  
I drawn two diagrams to explain my results.  

![image](https://github.com/TotallyNewGuy/sn-intern-project/blob/main/SN/sn.png)  

### [A. Built a data automation pipeline from IoT devices to AWS](#jump1)  
### [B. Wrote a script which can provisioning over 1 million IoT device in AWS](#jump2)  
#### [Step1. Install Provisional Cliam](#jump3)  
#### [Step2. Register Thing](#jump4)  
#### [Step3. Get Credentials](#jump5)  

<span id="jump1"></span>
## A. Built a data automation pipeline from IoT devices to AWS
▪ Used Spring Cloud and Kafka to build a Data Platform capture 1 billion bio-data a day.  
▪ Built a CI/CD Pipeline to process Parquet and Protocol Buffer files from Kafka using Pandas.  
▪ Optimized AWS Lambda function with multiprocessing that make 30% Cost Reduction in pipeline.  
▪ Exerted SQL to select and store data to DynamoDB and S3 which triggered by AWS EventBridge.  

![image](https://github.com/TotallyNewGuy/sn-intern-project/blob/main/SN/sleep%20number_task1.png)  
![image](https://github.com/TotallyNewGuy/sn-intern-project/blob/main/SN/multiprocess%20(1).png)  

<span id="jump2"></span>
## B. Wrote a script which can provisioning over 1 million IoT device in AWS
▪ Implemented Flask and Python to write Scripts in Linux to build Automation which make devices registered in AWS automatically through AWS Cognito and IAM.  
▪ Migrated and provisioned over 1 million devices to AWS IoT Core to collaborate with AWS services.  

<span id="jump3"></span>
### Step 1: Install Provisional Cliam
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/SN/sleep%20number%20A.png)

<span id="jump4"></span>
### Step 2: Register Thing
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/SN/sleep%20number%20B.png)

<h4 align="center">Make this device as a cloud resource in AWS IoT core</h4>  

<span id="jump5"></span>
### Step 3: Get Credentials
![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/SN/sleep%20number%20C.png)

<h4 align="center">Interact with other AWS resources using this Assume Role</h4>  


