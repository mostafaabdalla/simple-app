
# Socks Shop

A brief description of what this project does and who it's for

## Infra Setup:
    1. Created Jenkins server on AWS EC2 instance.
    2. Setup Ansible server on EC2 instance.
    3. Setup bootstrap server for EKS.

## Deployment steps:
    1. Write ansible playbook to provision EKS cluster.
    2. Setup Jenkins job to automate the EKS cluster creation.
    3. Setup another jenkins job for the continous integration (clone, test and build the code).
    4. Setup the final jenkins job to continously deploy the code to the EKS cluster if the CI job is successful.
