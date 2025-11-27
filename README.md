# IaC VPC Baseline
A secure, production‑ready AWS VPC foundation built entirely with Terraform.

## Features
- Public/private subnets
- NAT gateway (toggleable)
- SSM Session Manager bastion (no SSH)
- Opinionated security groups
- Route tables + associations
- Cost‑aware design

## Structure
```
iac-vpc-baseline/
├── modules/
├── examples/
├── main.tf
├── variables.tf
├── outputs.tf
└── terraform.tfvars
```

## Deployment
```
terraform init
terraform plan
terraform apply
```

## Tags
AWS, Terraform, VPC, Networking, IaC
