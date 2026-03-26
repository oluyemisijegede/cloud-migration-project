# cloud-migration-project
This repo is all about Cloud Migration from On-Premises Infrastructure
# End-to-End Cloud Migration Project (On-Prem → AWS EKS)

## Overview
This project demonstrates a real-world DevOps scenario where a legacy Node.js application is migrated from on-premise infrastructure to AWS using modern DevOps practices.

## Architecture
- Terraform → Infrastructure provisioning
- Docker → Application containerization
- Kubernetes (EKS) → Orchestration
- GitHub Actions → CI/CD pipeline
- Prometheus + Grafana → Monitoring & Observability

## Key Features
- Infrastructure as Code using Terraform
- Automated CI/CD pipeline
- Containerized application deployment
- Kubernetes auto-scaling and self-healing
- Real-time monitoring dashboards

## CI/CD Flow
1. Developer pushes code to GitHub
2. GitHub Actions builds Docker image
3. Image pushed to container registry
4. Application deployed to EKS

## Monitoring
- Prometheus collects metrics
- Grafana dashboards visualize:
  - CPU / Memory usage
  - Pod health
  - Application performance

## Outcome
- Improved scalability and reliability
- Reduced manual deployments
- Enabled real-time system observability
