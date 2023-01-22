# Terraform_splat_expressions_aws_vpc

This project uses Terraform to create an AWS VPC with public and private subnets, as well as a NAT gateway for outbound internet access for the private subnets.

# Files

- `main.tf`: This file contains the main Terraform configuration, including provider and resources definitions.
- `network.tf`:This file contains the definitions for the VPC and its associated resources,such as subnets, internet gateways, and route tables.
- `outputs.tf`: This file contains the output variables that will be displayed upon Terraform apply, such as the VPC ID and public IP of the NAT gateway.
