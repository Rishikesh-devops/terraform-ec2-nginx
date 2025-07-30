\# Terraform EC2 + Nginx Deployment



This project automates the deployment of an EC2 instance running Nginx using Terraform on AWS.



\## ✅ Features



\- Creates a custom VPC

\- Deploys an EC2 instance with Amazon Linux 2

\- Sets up a security group for HTTP (port 80) and SSH (port 22)

\- Installs and runs Nginx on the instance using a user\_data script



\## 📁 Files Overview



| File                  | Description                              |

|-----------------------|------------------------------------------|

| `main.tf`             | Terraform configuration for infrastructure |

| `outputs.tf`          | Outputs for public IP, etc.              |

| `terraform.tfvars`    | Variable values for the project          |

| `.gitignore`          | Ignore .terraform and other sensitive files |



\## 🚀 How to Use



```bash

terraform init

terraform plan

terraform apply



