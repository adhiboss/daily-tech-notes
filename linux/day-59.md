# Day 59
## Focus
SSH Hardening Basics

## Why SSH Hardening?
SSH is a common attack target.
Hardening reduces risk of unauthorized access.

## Key Hardening Steps

### 1. Disable Password Login (Recommended)
Only allow SSH keys.
Config file:
`/etc/ssh/sshd_config`

Option:
- `PasswordAuthentication no`

### 2. Disable Root Login
Prevents direct root access.
Option:
- `PermitRootLogin no`

### 3. Change Default Port (Optional)
Default SSH port is 22.
Changing port reduces automated scans.
Option:
- `Port 2222`

### 4. Use Firewall Rules
Allow only required SSH access.
Example:
- `sudo ufw allow 22`

### 5. Limit Login Attempts
Tools like `fail2ban` block brute-force attempts.

Install:
```bash
sudo apt install fail2ban -y
