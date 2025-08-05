🚀 Task 2 - Jenkins CI/CD Pipeline using Docker

📌 Description

This project showcases a basic Jenkins CI/CD pipeline that automates the build and deployment process of a Dockerized application.

Using Jenkins, we clone the source code, build a Docker image, log in to Docker Hub, push the image, and finally deploy it (optionally to a remote server or local Docker engine).

---
🎯 Objective

> Set up a Jenkins pipeline to automate building and deploying a Docker-based application.

---

🔧 Tools & Technologies

- Jenkins
- Docker
- GitHub
- Shell Script
- (Optional) Remote Linux Server

---

🚀 Jenkins CI/CD Pipeline with Docker (Single Instance)

This project sets up a full CI/CD pipeline using Jenkins and Docker, all within a **single EC2 instance**. The goal is to automate the process of fetching source code, building a Docker image, pushing it to Docker Hub, and deploying it on the same machine.

---

🚀 How It Works

1. Jenkins pulls the source code from this GitHub repository.
2. Jenkins builds a Docker image using the Dockerfile.
3. Jenkins logs in to Docker Hub using stored credentials.
4. The built image is pushed to Docker Hub.
5. Jenkins then runs the Docker container locally on the same EC2 instance using a specified port.

---

✅ Prerequisites

- Jenkins installed and running on your EC2 instance.
- Docker installed and configured on the same instance.
- Docker Hub account.
- Docker Hub credentials configured in Jenkins (using `usernamePassword` credentials).
- Open port (e.g., `61`) in your EC2 security group for browser access.
- Git installed.
- Basic HTML or app code inside the GitHub repository.

---
