# Catalogue Microservice Repository

Welcome to the "Catalogue Microservice" repository! This repository hosts a powerful microservice that's a key component of our project. With streamlined deployment using Helm, CI/CD capabilities through Jenkins, and a well-structured directory layout, we're setting up the stage for efficient development and deployment.

## Key Features

- **Catalogue Microservice**: Our "catalogue" microservice provides essential functionalities for managing product catalog information.

- **Jenkins CI/CD Pipeline**: We've incorporated a robust Jenkins pipeline (Jenkinsfile) that automates building, testing, and deploying the "catalogue" microservice.

- **Docker Containerization**: We containerize the "catalogue" microservice using a Dockerfile, making it easy to run and scale in any containerized environment.

- **Source Code**: The source code for the "catalogue" microservice can be found in the `src/` directory. You can easily modify and extend its functionalities.

- **Helm for Deployment**: We use Helm charts to deploy the "catalogue" microservice, enabling consistent and repeatable Kubernetes deployments. The Kubernetes Deployment YAML file (manifest.yaml) is included in the `helm/` directory.

## Directory Structure

- `helm/`: Contains Helm chart for deploying the "catalogue" microservice.
  - `manifest.yaml`: Kubernetes Deployment YAML file.
- `src/`: Source code for the "catalogue" microservice.
- `Dockerfile`: Dockerfile for building the container image.
- `Jenkinsfile`: Jenkins pipeline configuration for CI/CD.

## Getting Started

To get started with this repository, follow these steps:

1. Clone the repository to your local development environment.

2. Explore the `src/` directory to work on the source code of the "catalogue" microservice.

3. Use the Dockerfile to build a container image for the microservice. Deploy and scale the microservice using the Docker image.

4. Utilize the Jenkins pipeline (Jenkinsfile) for automated building, testing, and deployment of the "catalogue" microservice.

5. Deploy the microservice to your Amazon EKS cluster using Helm and the provided Kubernetes Deployment YAML file.



---

This README emphasizes the robustness of your repository, showcasing the "catalogue" microservice, CI/CD capabilities, and well-organized project structure. It demonstrates your commitment to efficient development and deployment, which is sure to impress your team lead.
