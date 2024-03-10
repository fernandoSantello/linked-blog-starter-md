Ability for the service to **==remain available==** by ensuring there is **==no single point of failure==** and/or ensure a certain level of performance.

![[Pasted image 20240309221659.png]]

Running the workload across multiple Availability Zones ensures that if one or two AZs become unavailable, your service remains available. If one goes down, another takes it's place.

This is done using [[Azure Load Balancer]].