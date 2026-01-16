# AWS Infrastructure Automation with Terraform


##  📌 Project Overview

This project demonstrates end-to-end AWS infrastructure automation using Terraform to provision cloud resources and deploy a static web application hosted on NGINX.
The goal of this project is to showcase hands-on experience with Infrastructure as Code (IaC), cloud provisioning, and web server configuration.


## 🛠️ Technologies Used

* **Cloud Provider:** AWS

* **Infrastructure as Code:** Terraform

* **Compute Service:** Amazon EC2

* **Networking:** VPC, Subnet, IGW, Route Table, Security Groups

* **Web Server:** NGINX

* **Operating System:** Amazon Linux / Ubuntu

* **Version Control:** Git & GitHub


## ⚙️ Infrastructure Automation Details

* Terraform is used to automatically provision AWS resources

* EC2 instance is launched inside a public subnet

* Security Groups are configured to allow:
  * SSH access for administration
  * HTTP/HTTPS access for web traffic

* NGINX is installed and configured using Terraform user_data


