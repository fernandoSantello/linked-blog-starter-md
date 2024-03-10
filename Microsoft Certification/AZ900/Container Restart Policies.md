A Container Restart Policy specifies what a container should do when their process has completed. Azure Container Instances has three restart-policy options:
- **Always**: Container are always restarted. Suited for long running tasks, like web servers;
- **Never**: Containers run one time only. Suited for one off tasks, like simple background jobs;
- **OnFailure**: Containers that encounter an error.