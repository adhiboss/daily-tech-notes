# Day 52
## Focus
TCP Flow Control vs Congestion Control

## Flow Control
Flow control ensures the sender does not overwhelm the receiver.

### How it Works
- Receiver advertises a **window size**
- Sender sends only as much data as receiver can handle

### Key Term
- **Sliding Window**
  - Controls how many bytes can be sent before ACK is received

## Congestion Control
Congestion control prevents the sender from overwhelming the network.

### Why Needed
- Network routers have limited buffer space
- Too much traffic causes packet loss and delay

### TCP Congestion Mechanisms
- Slow Start
- Congestion Avoidance
- Fast Retransmit
- Fast Recovery

## Observations
- Flow control protects the receiver
- Congestion control protects the network
- Both are essential for stable TCP performance
