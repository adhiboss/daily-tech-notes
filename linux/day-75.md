# Day 75
## Focus
HTTP Cookies Basics

## What are Cookies?
Cookies are small pieces of data stored in the browser.
They are sent to the server with every request.

## Why Cookies are Used
- session management
- user login tracking
- personalization
- storing preferences

## Set-Cookie Header
Server sends cookie using:

Browser stores it.

## Cookie Header
Browser sends cookie back:

## Types of Cookies
- Session cookie (deleted when browser closes)
- Persistent cookie (stored with expiry)

## Security Flags
- HttpOnly (not accessible via JS)
- Secure (sent only on HTTPS)
- SameSite (prevents CSRF)

## Observations
Cookies are important for authentication and maintaining user sessions.
