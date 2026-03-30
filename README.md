## 🚀 Project Overview

This project demonstrates how to containerize a simple Java program using Docker and automate the build and deployment process with GitHub Actions. 

The application prints “Hello, Docker World!” and is packaged into a Docker image. A GitHub Actions workflow is triggered on each push to the `master` branch, which builds the image and pushes it to Docker Hub using secure credentials.

**Key Components:**
- Java program (`HelloWorld.java`)
- Dockerfile to build and run the application
- GitHub Actions workflow to automate build and push
- Docker Hub repository to store the image
