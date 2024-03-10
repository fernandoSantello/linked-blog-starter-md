ACIs are **stateless** by default. When a container crashes or stops all state is lost. To persist a state you need to **mount** an external volume.

You can mount the following external volumes:
- Azure Files (File Share);
- Secret Volume;
- Empty Directory;
- Cloud git repository.

T mount a file volume you need to do it via PowerShell or CLI and specify the details to mount the hard drive.

![[Pasted image 20240310201314.png]]