# Terraform AWS Web Application Infrastructure

This repository contains Terraform configurations for deploying a scalable web application infrastructure on AWS. The infrastructure is designed with best practices for security, scalability, and maintainability.

## Features

- Modular infrastructure design
- Secure VPC configuration
- Auto-scaling capabilities
- Load balancer setup
- Multi-environment support (dev, staging, prod)

## Prerequisites

- AWS Account
- Terraform >= 1.0.0
- AWS CLI configured with appropriate credentials

## Usage

1. Clone the repository:
```bash
git clone https://github.com/MukherjeePushpendu/terraform-aws-webapp-infra.git
```

2. Navigate to the project directory:
```bash
cd terraform-aws-webapp-infra
```

3. Initialize Terraform:
```bash
terraform init
```

4. Review the infrastructure plan:
```bash
terraform plan
```

5. Apply the configuration:
```bash
terraform apply
```

## Structure

```
terraform-aws-webapp-infra/
├── main.tf           # Main Terraform configuration
├── variables.tf      # Input variables
├── outputs.tf        # Output values
└── README.md        # Documentation
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
