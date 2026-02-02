# Day 36
## Focus
Threaded network servers

## What I Learned
- Single-threaded servers block on client handling
- Threads allow multiple clients to be served concurrently
- Thread-per-connection is simple but not scalable

## Concepts
- pthread_create()
- join vs detach
- race conditions

## Observations
- Concurrency improves responsiveness
- Resource management becomes critical
