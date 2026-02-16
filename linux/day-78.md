# Day 78
## Focus
CORS (Cross-Origin Resource Sharing) Basics

## What is CORS?
CORS is a browser security rule that controls which websites can access resources from another domain.

It prevents unauthorized cross-site API access.

---

## What is an Origin?
Origin = Protocol + Domain + Port

Example:
https://example.com:443

Different origins:
- http vs https
- different domain
- different port

---

## CORS Example
Frontend running on:http://localhost:3000

Backend API running on:http://localhost:5000

Browser blocks requests unless backend allows it.

---

## CORS Header
Server allows origin using:Access-Control-Allow-Origin: http://localhost:3000
allow all
Access-Control-Allow-Origin: *

---

## Preflight Request (OPTIONS)
For some requests (PUT/DELETE/POST with JSON), browser sends an OPTIONS request first.

This checks permissions before real request.

---

## Common CORS Headers
- Access-Control-Allow-Origin
- Access-Control-Allow-Methods
- Access-Control-Allow-Headers
- Access-Control-Allow-Credentials

---

## Observations
- CORS is enforced by browsers, not servers
- Servers must allow cross-origin access explicitly
- Preflight OPTIONS is common in API calls




