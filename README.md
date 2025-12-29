# project-2-ec2-webserver
EC2 Web Server Deployment on AWS: Launch and configure an Amazon EC2 instance, set up security groups, install Nginx/Apache web server, and verify public accessibility.

# AWS EC2 Web Server Deployment

## Overview
This project demonstrates how to deploy a web server on Amazon Web Services (AWS) using an EC2 instance. The web server is configured to serve HTTP traffic and is accessible via a public IP address.

## Services Used
- **Amazon EC2** – Virtual server provisioning
- **AWS IAM** – Identity and access management
- **Security Groups** – Inbound/outbound traffic control
- **Linux** – Server operating system (Amazon Linux)
- **Nginx** – Web server software

## Deployment Steps
1. **Launch EC2 Instance**  
   - Used Amazon Linux AMI
   - Selected t3.micro instance type
   - Assigned a security group allowing SSH (port 22) and HTTP (port 80)

2. **Connect to EC2 Using SSH**  
   - Connected via browser SSH (EC2 Instance Connect) or key pair

3. **Install Nginx Web Server**  
   - Updated system packages
   - Installed and started Nginx

4. **Verify Deployment**  
   - Accessed the application using the instance’s public IP
   - Confirmed Nginx welcome page in the browser

## Outcome
Successfully deployed a web server on AWS EC2 with secure access and publicly accessible web content.

## Usage
To test the deployment:
1. Go to the EC2 console
2. Copy the public IPv4 address of your instance
3. Paste into a browser:

