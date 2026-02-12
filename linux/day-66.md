# Day 66
## Focus
TCP Retransmission and Packet Loss Basics

## Why Retransmission Happens
TCP guarantees reliable delivery.
If a packet is lost, TCP resends it.

## How TCP Detects Packet Loss
### 1. Timeout (RTO)
- Sender waits for ACK
- If ACK not received in time → resend packet

### 2. Duplicate ACKs
- Receiver keeps sending ACK for last received packet
- After multiple duplicate ACKs, sender assumes loss

## Fast Retransmit
- If sender receives 3 duplicate ACKs
- It retransmits packet immediately (no timeout wait)

## Observations
- Retransmission increases latency
- Packet loss affects throughput
- TCP is designed to handle unreliable networks
