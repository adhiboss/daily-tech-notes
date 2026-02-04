# Day 41
## Focus
HTTPS and TLS basics

## What HTTPS Solves
- Encrypts data in transit
- Prevents eavesdropping and tampering
- Authenticates the server

## TLS Handshake (High Level)
1. ClientHello
2. ServerHello + certificate
3. Key exchange
4. Secure session established

## Key Concepts
- Symmetric vs asymmetric encryption
- Certificates and Certificate Authorities (CA)
- Public key infrastructure (PKI)

## Observations
- HTTPS = HTTP over TLS
- TLS happens before HTTP data exchange
- Encryption adds overhead but is mandatory today
