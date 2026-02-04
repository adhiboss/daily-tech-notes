# Day 40
## Focus
Persistent connections and keep-alive

## Notes
- HTTP/1.1 uses persistent connections by default
- Keep-Alive reduces repeated TCP handshakes
- Improves latency and throughput
- Server controls timeout and max requests per connection

## Observations
- Efficient for multiple small requests
- Idle connections consume server resources
