# Understanding VMs vs Containers

## Virtual Machines (VMs)
- Allow multiple full operating systems to run on one physical machine using hypervisor software
- The hypervisor is the software layer that creates and manages the VMs.
- Each VM has a full guest operating system & it's own binaries, libraries, and dependencies
- They are heavy and use alot of CPU
- Slow startups as it has to boot an entire OS
- Strong isolation as it acts like a seperate computer
- Less portable as it has large files

## Containers
-Allow multiple applications to run in isolated environments on one physical machine using Docker Engine
- Share the host OS kernel
- Each container include the app and binaries/libraries it needs
- Much smaller and faster than VMs
- Containers are isolated so apps don't interfere with each other
- Runs the same everywhere
