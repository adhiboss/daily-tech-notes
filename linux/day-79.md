# Day 79: DNS Basics + /etc/resolv.conf in Linux (WSL)

## What is DNS?
DNS (Domain Name System) converts domain names like:
google.com
into IP addresses like:
142.250.x.x

Without DNS, browsers would require IP addresses directly.

---

## DNS Resolution Flow
1. User requests domain name
2. System checks local cache
3. System checks /etc/hosts
4. DNS query sent to configured DNS server
5. DNS server replies with IP address

---

## /etc/resolv.conf
This file defines DNS servers used by the system.

Example:
nameserver 8.8.8.8
nameserver 1.1.1.1

---

## WSL DNS Issue
In WSL, resolv.conf is sometimes auto-generated and resets after reboot.

Fix method:
1. Disable auto-generation
2. Create custom resolv.conf

---

## Useful Commands

### Check DNS server
cat /etc/resolv.conf

### Test DNS lookup
nslookup google.com

### Alternative DNS test
dig google.com

### Check connectivity
ping google.com

---

## Key Learning
- DNS is required for domain resolution.
- /etc/resolv.conf controls DNS servers.
- WSL sometimes overwrites resolv.conf automatically.
