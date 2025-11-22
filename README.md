### Terraform + Docker + AWS ECS (Fargate) Deployment

This project demonstrates how to deploy a Dockerized Nginx application on AWS ECS (Fargate) using Terraform. It includes an Application Load Balancer, task definitions, IAM roles, networking, and a fully automated infrastructure workflow.
### Project Highlights

Deploy Docker container → ECS Fargate

Application Load Balancer (ALB) with health checks

ECS Task Definition + ECS Service

VPC, Subnets, Security Groups

IAM roles and execution roles

Fully automated Infrastructure as Code (IaC)

Version-locked providers with .terraform.lock.hcl

Clean GitHub structure (no large files, no state files)

🔧 How to Deploy
1️⃣ Initialize Terraform
terraform init

2️⃣ Validate configuration
terraform validate

3️⃣ Preview changes
terraform plan

4️⃣ Deploy infrastructure
terraform apply

5️⃣ Destroy infrastructure 
terraform destroy
