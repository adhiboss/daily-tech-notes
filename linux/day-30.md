# Linux Networking – Day 30

## Topics Covered
- Well-known ports and services
- Identifying listening services
- Mapping ports to applications

## Commands Practiced
- ss -tuln
- ss -tulpn
- lsof -i :80
- nmap -p 1-100 localhost

## Notes
- ss shows listening sockets and protocols.
- ss -p maps ports to processes.
- lsof helps identify which app uses a port.
- Port scanning helps discover exposed services.

## Reflection
Today I learned how to identify running services and map ports to applications on a Linux system.
