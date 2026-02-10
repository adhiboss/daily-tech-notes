# Day 56
## Focus
Load Balancing Algorithms

## What is Load Balancing?
Load balancing distributes incoming traffic across multiple servers to improve:
- performance
- reliability
- scalability

## Common Load Balancing Algorithms

### Round Robin
- Requests are distributed sequentially
- Simple and widely used
- Does not consider server load

### Weighted Round Robin
- Servers get traffic based on assigned weight
- Powerful when servers have different capacities

### Least Connections
- Sends traffic to the server with the fewest active connections
- Works well for long-lived connections

### IP Hash
- Uses client IP to decide backend server
- Same client often hits the same server
- Useful for session persistence

## Observations
- Reverse proxies like Nginx can load balance
- Least connections is better for uneven workloads
- Load balancing is essential in production systems
