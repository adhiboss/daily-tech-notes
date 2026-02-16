# Day 77
## Focus
CSRF (Cross-Site Request Forgery) Basics

## What is CSRF?
CSRF is an attack where a user is tricked into sending an unwanted request to a website where they are already logged in.

The browser automatically sends cookies, so the request looks valid.

---

## Example Scenario
1. User logs into bank website
2. Session cookie is stored in browser
3. User visits attacker website
4. Attacker triggers a request to bank website
5. Browser sends bank cookies automatically
6. Bank thinks it is a real user request

---

## Why CSRF Works
- Cookies are sent automatically by the browser
- Server trusts the cookie/session

---

## CSRF Protection Methods
### 1. CSRF Token
Server sends unique token.
Client must send token back in POST requests.

### 2. SameSite Cookies
Cookie option:
- SameSite=Strict
- SameSite=Lax

Prevents cookie from being sent to other sites.

### 3. Verify Referer/Origin Header
Server checks request source.

---

## Observations
- CSRF mainly affects state-changing requests (POST/DELETE)
- GET requests usually should not change server data
- SameSite cookies are a strong modern defense
