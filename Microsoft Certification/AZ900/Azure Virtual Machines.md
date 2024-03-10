Is a highly configurable server. Virtualization let you run a server without having to buy and maintain the physical hardware that runs it. But they still require maintenance, such as applying [[Operating Systems]] patches and installing and configuring packages.

Some important things about AVMs:
- The size of the virtual machine is determined by the Image (which is a combination of vCPUs, memory and storage capacity);
- The current limit on a per subscription basis is 20 VMs per region;
- Azure VMs are billed at an hourly rate;
- A single instance VMs has an availability of 99.9% (when all storage disks are premium);
- Two instances deployed in Availability Set will give you 99.95% availability;
- You can attach multiple managed disks to your Azure VMs.

When an AVM is launched, other networking components will be either created or associated with this VM:
- **Network Security Group (NSG)**: Attached to the NIC, virtual firewall with rules around ports and protocols;
- **Network Interface (NIC)**: A device that handles IP protocols and network communication;
- **Virtual Machine Instance**: The actual running server;
- **Public IP Address**: The address that you will use to publicly access your VM;
- **Virtual Network (VNet)**: The network where the VM will reside.

	![[Pasted image 20240310110619.png]]

For [[Scalability]] in the AVMs, you can use [[Azure Scale Sets]].
For [[Elasticity]] in the AVMs, you can use [[Azure Scaling Policy]].
