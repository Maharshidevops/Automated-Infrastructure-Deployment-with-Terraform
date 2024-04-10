# Automated-Infrastructure-Deployment-with-Terraform

This project aims to automate the deployment of AWS infrastructure components such as EC2 instances, subnets, VPCs, and security groups using Terraform. By utilizing Terraform's infrastructure as code (IaC) capabilities, the process of provisioning and managing AWS resources becomes more efficient and scalable.

Project Components:

Terraform Configuration Files: These files define the infrastructure components to be provisioned on AWS.

EC2 Instances: Virtual servers that run applications on the AWS cloud platform.

Subnets: Segmented sections of a VPC to organize and manage network traffic.

VPC (Virtual Private Cloud): A virtual network dedicated to your AWS account, isolated from other virtual networks.

Security Groups: Virtual firewalls that control inbound and outbound traffic to AWS resources.

1. Install Terraform on your local machine.
Configure AWS credentials with appropriate permissions.

2. Clone Repository:
3. Navigate to Project Directory:
4. cd terraform-automation-project
Update Variables:
5.Review and update variables in the Terraform configuration files (e.g., variables.tf) according to your requirements.
6.Initialize Terraform using terraform init, terraform plan, terraform apply

WARNING! 
After completing your project don't forget to vipe everything with the command: terraform destroy

Contributing:
We welcome contributions from the community! Feel free to fork this repository, make improvements, and submit pull requests.
