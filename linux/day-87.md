# Day 87: TCP Congestion Control

## Why It Exists
If too much data is sent too quickly, the network becomes congested.
This causes packet loss, delay, and retransmissions.

TCP uses congestion control to prevent network collapse.

---

## Key Variable
TCP maintains:

Congestion Window (cwnd)

Actual send window = min(cwnd, receiver window)

---

## Phases

### 1. Slow Start
- Starts with small cwnd (1 MSS)
- cwnd doubles every RTT
- Exponential growth

---

### 2. Congestion Avoidance
- Growth becomes linear
- cwnd increases slowly (1 MSS per RTT)

---

### 3. Fast Retransmit
- 3 duplicate ACKs → retransmit immediately
- No timeout wait

---

### 4. Fast Recovery
- Reduce cwnd
- Avoid full slow start reset

---

## On Timeout
- cwnd resets to 1 MSS
- Enters Slow Start again

---

## Common Algorithms
- Reno
- Cubic (default in Linux)
- BBR

Check current algorithm:

sysctl net.ipv4.tcp_congestion_control
