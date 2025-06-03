# ☁ Cloud Cybersecurity Homelab
Deploy an attack/defend cybersecurity homelab.

# Topology 
Provider: AWS.



![Topology](https://github.com/collinsmc23/cloud-cybersecurity-homelab/blob/main/images/Cloud-hosted%20Cybersecurity%20Homelab.png)




# Deploy 

Download Terraform: https://developer.hashicorp.com/terraform/downloads 

`terraform init`: Initialize Terraform.

`terraform plan`: Plan Terraform configuration.

`terraform apply -var="aws-key"`: Specify the public key name created in AWS in EC2 -> Network & Security.
- Add Public Key Name in between double quotes.

`terraform destory`: Destroy AWS infrastructure.
