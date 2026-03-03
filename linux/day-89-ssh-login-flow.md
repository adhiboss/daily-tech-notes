# Day 89 - SSH Login Flow

## What is SSH?

SSH (Secure Shell) allows secure remote login to a server over TCP (port 22).

---

## What Happens During SSH Login

1. Client connects to server on port 22 (TCP handshake).
2. Server sends its public key.
3. Client verifies server key (known_hosts).
4. Encryption algorithm negotiation happens.
5. User authentication:
   - Password OR
   - Public key authentication
6. Encrypted session established.
7. User gets remote shell access.

---

## Why It Matters

Understanding SSH helps in:

- Debugging login failures
- Securing servers
- Managing cloud instances
- Configuring key-based authentication
