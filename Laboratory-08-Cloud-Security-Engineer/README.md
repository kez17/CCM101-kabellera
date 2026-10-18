# The Cloud Security Engineer

## Mission Overview
This activity places me as a Cloud Security Engineer tasked to secure an exposed Ubuntu server. I deployed a web service, checked its network status, and configured UFW following a Default Deny approach allowing only SSH and port 8080 traffic to apply defense in depth and least privilege principles.

## Objectives
- Understand Attack Surface and Principle of Least Privilege concepts
- Perform basic network port audit on a Linux server
- Configure UFW with Default Deny incoming policy
- Selectively permit SSH and web traffic on port 8080
- Document all work in Markdown and update GitHub portfolio

## Commands Executed
docker run -d -p 8080:80 --name secure-web-app nginx
curl localhost:8080
sudo ufw allow ssh
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw allow 8080/tcp
sudo ufw status verbose
sudo ufw status numbered
curl localhost:8080

## Skills Learned
- Deploying containerized applications
- Using UFW to harden server security
- Why blocking everything first is safer than listing threats
- Critical rule order: always allow SSH before enabling firewall
- Writing clear technical records and building professional portfolio
