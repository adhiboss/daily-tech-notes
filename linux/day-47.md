# Day 47
## Focus
Subnet Mask and CIDR Notation

## Subnet Mask
- Defines which part of an IP is network and which part is host
- Example:
  - IP: 192.168.1.10
  - Mask: 255.255.255.0

This means:
- Network part: 192.168.1
- Host part: .10

## CIDR Notation
CIDR = Classless Inter-Domain Routing

Format:
- IP/prefix-length
Example:
- 192.168.1.0/24

## Common CIDR Prefix Values
- /8  = 255.0.0.0
- /16 = 255.255.0.0
- /24 = 255.255.255.0
- /32 = single host

## Observations
- Smaller prefix number = larger network
- Larger prefix number = fewer hosts
- CIDR is used in routing and subnet planning
