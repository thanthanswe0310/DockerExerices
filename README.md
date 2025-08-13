# Docker Commands Guide

This repository contains instructions for building, running, and managing Docker containers. Use this guide to get started with Docker commands quickly.

---

## 1. Build a Docker Image

Use the following command to build a Docker image from a Dockerfile in the current directory:

```bash
docker build .

2. Run a Docker Container
Run a Docker container from an image:

docker run <image_id>

You can also map ports between your host and container:

docker run -p 3000:3000 <image_id>

Example:

docker run 318892a86b6ffdc7640a64

3. List All Running Containers
To see all active containers:

docker ps

4. Stop a Running Container
To stop a running container:

docker stop <container_name>
Example:

docker stop hungry_swartz

