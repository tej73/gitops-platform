# End-to-End GitOps Platform on Kubernetes

Production-grade DevOps platform built with Docker, Kubernetes, ArgoCD, Prometheus, and Grafana.

## Tech Stack
- **CI/CD:** GitHub Actions
- **Containerization:** Docker
- **Orchestration:** Kubernetes (AKS)
- **GitOps:** ArgoCD
- **IaC:** Terraform
- **Monitoring:** Prometheus + Grafana
- **Frontend Hosting:** Vercel

## Architecture
Code Push → GitHub Actions (CI/CD) → Docker Image → Azure Container Registry → ArgoCD → Kubernetes

## Running Locally
```bash
docker compose up --build
```
Frontend: http://localhost:8080
Backend API: http://localhost:3000

## Screenshots
Coming soon — Grafana dashboard, ArgoCD sync, GitHub Actions pipeline

## Author
Tejal Kadlag — DevOps Engineer
