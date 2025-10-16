# Kaiburr Task 2: Kubernetes Deployment

This repository contains the solution for Kaiburr Assessment Task 2, which involves containerizing and deploying a Java Spring Boot application to a Kubernetes cluster.

## Submission Requirements

* **README File**: This file includes a clear description of the application, how to deploy it to Kubernetes, and embedded screenshots.
* **Kubernetes Manifests**: The application is deployed using Kubernetes YAML manifests, not Docker Compose files.
* **Screenshots**: All screenshots include the current date and time along with my name (Chandan Boyina) to prove the work is my own.
* **AI Usage**: AI models were used to assist in writing the code and troubleshooting issues, but I wrote and understand all submitted code.

---

## Deployment Instructions

### 1. Prerequisites

* **Java JDK 17+**: Required to build the application.
* **Maven**: Required to package the application.
* **Docker Desktop**: Used to build the Docker image and provides a local Kubernetes cluster.
* **kubectl**: The command-line tool for interacting with the Kubernetes cluster.

### 2. Build and Push the Docker Image

First, build the application's executable JAR file. From your project's root directory, run:
```bash
mvnw.cmd clean package
