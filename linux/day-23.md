# Linux Networking – Day 23

## Concepts Learned
- Client–Server Model: A client sends a request and a server responds with data.
- HTTP: A protocol used for communication between web clients and servers.
- Request–Response Cycle: Client sends a request, server processes it, and returns a response.
- URL: Specifies the address of a resource on the internet.

## Commands Practiced
- curl http://example.com
- curl -I http://example.com
- ss -tuln

## Notes
- curl is used to send HTTP requests from the command line.
- curl -I fetches only HTTP headers from a server.
- HTTP uses TCP as its underlying transport protocol.
- The client–server model is the foundation of web communication.
- ss helps verify which services are listening on which ports.

## Reflection
Today I learned how clients and servers communicate using HTTP and understood the basic request–response cycle of web communication.
