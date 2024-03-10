A Load Balancer can be associated with a [[Azure Scale Sets]]. This allows to:
- Evenly distribute VMs across multiple [[Availability Zones]] to make your application have [[Availability]];
- Use Load Balancer to probe checks for more robust Health Checks.

There are two types of Load Balancer:
- **Azure Application Gateway**: Is an HTTP/HTTPS web traffics load balancer with URL based routing, SSL termination, session persistence and web application firewall. Designed to handle web traffic.;
- **Azure Load Balancer**: Supports all TCP/UDP network traffics, port-fowarding and outbound flows. Designed to distribute network traffic across multiple machines.