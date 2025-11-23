# Understanding Docker Networking

- It controls how containers talk to each other, how they talk to the host machine, and how they reach the outside world (internet).
- Essential for microservices, DevOps workflows, and multi-container applications.

## Bridge Network (Default)
- Default network for containers on the same machine
- Containers get their own IP addresses
- Containers on the same bridge can communicate
- Isolated from the host’s main network which adds security
- Best for: most applications running on one machine

## Host Network
- Container shares the host’s network directly
- No isolation — container uses host’s ports & IP
- Best for: apps needing high performance or deep host integration

## None Network
- Container gets no network access
- Completely isolated (no inbound/outbound traffic)
- Best for: high-security workloads

