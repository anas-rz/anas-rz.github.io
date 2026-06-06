---

layout: page
title: Facial Recognition Deployment with PostgreSQL and pgvector
description: Scalable facial recognition system using FastAPI, PostgreSQL, pgvector, Docker, and Kubernetes.
img: assets/img/project_1.png
importance: 1
category: work
related_publications: false
---------------------------

# Facial Recognition Deployment with PostgreSQL and pgvector

A production-ready facial recognition system built with FastAPI and PostgreSQL, leveraging the pgvector extension for efficient vector similarity search. The project supports facial embedding extraction, storage, and nearest-neighbor matching while providing scalable deployment options through Docker and Kubernetes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/facial-recognition/deploying-app.png" title="Application Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    High-level deployment architecture showing FastAPI, PostgreSQL, Docker, and Kubernetes integration.
</div>

## Overview

This project demonstrates how modern facial recognition applications can be deployed using a robust cloud-native architecture. Facial embeddings are generated using DeepFace and stored inside PostgreSQL using the pgvector extension, enabling efficient similarity searches directly within the database.

The solution supports both Docker Compose deployments for local environments and Kubernetes deployments for production workloads.

## Key Features

* Facial embedding extraction using DeepFace
* PostgreSQL database with pgvector extension
* Vector similarity search for face matching
* FastAPI REST API backend
* Docker-based containerized deployment
* Kubernetes deployment support
* Persistent storage using Docker Volumes
* Persistent Volume Claims (PVC) for Kubernetes
* Scalable microservice architecture

## Technology Stack

* Python
* FastAPI
* PostgreSQL
* pgvector
* DeepFace
* Docker
* Docker Compose
* Kubernetes
* Google Kubernetes Engine (GKE)
* psycopg2

## System Architecture

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/facial-recognition/architecture.png" title="System Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/facial-recognition/database.png" title="Database Layer" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    FastAPI service communicates with PostgreSQL and pgvector to store and compare facial embeddings.
</div>

## Docker Deployment

The application is fully containerized and can be deployed using Docker Compose.

### Clone Repository

```bash
git clone https://github.com/anas-rz/facial-recognition-deployment.git
cd facial-recognition-deployment
```

### Start Services

```bash
docker compose up -d
```

### Benefits

* Rapid deployment
* Isolated runtime environment
* Reproducible builds
* Persistent data through Docker volumes

## Kubernetes Deployment

For production environments, the application can be deployed on Kubernetes or Google Kubernetes Engine (GKE).

### Deployment Components

* FastAPI Deployment
* PostgreSQL Deployment
* Services
* Persistent Volume Claims (PVC)
* Container Registry Integration

### Deployment Workflow

```bash
docker build -t gcr.io/[project]/image_name .
docker push gcr.io/[project]/image_name

kubectl apply -f fastapi-deployment.yaml
kubectl apply -f fastapi-service.yaml
kubectl apply -f postgres-deployment.yaml
kubectl apply -f postgres-pvc.yaml
kubectl apply -f postgres-service.yaml
```

## API Usage

### Register Facial Embeddings

```bash
for file in images/input_embeddings/*; do
    curl -X POST \
    -F "file=@$file" \
    -F "name=$(basename $file)" \
    http://localhost:8000/embeddings
done
```

### Find Closest Face Match

```bash
curl -X POST \
-F "file=@images/test/shahid_test.jpeg" \
http://localhost:8000/embeddings/closest
```

## Results

This project demonstrates:

* Efficient vector search using pgvector
* End-to-end facial recognition pipeline
* Cloud-native deployment practices
* Persistent storage management in containerized environments
* Scalable API-driven architecture

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/facial-recognition/api-demo.png" title="API Demo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/facial-recognition/matching-results.png" title="Matching Results" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/facial-recognition/kubernetes.png" title="Kubernetes Deployment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example API interactions, facial matching results, and Kubernetes deployment.
</div>

## Repository

GitHub Repository:

https://github.com/anas-rz/facial-recognition-deployment

## Future Enhancements

* Real-time video stream processing
* Multi-face tracking
* Authentication and authorization
* Distributed vector database support
* GPU-accelerated inference
* CI/CD pipeline integration

## Acknowledgements

This project utilizes several excellent open-source technologies including FastAPI, PostgreSQL, pgvector, DeepFace, Docker, Kubernetes, and psycopg2.
