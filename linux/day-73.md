# Day 73
## Focus
HTTP/2 Basics (Multiplexing and Performance)

## What is HTTP/2?
HTTP/2 is an improved version of HTTP/1.1 designed to improve speed and performance.

It still uses the same HTTP methods (GET, POST, etc.) but changes how data is transmitted.

---

## Problems with HTTP/1.1
- Multiple requests can block each other (head-of-line blocking)
- Browser opens many TCP connections for parallel downloads
- Higher latency and more overhead

---

## HTTP/2 Key Features

### Multiplexing
- Multiple requests/responses can happen simultaneously over one TCP connection.
- No need for multiple connections.

### Binary Protocol
- HTTP/2 uses binary frames instead of text.
- Faster and more efficient parsing.

### Header Compression
- Uses HPACK compression
- Reduces bandwidth usage

### Server Push (Optional)
- Server can send resources before client requests them
- Improves page load speed (but not always used)

---

## Observations
- HTTP/2 is faster than HTTP/1.1
- Multiplexing is the biggest improvement
- Most modern browsers use HTTP/2 automatically over HTTPS
