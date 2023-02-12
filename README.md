
# Socks Shop

A brief description of what this project does and who it's for

## Infra Setup:
    1. Created Jenkins server on AWS EC2 instance.
    2. Setup Ansible server on EC2 instance.
    3. Setup bootstrap server for EKS.

## Deployment steps:
    1. Write ansible playbook to provision EKS cluster.
    2. Setup Jenkins job to automate the EKS cluster creation.
    3. Setup another jenkins job to clone the microservices app and deploy it on the EKS cluster.
## Demo
For more information about the socks app and how to use it, please go to this link:
https://github.com/mostafaabdalla/microservices-demo