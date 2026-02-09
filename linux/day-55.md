# Day 55
## Focus
Proxy vs Reverse Proxy

## Proxy (Forward Proxy)
A proxy server that sits between the client and the internet.

### How it Works
Client → Proxy → Internet Server

### Uses
- hides client identity (privacy)
- content filtering
- caching
- access control in organizations

Example:
- Company proxy blocks social media sites

## Reverse Proxy
A reverse proxy sits between the internet and backend servers.

### How it Works
Client → Reverse Proxy → Backend Server

### Uses
- load balancing
- SSL termination (HTTPS handling)
- caching responses
- hiding backend server details
- DDoS protection

Example:
- Nginx reverse proxy forwarding to Node.js servers

## Key Difference
- Proxy protects/hides the client
- Reverse proxy protects/hides the server

## Observations
- Reverse proxies are common in real-world deployments
- Nginx and Apache can act as reverse proxies
- Reverse proxy improves scalability and security
# Day 55
## Focus
Proxy vs Reverse Proxy

## Proxy (Forward Proxy)
A proxy server that sits between the client and the internet.

### How it Works
Client → Proxy → Internet Server

### Uses
- hides client identity (privacy)
- content filtering
- caching
- access control in organizations

Example:
- Company proxy blocks social media sites

## Reverse Proxy
A reverse proxy sits between the internet and backend servers.

### How it Works
Client → Reverse Proxy → Backend Server

### Uses
- load balancing
- SSL termination (HTTPS handling)
- caching responses
- hiding backend server details
- DDoS protection

Example:
- Nginx reverse proxy forwarding to Node.js servers

## Key Difference
- Proxy protects/hides the client
- Reverse proxy protects/hides the server

## Observations
- Reverse proxies are common in real-world deployments
- Nginx and Apache can act as reverse proxies
- Reverse proxy improves scalability and security
