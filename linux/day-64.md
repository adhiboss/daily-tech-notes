# Day 64
## Focus
HTTP Status Codes (1xx to 5xx)

## 1xx (Informational)
- Request received, processing continues
Example:
- 100 Continue

## 2xx (Success)
- Request was successful
Examples:
- 200 OK
- 201 Created
- 204 No Content

## 3xx (Redirection)
- Resource moved or redirect required
Examples:
- 301 Moved Permanently
- 302 Found
- 304 Not Modified

## 4xx (Client Errors)
- Client sent wrong request
Examples:
- 400 Bad Request
- 401 Unauthorized
- 403 Forbidden
- 404 Not Found

## 5xx (Server Errors)
- Server failed to process valid request
Examples:
- 500 Internal Server Error
- 502 Bad Gateway
- 503 Service Unavailable
- 504 Gateway Timeout

## Observations
- 4xx means client issue
- 5xx means server/backend issue
- 301 is permanent redirect (SEO important)
- 502 often occurs with reverse proxy issues
