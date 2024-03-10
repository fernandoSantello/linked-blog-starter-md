Azure Container Instances (ACI) allows you to launch containers without the need to worry about configuring or managing the underlying virtual machine. It is designed for **isolate containers**, that are simple applications, that are a task automation or that build jobs.

Let's compare it with [[Azure Virtual Machines]]:
- Containers can be provisioned within seconds, whereas a VM can take several minutes;
- Containers are billed per second whereas VMs are billed per hour;
- Containers have granular and custom sizing of vCPUs, memory and GPUs, whereas VMs sizes are predetermined.

Some qualities of ACI:
- Can deploy both Windows and Linux containers;
- You can persist storage with Azure Files for your ACI containers;
- ACIs are accessed via a fully qualified domain name (just like a website).

If you want to deploy a conjunction of containers, you can use [[Containers Groups]].

You can set up one of the [[Container Restart Policies]] for your containers.

For configuration details, you can just set up [[Container Environment Variables]].

To maintain a state in an ACI, you can use [[Container Persistent Storage]].