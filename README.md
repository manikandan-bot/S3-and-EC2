# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
# REGISTER NUMBER:212224110037

## AIM :

To create an AWS account, set up a root user, and create an IAM user with specified permissions.

## PROBLEM STATEMENT :

This experiment involves creating an AWS account, configuring security settings for the root user, and setting up an IAM user. IAM users allow for secure, managed access to AWS resources without exposing the main account's root credentials.

## Procedure:
```
Sign in to the AWS Management Console:
• Go to the AWS Management Console and log in with your AWS credentials.
Navigate to the EC2 Dashboard:
• Once logged in, locate and click on the "EC2" service in the AWS Management Console.
Launch an Instance:
• On the EC2 dashboard, click the "Launch Instance" button.
Choose an AMI (Amazon Machine Image):
• Select the operating system and software you want to use for your instance (e.g., Amazon Linux, Ubuntu, Windows).
• Click "Select" to choose the AMI.
Choose an Instance Type:
• Select the type of instance you need (e.g., t2.micro, m5.large) based on your workload requirements.
• Click "Next: Configure Instance Details".
Configure Instance Details:
• Set the number of instances to launch, the availability zone, and other optional settings like networking and security.
• Click "Next: Add Storage".
Configure Storage:
• Specify the size and type of storage for your instance.
• Click "Next: Add Tags".
Add Tags (Optional):
• Add tags to your instance for easier identification and management.
• Click "Next: Configure Security Group".
Configure Security Group:
• Choose or create a security group to control inbound and outbound traffic to your instance.
• Click "Review and Launch".
Review and Launch:
• Review all the configurations and click "Launch".
Create a Key Pair (if you haven't already):
• You'll be prompted to create a new key pair or choose an existing one.
• Download the key pair (.pem file) and store it securely.
Launch the Instance:
• Click "Launch Instance" to start the instance creation process.
Connect to your Instance:
• Once the instance is running, you can connect to it using SSH (for Linux) or RDP (for Windows).
• Use the key pair you downloaded earlier to connect.
```
## Output:
<img width="1247" height="607" alt="image" src="https://github.com/user-attachments/assets/f3b811dd-1d7a-4d1e-ab0e-472e8fcdca5d" />


<img width="1257" height="622" alt="image" src="https://github.com/user-attachments/assets/4af86337-b069-4dec-a351-f5da9ee8e07b" />


<img width="1252" height="652" alt="image" src="https://github.com/user-attachments/assets/d30306a1-1107-4078-a29f-245d0bf5295b" />


<img width="1255" height="635" alt="image" src="https://github.com/user-attachments/assets/4168d941-41f2-4428-8450-7b61b2383e39" />


## RESULT:
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
