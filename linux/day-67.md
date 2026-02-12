# Day 67
## Focus
TCP Window Size and Throughput

## What is TCP Window Size?
TCP window size is the amount of data a sender can send before receiving an acknowledgement (ACK).

It is part of TCP flow control.

## Sliding Window Concept
- Sender sends multiple packets without waiting for ACK after each packet
- Receiver acknowledges received bytes
- Window "slides" forward as ACKs arrive

## Why Window Size Matters
- Larger window size = better throughput (especially in high latency networks)
- Small window size = slow transmission because sender waits often

## Bandwidth-Delay Product (BDP)
Throughput depends on:
- bandwidth
- round trip time (RTT)

High RTT networks need larger windows to fully utilize bandwidth.

## Window Scaling
TCP uses window scaling to support large window sizes beyond 65535 bytes.

## Observations
- Window size affects speed and performance
- TCP scaling improves performance on modern networks
- High latency + small window = low throughput
