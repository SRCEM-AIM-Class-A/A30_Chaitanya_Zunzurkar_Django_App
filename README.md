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


## 🚀 Technologies Used
- Django (Python)
- Docker
- Jenkins
- Git & GitHub

## 🛠 How to Run the Project

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/SRCEM-AIM-Class-A/A30_Chaitanya_Zunzurkar_Django_App
cd django_project


### Build and Run with Docker
Ensure you have **Docker installed** before proceeding.

Now, visit **http://localhost:8000/** in your browser to access the application.

### Run with Docker Hub (Alternative)
If you prefer to pull and run the pre-built image from Docker Hub, use:


### Setting Up Jenkins Pipeline
1. Install **Jenkins** and required plugins.
2. Create a new **Pipeline Job** in Jenkins.
3. Configure the job to pull from your GitHub repository.
4. Add pipeline script from **Jenkinsfile**.
5. Run the Jenkins job to automate the build and push process.
