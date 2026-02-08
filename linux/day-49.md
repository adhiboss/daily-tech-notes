# Day 49
## Focus
ARP (Address Resolution Protocol) and MAC Address Resolution

## What is ARP?
ARP is used to map an IP address to a MAC address in a local network.

Example:
- Device knows IP: 192.168.1.1
- But needs MAC address to send Ethernet frame
- ARP finds the MAC address

## ARP Process
1. Device broadcasts ARP request:
   "Who has 192.168.1.1?"
2. Target device replies:
   "192.168.1.1 is at <MAC address>"
3. MAC address is stored in ARP cache

## ARP Cache
- Temporary storage of IP → MAC mappings
- Helps reduce broadcast traffic

## Linux Commands
- View ARP table:
  - `ip neigh`
  - `arp -a`

## Observations
- ARP works only inside LAN
- ARP spoofing can be used for MITM attacks
- ARP is required for communication within same subnet
