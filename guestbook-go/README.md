## Assignment Overview

This repository contains the solution to the Kubernetes assignment, which includes:

1. Phase I: GitHub Actions for Docker Image
2. Phase II: Kubernetes Deployment
3. Phase III: GitHub Actions Conditions and Branch Protection

## Phase I: GitHub Actions for Docker Image

- Repository Creation: Created a public GitHub repository based on the guestbook-go example.
- Workflow File: Implemented a GitHub Actions workflow (`docker-image.yml`) to build and push the Docker image to Docker Hub.

### Workflow Details
- Trigger: The workflow runs on pushes to the `master` branch and when commit messages contain `BUILD_CONTAINER_IMAGE`.
- Docker Image: The image is pushed to Docker Hub under `rcamith/my-app-image:latest`.

## Phase II: Kubernetes Deployment

- Kubernetes Deployment: Deployed the Docker image to a local Kubernetes cluster.
- Service: Exposed the application using a NodePort service.

- ## Proof of Completion
- ![Screenshot (247)](https://github.com/user-attachments/assets/9ee9051d-6604-4d2f-acd5-bc11d97feca1)

- ![image](https://github.com/user-attachments/assets/7ef552ef-5be2-45a5-9dfc-159d4e6f0965)

