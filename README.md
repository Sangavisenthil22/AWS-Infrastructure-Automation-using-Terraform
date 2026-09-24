# AWS-Infrastructure-Automation-using-Terraform

**Overview**

This project uses Terraform to automate the creation and configuration of AWS infrastructure.

Instead of creating AWS resources manually through the AWS Console, Terraform is used to deploy the infrastructure as code. The project provisions a VPC, public subnet, Internet Gateway, route table, security group, IAM role, and EC2 instance, with an Apache web server configured automatically.

**AWS Resources**

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

**Technologies Used**

AWS | Terraform | Linux | Apache
