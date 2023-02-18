# Week 0 — Billing and Architecture

   ##  Required Tasks for week 0
  
   #### 1. Create a Free Github Account
   
         Already have account
    
   ####  1b – Set up MFA on your Github Account
   
         My github account has multifactor Authentication using google authenticatore from my Android phone.
        
   ####  2 – Create a Free Gitpod Account
         I have created free Gitpod Account, Also have chrome extension which provides gitpod button in github.

   ####  3 – Create Your Free AWS Account
   I have AWS account already , the Details of my account is found in student portal submission.
   [ Instruction to Install Aws CLI on Linux can be found from this link](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
   
  
   ####  4 –Test cloudShell
   I tested cloudShell from aws inbuilt terminal and created simple bucket in s3 storage like below.
   ![create a bucket using cloudShell](https://github.com/mesfint/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/cloudshell.png)
   
   **Note to Insert Image**
    
   ![S3 bucket](https://github.com/mesfint/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/create-s3-bucket-cli.png)
   
   ###¤ 5 - Install Aws cli
   
   I Installed AWS CLI on Ubuntu 20.4 using  the following **command**
           
   ```
   curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
   unzip awscliv2.zip
   sudo ./aws/install 
        
   ```
   [Instruction to Install aws cli on Linux can be found from this link](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
   
   **Note to Insert Image** 
   
   ![AWS CLI in Practice](https://github.com/mesfint/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/aws-cli.png)
   
   
   ####  6 – Create Create Billing Alarm
         I have created a  billing alarm following Brown video , My billing alarm will come as email.
         
   ####  7 – Create a Budget
          I created a budget from aws cli based on Andrew video . The new budget is reflected with exact information on aws, since the script is maching    with the the actual budget create.I Used this command to crereate budget using cli
   ```
   
   aws budgets create-budget \
    --account-id $ACCOUNT_ID \
    --budget file://aws/json/budget.json \
    --notifications-with-subscribers file://aws/json/budget-notifications-with-subscribers.json
   
   
   ```
   
   **Note to Insert Image**   
   ![Proof of Budget alert](https://github.com/mesfint/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/budget.png)
   
   #### 8 - Recreate Logical Architecture Diagram in Lucid Charts
   I have created the diagram as shown below, The diagram is a simple one, thatI have tried to incoorporate some aws services that will enhance the      microservice application performance.As I learn more about each services I would add more...
  **Note to Insert Image**
   ![Logical conceptual diagram](https://github.com/mesfint/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/conceptual-diagram.png)
         
   
   ####  9– Create Your Free Honeycomb.io Account
         I have created
   ####  10 – Create Your Free Rollbar Account
         I have created
