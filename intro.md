## Why Use Docker?
 1. Dev/Prod parody
 2. Simplifying Configuration
 3. Code Pipeline Management
 4. Developer Productivity
 5. App Isoliation
 6. Server Consolidation
 7. Debugging Capabilities
 8. Multi-tenancy

## Docker Architecture
Docker architecture:
1. Client-server architecture
2. Client talks to the Docker daemon
3. The Docker daemon handles:
 - Building
 - Running
 - Distributing
4. Both communicate using a REST API:
 - UNIX sockets
 - Network interface

## The Docker daemon (dockerd):
Listens for Docker API requests and manages Docker objects:
 - Images
 - Containers
 - Networks
 - Volumes

## The Docker client (docker):
 - Is how users interact with Docker
 - Sends commands to dockerd
 
## Docker registries:
 - Stores Docker images
 - Public registry such as DockerHub
 - Let you run your own private registry

## Docker objects:
 ### Images:
 - Read-only template with instructions for creating a Docker container 
 - Image is based on another image
 - Create your own images
 - Use images published to a registry
 - Use a Dockerfile to build images
 ### Containers:
 - Runnable instance of an image
 - Connect a container to networks
 - Attach storage
 - Create a new image based on its current state
 - Isolated from other containers and the host machine
 ### Services
 - Scale containers across multiple Docker daemons
 - Docker Swarm
 - Define the desired state
 - Service is load-balanced
