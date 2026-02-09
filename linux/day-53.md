# Day 53
## Focus
DNS Record Types (A, AAAA, CNAME, MX, TXT, NS)

## A Record
- Maps domain name to IPv4 address
- Example:
  google.com → 142.250.x.x

## AAAA Record
- Maps domain name to IPv6 address

## CNAME Record
- Alias for another domain name
- Example:
  www.example.com → example.com

## MX Record
- Mail exchange record
- Specifies mail server for a domain
- Example:
  example.com → mail.example.com

## TXT Record
- Stores text-based data
- Used for:
  - domain verification
  - SPF/DKIM email security
  - ownership proof

## NS Record
- Defines authoritative name servers for a domain
- Tells where DNS queries should be handled

## Observations
- DNS records control routing of web and email traffic
- Misconfigured DNS causes downtime
- CNAME is useful for managing subdomains
