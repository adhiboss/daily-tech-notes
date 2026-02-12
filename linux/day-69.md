# Day 69
## Focus
NAT vs Port Forwarding

## NAT (Network Address Translation)
NAT translates private IP addresses into a public IP address.

Example:
- Devices inside LAN use private IPs (192.168.x.x)
- Router converts them into 1 public IP for internet access

## Why NAT is Used
- Saves IPv4 addresses
- Allows multiple devices to share one public IP

## Port Forwarding
Port forwarding is a NAT feature that allows external traffic to reach an internal device/service.

Example:
- Public IP: 49.x.x.x
- Forward port 80 → internal server 192.168.1.10:80

So when someone accesses:
