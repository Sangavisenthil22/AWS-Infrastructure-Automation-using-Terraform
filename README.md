# AWS-Infrastructure-Automation-using-Terraform

**OVERVIEW**

This project uses Terraform to automate the creation and configuration of AWS infrastructure.

Instead of creating AWS resources manually through the AWS Console, Terraform is used to deploy the infrastructure as code. The project provisions a VPC, public subnet, Internet Gateway, route table, security group, IAM role, and EC2 instance, with an Apache web server configured automatically.

**AWS RESOURCES**

The project creates:

VPC – Creates the AWS network

Public Subnet – Hosts the EC2 instance

Internet Gateway – Provides internet access

Route Table – Routes traffic to the internet

Security Group – Allows HTTP traffic

IAM Role – Provides permissions to EC2

EC2 Instance – Runs the web server

AWS Systems Manager (SSM) – Allows secure EC2 management

Apache – Hosts the web page

**TECHNOLOGIES USED**

AWS | Terraform | Linux | Apache

**HOW IT WORKS**

Terraform 
↓
AWS VPC 
↓
Public Subnet 
↓
EC2 Instance
↓
Apache Web Server
↓
Web Page

The EC2 instance is managed using AWS Systems Manager instead of SSH.

**DEPLOYMENT**

Run the following commands:

- terraform init

- terraform validate

- terraform plan

- terraform apply

Terraform then creates the required AWS resources automatically.

**RESULT**

The EC2 instance runs an Apache web server with the following page:

Hello from Terraform

The infrastructure can be verified through the AWS Management Console, and the EC2 instance can be managed using AWS Systems Manager Session Manager.

**WHAT I LEARNED**

- Terraform Infrastructure as Code

- AWS VPC and networking

- EC2 deployment

- IAM roles

- AWS Systems Manager

- Linux and Apache

- AWS infrastructure automation

**CLEANUP**

To remove the AWS resources:

terraform destroy

This project was created to gain practical, hands-on experience with AWS and Terraform.
