# Day 02 - Amazon EC2

## Objective
Learn how to launch and connect to an EC2 instance using SSH.

## Hands-on Performed
- Launched an EC2 instance
- Connected using PuTTY
- Ran basic Linux commands
- Installed Apache HTTP Server
- Verified the Apache web page

## Linux Commands
```bash
pwd
ls
mkdir myproject
cd myproject
touch index.html
```

## Apache Commands
```bash
sudo dnf update -y
sudo dnf install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
```

## Key Learnings
- EC2 is a virtual server in AWS.
- SSH provides secure remote access.
- Apache is a web server.
