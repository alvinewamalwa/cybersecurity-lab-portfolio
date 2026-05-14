# Process and Network Connection Monitoring

## Task
Identify active processes and suspicious network connections.

## Commands Used
- ps
- netstat
- grep
- lsof

## Execution
ps aux | grep ssh
netstat -tulnp
lsof -i

## Result
Active processes and listening network ports were displayed, including services running on the system.

## Security Insight
Monitoring processes and network connections helps detect unauthorized services or suspicious outbound connections in real-time.
