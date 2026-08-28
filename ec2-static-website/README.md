# EC2 Static Website (Apache/Nginx)

## What this project does
Launched an EC2 instance and hosted a static website using Apache/Nginx, 
accessible via a public IP.

## Architecture
User → Internet → EC2 (Public IP) → Apache/Nginx → HTML Website

## Steps taken
1. Launched EC2 instance (Amazon Linux/Ubuntu)
2. Configured Security Group to allow HTTP (port 80) and SSH (port 22)
3. Connected via SSH
4. Installed Apache/Nginx
5. Deployed index.html
6. Verified website loads via public IP

## Screenshots
(add here)

## What I learned
How to expose a web server publicly using EC2 security groups, and the 
difference between SSH access (port 22) vs web traffic (port 80).
