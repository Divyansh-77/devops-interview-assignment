# DevOps Interview Assignment

# Overview
Simple Python web application containerized with Docker and deployed using GitHub Actions CI/CD pipeline.

## Application
The application exposes "Hello World" on port 8000.

## Docker
Dockerfile builds the image and runs the application.

# CI/CD Pipeline
GitHub Actions pipeline:
 builds Docker image
 tags image with git commit id and latest
 pushes image to DockerHub

# Webhook Automation
Webhook listener pulls the latest Docker image and restarts the container automatically.

# Screenshots
(screenshots folder)