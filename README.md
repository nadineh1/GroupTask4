## Project Overview

This project demonstrates how to containerize a simple Java program using Docker and automate the build and deployment process with GitHub Actions.

Docker is used to package the Java application into a container so it can run consistently in any environment. GitHub Actions is used to automatically build the Docker image and push it to Docker Hub whenever changes are pushed to the repository.

The application prints “Hello, Docker World!” and is stored as a Docker image on Docker Hub.

**Key Components:**
- Java program (`HelloWorld.java`)
- Dockerfile to build and run the application
- GitHub Actions workflow to automate build and push
- Docker Hub repository to store the image
