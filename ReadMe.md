﻿# terraform-azurevm
## This repo contains Terraform HCL scripts to span a virtual machine in Azure
### 1. Install Terraform
### 2. Install AzureCLI and login to Azure from CLI
### 3. Clone this repo, Copy the ssh pub key file to the repo directory
### 4. Run *terraform init* in terminal
### 5. Run *terraform plan* in terminal and verify the resources to be created
### 6. Run *terraform apply* to create resources on Azure
### 7. Copy the IP of the newly created VM from Azure portal and the below command to connect to the vm
###    Run *ssh [IP Copied from portal] -i [ssh pub key nam]> -l ubuntu_user*
### 8. Run *terraform destroy* to delete to resources
