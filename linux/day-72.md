# Day 72
## Focus
HTTP Keep-Alive and Persistent Connections

## What is HTTP Keep-Alive?
Keep-Alive allows multiple HTTP requests and responses to use the same TCP connection.

Instead of opening a new TCP connection for every request, the connection stays open.

---

## Why Keep-Alive is Important
- reduces TCP handshake overhead
- improves performance
- reduces latency
- saves server resources

---

## Without Keep-Alive
For every request:
- TCP handshake happens
- request sent
- response received
- connection closed

This is slow for websites with many resources.

---

## With Keep-Alive
- one TCP connection is reused
- multiple requests are sent over the same connection

---

## Header Used
Request header:
