# Day 88 - DNS Resolution Flow

## What is DNS?

DNS (Domain Name System) converts domain names into IP addresses.

Example:
google.com → 142.250.x.x

---

## DNS Resolution Steps

1. User enters domain in browser
2. Browser checks local cache
3. OS checks DNS cache
4. Query sent to Recursive Resolver (ISP or configured DNS)
5. Resolver contacts:
   - Root server
   - TLD server (.com)
   - Authoritative name server
6. IP address returned to client
7. Browser connects to server via TCP

---

## Types of DNS Servers

- Recursive Resolver
- Root Server
- TLD Server
- Authoritative Server

---

## Why It Matters

Understanding DNS helps in:
- Debugging network issues
- Diagnosing slow website loading
- Fixing domain misconfigurations
