# Assignment: Multi-App Django Project with Docker and Jenkins

## 📌 Objective
The goal of this assignment is to create a multi-app Django project, containerize it using Docker, and automate deployment with Jenkins.

## 📋 Requirements
1. **Django Project:**
   - Create a Django project named **django_project**.
   - Add at least two apps (e.g., `app1` and `app2`).
   - Each app should have static views and templates.
   - No database should be used.

2. **Dockerization:**
   - Create a `Dockerfile` to containerize the project.
   - Use a Python base image.
   - Install Django and required dependencies.
   - Copy the project into the container and run the Django server.

3. **Jenkins Integration:**
   - Write a `Jenkinsfile` to automate:
     - Pulling the project from GitHub.
     - Building the Docker image.
     - Pushing the image to Docker Hub.

4. **Docker Hub:**
   - Set up a Docker Hub repository.
   - Push the built Docker image to Docker Hub.


