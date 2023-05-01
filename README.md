                                 Marvel Team
   Project
Create a Serverless Workflow with AWS Step Functions and AWS Lambda
 
In this project, you will:
·      Create a Step Functions state machine to describe the current call center process
·      Create a few simple Lambda functions that simulate the tasks of the support team
·      Pass data between each Lambda function to track the progress of the support case
·      Perform several tests of your workflow to observe how it responds to different inputs
·  	Delete the AWS resources you used in the tutorial
Architecture
![image](https://user-images.githubusercontent.com/131652504/235493755-90dfa55b-bef4-43d2-9370-78a50afa2707.png)
Summary
This is an AWS CloudFormation template that creates resources to automate a call center support session using AWS Step Functions. 
It creates IAM roles for the Lambda functions and Step Functions state machine. 
It also creates Lambda functions for opening, assigning, working on, escalating, and closing support cases. 
Finally, it creates a Step Functions state machine that defines the flow of the call center support session, starting with opening a support case and ending with closing the support case, and uses the Lambda functions to perform the required actions at each state of the session.
                                                                          Flow chart
               If Case is success                                    
 ![image](https://user-images.githubusercontent.com/131652504/235494087-4ebc3703-18e7-499b-afaf-8c8d25cb0a42.png)
               If case is fail    
  ![image](https://user-images.githubusercontent.com/131652504/235494206-21108e71-ec3a-48c5-91b7-1fd7e1b553b6.png)

1)	What is the project about?
A)	Creating a Serverless Workflow with AWS Step Functions and AWS Lambda

2)	What are the steps involved in the project?
A)	Creating a Step Functions state machine to describe the current call center process

3)	 Creating simple Lambda functions to simulate the tasks of the support team
A)	Passing data between each Lambda function to track the progress of the support case
              Performing several tests of the workflow to observe how it responds to different inputs
               Deleting the AWS resources used in the tutorial
4)	What is the purpose of creating a Step Functions state machine?
A)	To describe the current call center process.

5)	What is the purpose of creating Lambda functions in this project?
A)  To simulate the tasks of the support team.
       6) What is the purpose of passing data between Lambda functions?
        A) To track the progress of the support case.
        7) What is the purpose of performing tests on the workflow?
        A) To observe how it responds to different inputs.
        8) What is the final step of the project?
        A) Deleting the AWS resources used in the tutorial.

