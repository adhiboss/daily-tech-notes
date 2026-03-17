# Day 92 — Linux Process States

In Linux, every running program is represented as a **process**. Each process goes through different states during its lifecycle.

## Common Process States

R – Running  
The process is currently executing or ready to run.

S – Sleeping  
The process is waiting for an event (most common state).

D – Uninterruptible Sleep  
The process is waiting for I/O operations such as disk access.

T – Stopped  
The process has been stopped by a signal or debugger.

Z – Zombie  
The process has finished execution but still has an entry in the process table.

## View Process States

Use:

Example output:

Example output:
USER PID %CPU %MEM STAT COMMAND
root 1 0.0 0.1 Ss systemd
adhi 2345 0.1 0.3 R python

The **STAT column** shows the process state.

## Why This Matters

Understanding process states helps with:

- debugging system issues
- diagnosing stuck processes
- analyzing system performance
- managing system resources

Linux administrators frequently inspect process states when troubleshooting system behavior.
