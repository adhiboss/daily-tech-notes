# Day 51
## Focus
TCP 3-Way Handshake and Connection Termination

## TCP 3-Way Handshake
TCP establishes a reliable connection using a 3-step handshake.

### Steps
1. **SYN**
   - Client sends SYN packet to server
   - Requests to start connection

2. **SYN-ACK**
   - Server responds with SYN-ACK
   - Acknowledges client SYN and sends its own SYN

3. **ACK**
   - Client sends ACK back to server
   - Connection is established

## Why Handshake is Needed
- Confirms both sides are reachable
- Synchronizes sequence numbers
- Prevents half-open connections

## TCP Connection Termination (4-Way)
TCP closes using FIN packets.

### Steps
1. Client sends FIN
2. Server sends ACK
3. Server sends FIN
4. Client sends ACK

## TIME_WAIT State
- After closing, client waits in TIME_WAIT state
- Prevents delayed packets from old connection interfering

## Observations
- TCP ensures reliability using acknowledgements
- Connection setup and teardown adds overhead
- UDP avoids handshake but sacrifices reliability
