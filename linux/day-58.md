# Day 58
## Focus
SSH Authentication Flow (Password vs Key-Based)

## What is SSH?
SSH (Secure Shell) is a secure protocol used to remotely access servers.

Default port: 22

## Password Authentication
- User enters username and password
- Easy but less secure
- Vulnerable to brute-force attacks if weak passwords exist

## Key-Based Authentication
Uses cryptographic keys:
- Private key (stored on client machine)
- Public key (stored on server)

### How it Works
1. Client connects to server
2. Server sends challenge
3. Client signs challenge using private key
4. Server verifies using public key
5. Access granted

## Advantages of Key-Based SSH
- Strong security
- No password required
- Resistant to brute-force attacks

## Important Files
- Client private key:
  `~/.ssh/id_ed25519`
- Client public key:
  `~/.ssh/id_ed25519.pub`
- Server authorized keys:
  `~/.ssh/authorized_keys`

## Observations
- Private key must never be shared
- Key-based SSH is standard for production servers
- SSH is widely used in DevOps and cloud environments
