# Terraform_

Terraform Installation in MAC:

brew tap hashicorp/tap\nbrew install hashicorp/tap/terraform
terraform -help

Pre-requisites to work with AWS:
  Terraform CLI
  AWS CLI

Install AWS CLI:

curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
sudo installer -pkg ./AWSCLIV2.pkg -target /

To Check if the installation is complete:

which aws
aws --version


Terraform Commands:

Terraform init

Terraform plan

Terraform apply

Terraform show

Terraform state list

Terraform validate
