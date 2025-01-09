# Automated AWS Infrastructure Deployment and Optimization

This project automates the deployment and management of AWS infrastructure using Terraform, Jenkins, and other tools. It ensures secure, efficient, and scalable infrastructure setups.

## Key Features
- Automated provisioning of AWS resources (VPC, EC2, Load Balancer).
- Continuous deployment of infrastructure changes using Jenkins and GitHub.
- Terraform state management with Amazon S3 for version control and security.
- Infrastructure monitoring with AWS CloudWatch.
- Cost and security optimization with AWS Trusted Advisor.
- Code quality assurance with SonarQube.

## Tools and Technologies
- **Terraform**: Infrastructure as Code (IaC)
- **Jenkins**: CI/CD automation
- **SonarQube**: Code quality checks
- **AWS Services**: VPC, EC2, S3, CloudWatch, Trusted Advisor
- **GitHub**: Version control

## Architecture
![Architecture Diagram](diagrams/architecture-diagram.png)

## Usage
1. Clone the repository.
2. Navigate to the `terraform` directory and initialize Terraform:
   ```bash
   cd terraform
   terraform init
   terraform apply
