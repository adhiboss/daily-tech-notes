# Day 42
## Focus
DNS resolution flow and caching

## DNS Resolution Steps
1. Application queries local resolver
2. Resolver checks browser / OS cache
3. Query sent to recursive DNS resolver
4. Resolver contacts root server
5. Root points to TLD server
6. TLD points to authoritative server
7. IP address returned to client

## DNS Records
- A / AAAA → IP address
- CNAME → alias
- MX → mail servers
- NS → name servers

## Caching
- DNS responses are cached using TTL
- Reduces latency and DNS load
- Stale records can cause resolution issues

## Observations
- DNS is critical for networking
- Most latency is avoided due to caching
- DNS issues often look like “network down”
