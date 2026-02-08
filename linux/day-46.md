# Day 46
## Focus
NAT (Network Address Translation) and Public vs Private IP

## Public IP
- Globally unique IP address
- Assigned by ISP
- Used to communicate over the internet
- Example: 142.250.183.14

## Private IP
- Used inside local networks (LAN)
- Not routable on the internet
- Common ranges:
  - 192.168.0.0/16
  - 10.0.0.0/8
  - 172.16.0.0/12

## NAT (Network Address Translation)
- Converts private IP to public IP for internet access
- Usually done by routers
- Allows many devices to share one public IP

## Types of NAT
- Static NAT (1 private ↔ 1 public)
- Dynamic NAT (pool of public IPs)
- PAT (Port Address Translation) → most common

## PAT (Most Common NAT)
- Multiple private devices share one public IP
- Differentiated using port numbers

## Observations
- NAT saves IPv4 addresses
- NAT adds complexity for inbound connections
- Port forwarding is needed to host services behind NAT
