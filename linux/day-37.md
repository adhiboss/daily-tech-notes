# Day 37
## Focus
HTTP request–response lifecycle

## Lifecycle Steps
1. Client resolves server IP using DNS
2. TCP 3-way handshake is established
3. Client sends HTTP request
4. Server processes request
5. Server sends HTTP response
6. Connection is closed or kept alive

## HTTP Request
- Request line (method, path, version)
- Headers
- Optional body (POST)

## HTTP Response
- Status line
- Headers
- Body

## Observations
- HTTP is stateless
- TCP handles reliability
- Persistent connections reduce overhead
