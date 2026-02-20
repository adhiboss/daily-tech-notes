# Day 81
## Focus
Rate Limiting in APIs

## What is Rate Limiting?
Rate limiting controls how many requests a client can send in a given time.

It prevents:
- abuse
- DDoS attacks
- brute force login attempts
- server overload

---

## Example
Allow:
100 requests per minute per IP.

If limit exceeded:
Server returns:
429 Too Many Requests

---

## Methods of Rate Limiting
- IP based
- User based
- Token based

---

## Common Algorithms
- Fixed window
- Sliding window
- Token bucket
- Leaky bucket

---

## Observations
- Rate limiting protects backend services
- 429 status code indicates limit exceeded
- Often implemented in API gateways
