# Virtualization
# Name: Krithika Sulochana Balasundaram
# Register Number: 212223060130

# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
# Aim
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
```
a) Steps to Create a First S3 Bucket
Sign in to the AWS Management Console
Go to AWS S3 Console.

Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.

Create Bucket
Click the Create bucket button.

Configure Bucket Settings

Bucket name: Choose a globally unique name.
AWS Region: Select the region where you want to store your data.
Object Ownership
Choose between:

ACLs disabled (recommended): Bucket owner has full control.
ACLs enabled: Control access via access control lists.
Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.

Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.

Encryption (optional)
Select encryption options: SSE-S3, SSE-KMS, or none.

Advanced Settings (optional)
Add tags, configure logging, etc.

Create the Bucket
Click Create bucket at the bottom of the page.

b) Steps to Launch an EC2 Instance
Go to the EC2 Dashboard in AWS Console.
Click on Launch Instance.
Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
Select an instance type (e.g., t2.micro for Free Tier).
Create or choose a key pair for SSH access.
Configure network settings (use default VPC/subnet).
Configure storage (default root volume is fine).
Review the settings and click Launch Instance.
Wait for the instance to enter the running state.
c) Connect to Your Instance
Linux: Use SSH command with your .pem key.
Windows: Use RDP with decrypted admin password.
d) Steps to Clean Up (Terminate the Instance)
Go to EC2 Instances.
Select your instance → Instance State → Terminate.
```
# Output

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/49d9304d-58ae-4efe-b255-0dde77ca5dd2" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6a0b707f-6408-4887-89a7-8bcb41c72eec" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b3574bb8-08f8-40bf-b5ea-6501d342b48c" />

# Result
```
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) instance has been successfully created and launched in AWS.
```
