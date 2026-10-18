# Firewall Configuration Documentation

## Command to allow SSH
sudo ufw allow ssh
This rule keeps port 22 open permanently so administrators can connect remotely and manage the server at all times.

## Set Default Deny Policy
sudo ufw default deny incoming
sudo ufw default allow outgoing
These set the base behavior: all unsolicited incoming connections get rejected, while the server can still make its own outgoing connections for updates and external services.

## Allow Port 8080
sudo ufw allow 8080/tcp

## What Happens if UFW Is Enabled Before Allowing SSH?
If you run sudo ufw enable before allowing SSH, your current remote session will terminate immediately and you will lose the ability to reconnect to the server.
