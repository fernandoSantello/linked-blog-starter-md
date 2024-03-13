A logical division of an address space.

Subnets help you **define different kinds of workloads** and allows you to apply virtual isolation within your network. When you launch an Azure resource you choose the subnet you want to launch within and an IP from that subnet is assigned to your resource.

A subnet needs a [[Route Table]] so it can access the internet or anything at all.

Public and Private subnet describe whether a subnet is a reachable from the internet or not. Azure has no concept of private and public subnets and its up to you to configure the subnets to ensure they do reach the internet by ensuring they have a route via the route table to the Internet Gateway.