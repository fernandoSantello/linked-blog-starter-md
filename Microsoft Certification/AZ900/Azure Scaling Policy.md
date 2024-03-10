A Scaling Policy determines when a VM should be added or removed to meet current capacity demands and requirements.
Using [[Elasticity]], they can be both Scaled Out and Scaled In.

After you create your [[Azure Scale Sets]], you have a lot more options available to configure the rules of your scaling policy. For example:
### Built-in Host-based metrics:
- Percentage CPU;
- Network In;
- Network Out;
- Disk Read Bytes;
- Disk Write Bytes;
- Disk Read Operations/Sec;
- Disk Write Operations/Sec;
- CPU Credits Remaining;
- CPU Credits Consumed.
### Aggregates:
- Average;
- Minimum;
- Maximum;
- Total;
- Last;
- Count.
### Operators:
- Greater than;
- Greater than or equal to;
- Less than;
- Less than or equal to;
- Equal to;
- Not equal to.
### Actions:
- Increase count by X;
- Increase percent by X%;
- Increase count to X;
- Decrease count by X;
- Decrease percent by X%;
- Decrease count to X.
### Scale-In Policy:
- Determines what VM is removed/deleted to decrease the capacity of the [[Azure Scale Sets]].
	- Default: deletes the VM with the highest instance ID;
	- Newest VM: Deletes the newest created VM;
	- Oldest VM: Deletes the oldest created VM.

### Update Policy:
- Determines how VM instances are brought up-to-date with the latest scale set model.
	- Automatic: Increases with start updating immediately in random order;
	- Manual: Existing instances must be manually upgraded;
	- Rolling: Upgrades roll out in batches with optional pause.
