# Introduction to Docker Compose

## What is Docker Compose
- A tool for managing multi-container Docker applications
- Lets you define all services (web app, database etc.) in a single YML file
- Eliminates the need to start/stop containers one-by-one, can now be done with `docker-compose up`
`docker-compose down`
- Automatically creates a network for all services in the YAML file that can communicate using service names (e.g., mydb, web)
  
