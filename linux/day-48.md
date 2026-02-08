# Day 48
## Focus
Routing Basics and Default Gateway

## What is Routing?
Routing is the process of forwarding packets from one network to another using routing tables.

A router decides the best path for packets to reach the destination.

## Default Gateway
- The router IP address that forwards traffic outside the local network
- Used when the destination is not in the same subnet

Example:
- PC IP: 192.168.1.10
- Router (gateway): 192.168.1.1
- Any traffic outside 192.168.1.0/24 goes to 192.168.1.1

## Routing Table
A routing table contains rules like:
- destination network
- gateway
- interface

## Important Commands (Linux)
- View routing table:
  - `ip route`
- View interfaces:
  - `ip a`

## Observations
- Without a default gateway, internet access fails
- Routing is essential for communication between networks
- `ip route` is a key troubleshooting tool
