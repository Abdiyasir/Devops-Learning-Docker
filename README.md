# Docker Learning





| Command | Description |
|--------|-------------|
| `docker --version` | Shows the installed Docker version. |
| `docker info` | Displays detailed Docker system information. |
| `docker images` | Lists all images stored locally on your machine. |
| `docker inspect <image-id>` | Shows detailed metadata about an image. |
| `docker rmi <image-id>` | Deletes a local Docker image. |
| `docker system prune` | Cleans unused containers, images, networks, and cache. |
| `docker ps` | Shows running containers. |
| `docker ps -a` | Shows all containers (running + stopped). |
| `docker build -t <image-name> .` | Builds a Docker image from a Dockerfile in the current directory. |
| `docker run <image-name>` | Runs a container from an image. |
| `docker stop <container-id>` | Stops a running container. |
| `docker rm <container-id>` | Removes (deletes) a stopped container. |
| `docker network ls` | Lists all Docker networks. |
| `docker network create <network-name>` | Creates a new custom Docker network. |
| `docker network connect <network-name> <container>` | Connects a container to a network. |
| `docker run -d -p <host-port>:<container-port> --name <container-name>` | Runs a container in detached mode with port mapping and a custom name. |
| `docker run -d --name <db-container> --network <network-name> -e MYSQL_ROOT_PASSWORD=<password> mysql:8` | Runs a MySQL container on a custom network with environment variables. |
| `docker-compose up` | Starts all services defined in a docker-compose.yml file. |
| `docker-compose down` | Stops and removes all services from docker-compose.yml. |
| `docker build -t <username>/<repo>:v1 .` | Builds an image and tags it for pushing to Docker Hub or ECR. |
| `docker pull <username>/<repo>:v1` | Pulls an image from a container registry. |



