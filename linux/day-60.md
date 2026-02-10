# Day 60
## Focus
Systemd Services Basics

## What is systemd?
systemd is the main service manager in modern Linux distributions.
It manages:
- services
- startup processes
- logging
- background daemons

## What is a Service?
A service is a background program that runs continuously.
Example:
- ssh service
- nginx service

## Important systemctl Commands
### Check status
```bash
systemctl status ssh
