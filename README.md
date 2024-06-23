## Cloud Formation Assignment


#### Problem Statement 1 :

You work for XYZ Corporation. Your team is asked to deploy similar architecture
multiple times for testing, development, and production purposes. Implement
CloudFormation for the tasks assigned to you below.
Tasks To Be Performed:

1. Create a template which can create an S3 bucket named `intellipaat-<yourname>`
2. The template should be able to enable versioning for the bucket created.


#### Problem Statement 2 :

You work for XYZ Corporation. Your team is asked to deploy similar architecture
multiple times for testing, development, and production purposes. Implement
CloudFormation for the tasks assigned to you below.
Tasks To Be Performed:
1. Create a template with 1 VPC and 1 public subnet.
2. Launch an Amazon Linux EC2 instance in the public subnet and tag the
instance as “CFinstance”

   
#### Problem Statement 3 : 

You work for XYZ Corporation. Your team is asked to deploy similar architecture multiple times for testing, development, and production purposes. Implement CloudFormation for the tasks assigned to you below. 

Tasks To Be Performed: 

1. Use the template from CloudFormation task 1.
2. Add Notification to the CloudFormation stack using SNS so that you get a notification via mail for every step of the stack creation process. 

(Not don via code yet , done manually) - created an SNS topic and subscription to enable email notifications. 
Then updated the notifications settings during stack creation to add the SNS topic created.

#### Problem Statement 4:
							
You work for XYZ Corporation. Your team is asked to deploy similar architecture multiple times for testing, development, and production purposes. Implement CloudFormation for the tasks assigned to you below.
							
Tasks To Be Performed:
							
1. Create a FIFO SQS queue and test by sending messages. 
2. Register your mail in SES and send a test mail to yourself.
