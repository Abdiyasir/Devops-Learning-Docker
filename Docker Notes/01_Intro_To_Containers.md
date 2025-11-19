# Intro To Containers 

## What Containers Are

- Containers are lightweight packages that include an app and everything it needs to run.
- They keep the app’s code, libraries, and settings together in one place.
- This makes sure the app runs the same way everywhere — from development to production.
- Each container is isolated, so one app can’t affect another.

## How Containers Work
- **Infrastructure**: physical/virtual hardware (your laptop/server).
- **Host OS**: operating system running on the infrastructure.
- **Docker Engine**: enables building, running, and managing containers.
- **Containers**: Small isolated environments that run your apps, depending on the docker engine to function.

## Why Containers Are Efficient
- They share the host OS, making them lighter and much faster to start
- “It works on my machine” problem: App runs the same everywhere
- Easier deployment and can scale easily by running multiple container copies 
