# AWS Enterprise Infrastructure

## Overview
This repository contains modular Terraform configurations used to provision AWS infrastructure following production-grade best practices.

## Architecture
- VPC with environment-based tagging
- Modular structure for scalability
- Remote backend with S3 & DynamoDB locking
- Environment separation (dev, prod)

## Key Features
- Reusable Terraform modules
- Remote state management
- Infrastructure version control
- IAM least privilege ready

## Deployment

```bash
terraform init
terraform plan
terraform apply
