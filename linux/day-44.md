# Day 44
## Focus
HTTP vs HTTPS (Security Basics)

## HTTP
- Works on plain TCP
- Data is transmitted in plain text
- Vulnerable to sniffing and MITM attacks

## HTTPS
- HTTP over TLS (encrypted)
- Protects confidentiality and integrity
- Authenticates server using certificates

## Key Differences
- HTTP default port: 80
- HTTPS default port: 443
- HTTPS requires TLS handshake before HTTP exchange

## Observations
- HTTPS is mandatory for modern web apps
- TLS adds overhead but prevents data theft
- Without HTTPS, login credentials can be intercepted
