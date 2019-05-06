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
