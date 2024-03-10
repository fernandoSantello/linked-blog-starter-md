Health Monitoring can be enabled to determine if your server is **healthy or unhealthy.**

There are two modes of health monitoring:
- **Application Health Extension**: Ping an HTTP request to a specific path and expect a status 200;
- **Load Balancer Probe**: Checks based on TCP, UDP or HTTP requests.

If an instance is found to be unhealthy, an Automatic Repair Policy can be set up, that deletes it and launches a new instance.