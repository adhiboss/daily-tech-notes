# Day 54
## Focus
HTTP Cookies and Sessions

## Why Cookies Exist
HTTP is stateless, meaning the server does not remember the client automatically.
Cookies help maintain user identity across requests.

## Cookie
- Small data stored in browser
- Sent automatically with every request to the same domain

### Common Uses
- login authentication
- user preferences
- tracking

## Cookie Headers
### Server sets cookie:
- `Set-Cookie: sessionid=abc123`

### Browser sends cookie:
- `Cookie: sessionid=abc123`

## Session
- Session is server-side storage of user state
- Cookie usually stores a session ID
- Server maps session ID → user data

## Secure Cookie Flags
- Secure → cookie sent only over HTTPS
- HttpOnly → not accessible from JavaScript (prevents XSS stealing)
- SameSite → reduces CSRF attacks

## Observations
- Cookies are client-side, sessions are server-side
- Secure + HttpOnly are important for security
- Session IDs must be random and unpredictable
