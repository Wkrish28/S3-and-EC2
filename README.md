# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

# NAME : SHRIKRISHNA V
# REG NO : 212223040198

# AIM :
To create an AWS account, set up a root user, and create an IAM user with specified permissions.

# PROBLEM STATEMENT :
This experiment involves creating an AWS account, configuring security settings for the root user, and setting up an IAM user. IAM users allow for secure, managed access to AWS resources without exposing the main account's root credentials.

# Procedure:
Sign in to the AWS Management Console: • Go to the AWS Management Console and log in with your AWS credentials.
Navigate to the EC2 Dashboard: • Once logged in, locate and click on the "EC2" service in the AWS Management Console.
Launch an Instance: • On the EC2 dashboard, click the "Launch Instance" button.
Choose an AMI (Amazon Machine Image):
• Select the operating system and software you want to use for your instance (e.g., Amazon Linux, Ubuntu, Windows). • Click "Select" to choose the AMI.
Choose an Instance Type: • Select the type of instance you need (e.g., t2.micro, m5.large) based on your workload requirements. • Click "Next: Configure Instance Details".
Configure Instance Details: • Set the number of instances to launch, the availability zone, and other optional settings like networking and security. • Click "Next: Add Storage".
Configure Storage: • Specify the size and type of storage for your instance. • Click "Next: Add Tags".
Add Tags (Optional): • Add tags to your instance for easier identification and management. • Click "Next: Configure Security Group".
Configure Security Group:
• Choose or create a security group to control inbound and outbound traffic to your instance. • Click "Review and Launch".
Review and Launch:
• Review all the configurations and click "Launch".
Create a Key Pair (if you haven't already): • You'll be prompted to create a new key pair or choose an existing one. • Download the key pair (.pem file) and store it securely.
Launch the Instance: • Click "Launch Instance" to start the instance creation process.
Connect to your Instance:
• Once the instance is running, you can connect to it using SSH (for Linux) or RDP (for Windows). • Use the key pair you downloaded earlier to connect.

# output
<img width="1919" height="967" alt="image" src="https://github.com/user-attachments/assets/dd84a1c9-6983-4a56-b1ea-8f2d5cca40b9" />

<img width="1919" height="971" alt="image" src="https://github.com/user-attachments/assets/87b9bcad-a36d-4785-82e6-4cdeecd2308a" />



 # RESULT
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
