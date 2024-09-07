# Dockerize-a-Django-Application

This repository contains a Docker setup for a Django application, allowing you to easily build and deploy your Django project within a containerized environment.


### 1. Build the Docker Image

Build the Docker image using the provided Dockerfile

    docker build -t my-django-app .

### 2. Run the Docker container
Once the image is built, you can run the Django app inside a Docker container:

    docker run -p 8080:8000 my-django-app

### 3. Access the Application
Your Django application will be running at
    
    http://localhost:8080

