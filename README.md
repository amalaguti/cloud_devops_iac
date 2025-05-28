# CloudOps, DevOps, IaC

Ongoing experimentation to reinforce knowledge and stay current with evolving tools.

## 🚀 Project Overview

This project demonstrates modern DevOps and CloudOps practices by building a multi-layered solution:
- A web-based AI assistant frontend that accepts natural conversation from users
- A FastAPI backend (containerized with Docker) that receives instructions from the frontend
- Automated provisioning of cloud resources (Azure & AWS) using Terraform
- Containers: Docker, Kubernetes, ArgoCD, AKS
- Infrastructure deployment triggered via GitHub Actions workflows
- Modular repositories for frontend, backend, and infrastructure
- Designed for 24/7 operation using cost-effective cloud services (e.g., Render, Vercel)
- Implementation of day 0, day 1, day 2 management tools
- Monitoring tools
- Integrations


## 🏗️ Architecture

- **Frontend:** Node.js and Express (hosted on Vercel/Netlify)
- **Backend:** FastAPI app in Docker (hosted on Render)
- **Infrastructure:** Terraform, triggered by GitHub Actions, Docker, Kubernetes, and serverless functions



## 📝 Recent Progress

- **Backend Service:**
  - Scaffolded a minimal FastAPI backend, containerized with Docker
  - Refactored code into a clean structure under `portal_backend/backend_fastapi_docker/`
  - Added documentation and best practices for Docker, FastAPI, and deployment
  - Ready for deployment to Render or similar platforms

  See the backend repo and docs for details:
  [🔗 backend_fastapi_docker](https://github.com/amalaguti/backend_fastapi_docker)

## 🛠️ Tools Used

- **Frontend:** Node.js + Express (AI bot planned)
- **Backend:** FastAPI (Docker container)
- **Infrastructure:** Terraform, Kubernetes, GitHub Actions, AWS, Azure
- **Configuration:** Ansible, SaltStack, Cloud tools
- **Monitoring:** Prometheus, Grafana and more... TBD


## 📌 Next Steps and project status

[Project Board](https://github.com/users/amalaguti/projects/1)
---

