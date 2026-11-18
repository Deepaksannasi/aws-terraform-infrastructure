# AWS Infrastructure Provisioning Using Terraform Modules

## Project Overview
This project demonstrates how to provision AWS infrastructure using Terraform with a modular approach.

## AWS Services Used
- Amazon VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Groups
- Amazon EC2
- Amazon S3

## Tools Used
- AWS
- Terraform
- Linux
- Git and GitHub

## Project Structure
```text
aws-terraform-project/
├── provider.tf
├── main.tf
├── variable.tf
├── terraform.tfvars.example
├── outputs.tf
├── .gitignore
└── modules/
    ├── vpc/
    ├── ec2/
    ├── s3/
    └── security-group/
```

## Deployment Steps

1. Install Terraform and configure AWS authentication.
2. Clone this repository.
3. Create your own `terraform.tfvars` using `terraform.tfvars.example`.
4. Initialize Terraform:

```bash
terraform init
```

5. Validate the configuration:

```bash
terraform validate
```

6. Review the deployment plan:

```bash
terraform plan
```

7. Deploy the infrastructure:

```bash
terraform apply
```

8. Delete the infrastructure when finished:

```bash
terraform destroy
```

## Learning Outcomes
- Understanding Terraform modules.
- Creating reusable infrastructure components.
- Provisioning AWS resources using Infrastructure as Code.
- Managing AWS infrastructure through Terraform.
