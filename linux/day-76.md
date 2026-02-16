# Day 76
## Focus
HTTP Sessions (Login Flow)

## What is a Session?
A session is a server-side storage of user login information.

Because HTTP is stateless, sessions help servers remember users.

---

## How Session Works
1. User logs in (username/password)
2. Server verifies credentials
3. Server creates a session ID
4. Server stores session in memory/database
5. Server sends session ID as cookie to browser
6. Browser sends cookie in every request
7. Server checks session ID and identifies user

---

## Example Cookie
Server sends:
Set-Cookie: sessionid=xyz123Set-Cookie: sessionid=xyz123

Browser sends:

---

## Why Sessions are Needed
- user authentication
- maintaining login state
- tracking user actions

---

## Session Storage
Sessions can be stored in:
- RAM (fast but resets on restart)
- Database
- Redis (most common)

---

## Observations
- Cookies store session ID
- Session data stays on server
- Sessions expire after timeout
- Session hijacking is a security risk

