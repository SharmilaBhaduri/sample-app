# Sample App

A cloud-native sample application written in **Go (Golang)** and deployed on **Google Kubernetes Engine (GKE)** using Kubernetes YAML manifests.

## Overview

This project demonstrates how to build, containerize, and deploy a Go application to a Kubernetes cluster running on Google Cloud Platform (GCP).

The application showcases modern cloud-native development practices, including containerization, orchestration, and infrastructure-as-code deployment.

## Features

* Developed with Go (Golang)
* Docker container support
* Kubernetes deployment using YAML manifests
* Google Kubernetes Engine (GKE) integration
* Scalable and portable cloud-native architecture
* Infrastructure managed as code
* CI/CD ready deployment workflow

## Technologies Used

* Go (Golang)
* Docker
* Kubernetes
* Google Kubernetes Engine (GKE)
* Google Cloud Platform (GCP)
* YAML
* Git & GitHub

## Project Structure

```text
sample-app/
├── cmd/
├── pkg/
├── deployment.yaml
├── service.yaml
├── Dockerfile
├── go.mod
├── go.sum
└── README.md
```

## Prerequisites

* Go 1.20+
* Docker
* Kubernetes Cluster
* kubectl
* Google Cloud SDK

## Running Locally

Clone the repository:

```bash
git clone https://github.com/your-username/sample-app.git
cd sample-app
```

Install dependencies:

```bash
go mod tidy
```

Run the application:

```bash
go run .
```

## Build Docker Image

```bash
docker build -t sample-app .
```

Run the container:

```bash
docker run -p 8080:8080 sample-app
```

## Deploy to Kubernetes

Apply the Kubernetes manifests:

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

Verify deployment:

```bash
kubectl get pods
kubectl get services
```

## Learning Objectives

This project demonstrates:

* Go application development
* Docker containerization
* Kubernetes deployment
* Google Cloud Platform services
* Infrastructure as Code (IaC)
* Cloud-native application architecture

## Author

http://EXTERNAL-IP

https://sample-app.yourdomain.com

Sharmila Bhaduri

## License

This project is licensed under the MIT License.
