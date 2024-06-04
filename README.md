# Wisecow Deployment

This repository contains the necessary files to containerize and deploy the Wisecow application on a Kubernetes environment with secure TLS communication and an automated CI/CD pipeline.

## Repository Structure

wisecow-deployment/
├── .github/
│ └── workflows/
│ └── ci-cd.yml
├── kubernetes/
│ ├── deployment.yaml
│ ├── service.yaml
│ └── tls-secret.yaml
├── Dockerfile
├── README.md
└── app/ (Wisecow application source code)
