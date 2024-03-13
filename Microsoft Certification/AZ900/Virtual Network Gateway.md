A VPN extends a private network across a public network and enables users to send and receive data across shared or public networks as if their compute device were directly connected to the private network.

A Virtual Network Gateway is the software VPN device for your Azure virtual network. When you deploy a virtual network gateway it will deploy two or specialized VMs in a specific subnet you need to create called "gateway subnet".

These deployed VMs contain routing tables and run specific gateway services.

You will choose a Gateway Type and that will determine if it's a VPN Gateway or an ExpressRoute Gateway. 

If you pick the VPN Gateway door, you're choosing to connect in a way that's like a secure, private tunnel. If you choose the ExpressRoute Gateway door, you're picking a different, also secure, but more direct and possibly faster way to get in.

- **VPN Gateway**: Secure and private connection over the public internet, like a private tunnel.
- **ExpressRoute Gateway**: A direct and private connection that bypasses the public internet altogether, like a private road.