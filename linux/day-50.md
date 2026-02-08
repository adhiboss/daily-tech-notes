# Day 50
## Focus
Firewall Basics (iptables and ufw)

## What is a Firewall?
A firewall controls incoming and outgoing network traffic using rules.
It can allow or block traffic based on:
- IP address
- port number
- protocol (TCP/UDP)

## Why Firewall is Important
- Prevents unauthorized access
- Protects services running on a server
- Helps secure open ports

## Linux Firewall Tools
### iptables
- Low-level firewall tool in Linux
- Uses tables and chains (INPUT, OUTPUT, FORWARD)

Example:
- Block incoming traffic on port 8080:
  `sudo iptables -A INPUT -p tcp --dport 8080 -j DROP`

### ufw (Uncomplicated Firewall)
- Easier firewall management tool
- Uses simple commands

Common commands:
- Enable ufw:
  `sudo ufw enable`
- Allow SSH:
  `sudo ufw allow 22`
- Allow HTTP:
  `sudo ufw allow 80`
- Check status:
  `sudo ufw status`

## Observations
- Always allow SSH before enabling firewall on remote servers
- Firewalls reduce attack surface
- Port scanning shows which ports are open if firewall allows it
