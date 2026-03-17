# Linux Process Monitoring

Monitoring running processes is essential for diagnosing performance issues and understanding system behavior.

## Useful Commands

### 1. ps
Displays information about running processes.

Example:

ps aux

Important columns:

USER – process owner  
PID – process ID  
%CPU – CPU usage  
%MEM – memory usage  
COMMAND – process name

---

### 2. top

Shows real-time process activity.

Run:

top

Key information:

- CPU usage
- memory usage
- running processes
- system load

Press **q** to exit.

---

### 3. htop

Improved interactive process viewer.

Install:

sudo apt install htop

Run:

htop

Features:

- colored interface
- process tree view
- easy process management

---

### 4. kill

Terminates a process.

Example:

kill PID

Force terminate:

kill -9 PID

---

## Why Process Monitoring Matters

Process monitoring helps detect:

- high CPU usage
- memory leaks
- misbehaving services
- system performance issues

System administrators and DevOps engineers regularly use these tools to troubleshoot infrastructure problems.
