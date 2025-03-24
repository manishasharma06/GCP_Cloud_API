
##  Project 2: Google Cloud API Gateway

# Serverless Backend with GCP Cloud Functions & API Gateway

### Overview
A serverless backend built using Google Cloud Functions, accessed through a standardized API Gateway using an OpenAPI (Swagger) specification.

### Features
- Serverless deployment (no infrastructure maintenance)
- OpenAPI specification for endpoint definitions
- Fast, low-latency response times
- Cost-efficient architecture

### Tech Stack
- Google Cloud Functions
- Google API Gateway
- OpenAPI / Swagger
- Node.js / Python (choose depending on your implementation)

### What I Learned
- Writing OpenAPI definitions
- Deploying GCF with minimal setup
- Using GCP CLI and Console for monitoring
- Handling IAM permissions for APIs

### 📂 Run Locally
gcloud functions deploy helloWorld \
--runtime python310 \
--trigger-http \
--allow-unauthenticated
