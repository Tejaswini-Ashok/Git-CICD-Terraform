Implement CI/CD automation for the Terraform IaC workflows.

Example Terraform configuration, which creates an EC2 instance on AWS. Below is the summary of steps we will take to implement CI/CD on Github.

Set up Github project repository
Create the Terraform configuration files
Configure Github pipeline using .github/workflows/workflows-ci.yml
Add AWS credentials in Github
Set up the remote backend
Configure the backend for local development
Implement pipeline conditions and destroy the pipeline
