# Docker Notes

## Introduction

Docker is a platform for packaging and running applications in containers.

## Important Docker Commands

| Command | Purpose |
|---|---|
| `docker --version` | Display the Docker version |
| `docker ps` | List running containers |
| `docker ps -a` | List all containers |
| `docker images` | List local images |
| `docker pull <image>` | Download an image |
| `docker build -t <name> .` | Build an image from a Dockerfile |
| `docker run <image>` | Create and start a container |
| `docker logs <container>` | View container logs |
| `docker stop <container>` | Stop a running container |
| `docker rm <container>` | Remove a container |
| `docker rmi <image>` | Remove an image |

## Docker Concepts

- **Image:** A template used to create containers.
- **Container:** An isolated runtime instance of an image.
- **Dockerfile:** Instructions used to build an image.
- **Registry:** A service for storing and distributing images.

## Best Practices

- Prefer trusted base images.
- Avoid embedding secrets in Docker images.
- Use `.dockerignore` to exclude unnecessary build-context files.
- Inspect container logs when troubleshooting.
