# Mediawiki APP Deployment into Kubernetes Using Terraform & Azure
This is a simple automation for setting up minikube in Azure and deploying Mediawiki into it using terraform.

# Getting Started
Follow these simple instructions to get your minkikube up and running along with Mediawiki deployed into it.

# Prerequisites
Install Terraform and git on the machine.

wget https://releases.hashicorp.com/terraform/0.12.6/terraform_0.12.6_linux_amd64.zip
sudo unzip ./terraform_0.11.13_linux_amd64.zip -d /bin/

# Running The Automation
Clone the current repo to your local machine using
git clone https://github.com/Sai-prudhvi1483/MediawikiApp.git

# Move into Terraform directory
cd MediaWiki/Terraform/

# Run the Terraform script
terraform init 
terraform validate
terraform plan
terraform apply

You can access the application at http://{publicip}:30163/wiki
