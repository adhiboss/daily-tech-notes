# Linux Networking – Day 32

## Topics Covered
- TCP connection states
- Understanding connection lifecycle
- Identifying active and closed connections

## Commands Practiced
- ss -tan
- ss -tan state established
- ss -tan state time-wait
- ss -tan state listen

## Notes
- TCP connections go through multiple states such as LISTEN, ESTABLISHED, and TIME-WAIT.
- LISTEN indicates a server waiting for connections.
- ESTABLISHED shows active data transfer.
- TIME-WAIT ensures delayed packets are handled safely.
- ss is a powerful tool to inspect socket states.

## Reflection
Today I learned how TCP connections transition through different states and how to inspect them using Linux networking tools.

