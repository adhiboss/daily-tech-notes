# Linux Networking – Day 33

## Topics Covered
- Firewall basics and traffic control
- Understanding inbound vs outbound rules
- Service exposure and security awareness

## Commands Practiced
- sudo ufw status
- sudo ufw enable
- sudo ufw allow 22
- sudo ufw allow 80
- ss -tulpn

## Notes
- Firewalls filter traffic before it reaches applications.
- Allow rules must be explicit for exposed services.
- SSH access should always be protected.
- ss helps confirm which services are exposed.

## Reflection
Today I learned how basic firewall rules protect services and how to verify exposed ports on a Linux system.
