# AWS EC2 Static Website Deployment

## Project Overview
This project demonstrates how I deployed a static HTML website on an AWS EC2 instance using Ubuntu Server and Nginx.

## Technologies Used
- AWS EC2
- Ubuntu 24.04 LTS
- Nginx
- HTML
- JavaScript
- Linux

## Architecture
User Browser → AWS EC2 → Nginx → HTML Website

## Implementation Steps
1. Launched an Ubuntu EC2 instance on AWS.
2. Connected to the instance using EC2 Instance Connect.
3. Created a Linux user named `abilitycloud`.
4. Granted administrative privileges using the sudo group.
5. Updated the Ubuntu packages.
6. Installed and configured Nginx.
7. Created the website at `/var/www/html/index.html`.
8. Configured HTTP access through port 80.
9. Tested the website using the EC2 public IP address.

## Live Demo
http://13.61.174.38

## Key Learning Outcomes
- AWS EC2 instance provisioning.
- Linux user and permission management.
- Nginx installation and configuration.
- Hosting static websites on cloud infrastructure.
- Managing inbound security group rules.

## Author
Adekunle Jamiu Oyetayo

[GitHub](https://github.com/Abilitycloud) | [LinkedIn](https://www.linkedin.com/in/adekunle-jamiu-oyetayo)
