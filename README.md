# AWS-Cloud-Practitioner-Hands-On
AWS Cloud Infrastructure Setup and Management
Overview:

This project involves setting up and managing a complete AWS cloud infrastructure using various AWS services. Below is a step-by-step guide of what was done:


Architecture Diagram:

![AWS Cloud](https://github.com/user-attachments/assets/bd073376-09c6-414e-82b8-205e6ab8483c)








1. IAM User and Permissions Setup
Created IAM User: Set up an IAM (Identity and Access Management) user for secure access.
Assigned Permissions: Granted specific permissions to the IAM user based on the tasks needed.
Enabled Multi-Factor Authentication (MFA): Added an extra layer of security by enabling MFA for the IAM user.
2. VPC and Networking Configuration
Created a VPC: Designed a Virtual Private Cloud (VPC) to isolate and manage network resources.
Configured Subnets: Set up public and private subnets within the VPC to organize resources and manage traffic.
Attached an Internet Gateway: Connected the VPC to the internet for public access.
Set Up Route Tables: Configured route tables to manage traffic between subnets and the internet.
3. EC2 Instance Management
Launched EC2 Instance: Deployed an EC2 instance using the free-tier t3.micro instance type with an appropriate operating system.
Attached the Instance to VPC: Connected the EC2 instance to the previously configured VPC.
Added Storage: Configured additional storage using EBS (Elastic Block Store) volumes.
Created Security Groups: Set up security groups to control network access to the EC2 instance.
Configured SSH Access: Managed SSH access keys for secure login.
4. Remote Desktop Access
Accessed Windows Instance: Used Remote Desktop Protocol (RDP) to connect to a Windows EC2 instance.
Decrypted Key Pair Password: Obtained the Windows login password by decrypting the key pair.
5. Autoscaling Configuration
Set Up Autoscaling Groups: Configured autoscaling to automatically adjust the number of EC2 instances based on demand, ensuring high availability and cost efficiency.
6. Storage and Database Services:
Configured Amazon S3: Set up S3 buckets for scalable object storage, useful for backups and file storage.
Deployed Amazon RDS: Created an RDS (Relational Database Service) instance for relational database management.
Set Up Amazon DynamoDB: Created DynamoDB tables for NoSQL data storage, handling non-relational data efficiently.
7. CI/CD Pipeline Integration
Implemented CI/CD Pipelines: Used AWS CodePipeline, CodeBuild, and CodeDeploy to automate the deployment process for applications, ensuring consistent and efficient delivery.
8. Monitoring and Logging
Configured Amazon CloudWatch: Set up CloudWatch to monitor application performance and set up alerts for any issues.
Enabled AWS CloudTrail: Activated CloudTrail to log and track API calls across the AWS environment for auditing and compliance.



Key Learnings:

Mastered AWS service configuration and management
Gained experience in setting up scalable and secure cloud infrastructure
Learned to automate deployments and monitor systems effectively
This project showcases practical skills in AWS cloud services, infrastructure design, automation, and operational management.
