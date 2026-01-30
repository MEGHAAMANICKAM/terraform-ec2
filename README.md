# EC2 AMI Creation and Terraform Deployment

## 📌 Project Overview
This project demonstrates how to:

- Launch an EC2 instance
- Install Nginx
- Create a custom AMI
- Deploy a new EC2 using Terraform from that AMI

---

## 🛠 Tools Used

- AWS EC2
- Terraform
- GitHub
- Nginx

---

## 🚀 Steps

### 1. Launch EC2
Create an EC2 instance and allow SSH & HTTP.

### 2. Install Nginx
sudo dnf install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx


### 3. Create AMI
Create an image from the configured instance.

### 4. Terraform Deployment
Use Terraform to launch a new instance from the AMI.

terraform init
terraform apply


### 5. Verification
Check nginx:

nginx -v

Access: http://<public-ip>

---

## 🎯 Learning Outcomes

- AMI creation
- Infrastructure as Code
- Terraform basics
- AWS networking & security groups







