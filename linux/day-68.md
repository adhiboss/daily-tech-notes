# Day 68
## Focus
TLS/HTTPS Basics

## What is HTTPS?
HTTPS = HTTP + TLS (encryption)

It protects communication between client and server.

## Why TLS is Needed
TLS provides:
- Encryption (privacy)
- Integrity (prevents modification)
- Authentication (verifies server identity)

## TLS Handshake (High Level)
1. Client says hello + supported cipher suites
2. Server sends certificate (public key)
3. Client verifies certificate
4. Shared session key is created
5. Encrypted communication begins

## Certificates
- Certificates are issued by Certificate Authorities (CA)
- Browser trusts well-known CAs
- Certificate proves domain ownership

## Port
- HTTPS runs on port 443

## Observations
- HTTPS prevents sniffing and MITM attacks
- TLS is essential for secure logins and payments
- Modern internet depends heavily on TLS encryption
