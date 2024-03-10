An Availability Zone (AZ) is a physical location made up of one or more datacenters.

A datacenter is a secure building that contains hundreds of thousands of computers.

A region will generally contain three Availability Zones.

Datacenter within a region will be isolated from each other (in different buildings, for example). But they will be close enough to provide low-latency.

It's common practice to run workloads in at least 3 AZs to ensure services remain available in case one or two datacenters fail ([[Availability]]).

Not every region has support for Availability Zones. These region are know as **Alternate or Other. Recommend** regions are supposed to have at least three AZs.

An AZ in an Azure region is a **combination of** a [[Fault Domain]] and an [[Update Domain]].