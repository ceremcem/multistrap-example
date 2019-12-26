# Multistrap Example

This scripts are intended to create a Debian rootfs from scratch for: 

1. Use as LXC container:
		
	```console
	root@host:# ./build.sh 
	# only once after the build phase:
	root@debian:# /config-rootfs.sh 
	```

2. Create a fully bootable distro/installation:

	1. Follow the step #1
	2. Follow ./install-to-disk/README.md

# Install 

```
apt-get install multistrap
```
