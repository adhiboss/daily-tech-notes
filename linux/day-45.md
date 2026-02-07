# Day 45
## Focus
Ports, Sockets, bind() and listen()

## Port
- A number used to identify services on a machine
- Example: 80 for HTTP, 22 for SSH

## Socket
- A software endpoint for communication
- Combination of:
  - IP address
  - Port number
  - Protocol (TCP/UDP)

## bind()
- Assigns a port to a socket
- Required for servers

## listen()
- Marks a socket as a passive socket
- Allows incoming connection requests

## accept()
- Accepts a client connection
- Returns a new socket for that client

## Observations
- Server uses bind() + listen() + accept()
- Client uses connect()
- One server can handle multiple clients with concurrency
