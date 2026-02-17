# Day 80
## Focus
JWT (JSON Web Token) Basics

## What is JWT?
JWT is a token format used for authentication and authorization.

JWT is commonly used in APIs.

---

## JWT Structure
A JWT has 3 parts separated by dots:


Example:

---

## 1. Header
Contains token type and algorithm.
Example:
```json
{
  "alg": "HS256",
  "typ": "JWT"
}
. Payload

Contains user data (claims).
Example:

{
  "userId": 101,
  "role": "admin"
}

3. Signature

Signature is created using:

header

payload

secret key

This ensures the token is not modified.

Why JWT is Used

Stateless authentication

Server does not store session data

Easy to use for microservices

JWT Flow

User logs in

Server creates JWT

Client stores JWT

Client sends JWT in header:

Authorization: Bearer <token>


Server verifies token signature

Observations

JWT payload is not encrypted (only encoded)

Never store passwords inside JWT

JWT is valid until expiry

JWT is popular for REST API authentication
