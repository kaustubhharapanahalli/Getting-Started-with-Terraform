# Getting Started with Terraform

The project focuses on creating infrastructure using Hashicorp Configuration Language. The current implementation focuses on creating an infrastructure on AWS.

## Pre-requisites

- Terraform ([reference to setup terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli))
- Windows (Tested)
- AWS account and credentials saved in .aws folder ([reference](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html))

## Usage

- Initialize terraform using `terraform init`.

- After initialization, run `terraform plan -out aws_deploy.tfplan`.

- Apply the changes using `terraform apply aws_deploy.tfplan`.
