# Sudarshan Vashisht

### DevOps · SRE · Cloud —  (Linux, Kubernetes, Docker, CI/CD, GitOps, IaC)

<p>
  <a href="https://www.linkedin.com/in/sudarshan-vashisht-249380296/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/sudarshanvashisht"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:sudarshanvashisht09@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

> **TL;DR for recruiters:** Final-year CS student (AKTU, 2027) with two internships, a self-managed K3s homelab running GitOps + observability, an AI-powered Kubernetes troubleshooting agent, and merged PRs to Snipe-IT and Argo CD. Targeting DevOps / SRE / Cloud roles.

## Highlights

- Operated **Snipe-IT on Amazon EKS (Helm)** and migrated **1,000+ employee asset records**.
- Diagnosed real production failures (HTTP 404 storage, HTTP 500) with `kubectl`, logs and events.
- Built a **K3s homelab** with Argo CD GitOps, Prometheus and Grafana.
- Shipped an **AI Kubernetes troubleshooting agent** with 4 failure scenarios and a human-approval safety model.
- **3 merged upstream PRs** (Snipe-IT ×2, Argo CD) + 1 open PR to Kubernetes.

## About

I'm a final-year B.Tech Computer Science student at Accurate Institute of Management and Technology (AKTU), graduating June 2027, focused on DevOps, SRE and Cloud. I like taking applications from source code to containers, CI/CD pipelines and Kubernetes deployments, and understanding how reliable, scalable infrastructure is built end to end.

Currently a **Technology Intern** (Sep 2026 – Feb 2027), operating Snipe-IT on Amazon EKS with Helm, diagnosing workload failures and contributing fixes upstream. Previously an **IT Intern at CCRAS, Ministry of AYUSH** (Jun – Jul 2026), where I built backend infrastructure for a geospatial research-data platform.

## Tech stack

**Linux & Scripting**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![K3s](https://img.shields.io/badge/K3s-FFC61C?style=flat-square&logo=k3s&logoColor=black)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GitOps](https://img.shields.io/badge/GitOps-326CE5?style=flat-square&logo=git&logoColor=white)

**CI/CD & Version Control**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Cloud & IaC**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Databases & Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)

## Featured projects

### Kubernetes AI Troubleshooting Agent — flagship

Problem: Kubernetes incidents require correlating pods, logs, events, deployments and services by hand.

Stack: Python, FastAPI, Next.js, Kubernetes, kubectl, OpenRouter LLM, Docker Compose.

- Collects deterministic cluster evidence across pod, log, event, deployment and service inspection.
- Returns root cause, technical explanation, recommended fix, kubectl commands, prevention and a confidence score.
- Ships 4 built-in failure scenarios: CrashLoopBackOff, ImagePullBackOff, OOMKilled, service selector mismatch.
- Human-approval safety model: the AI investigates and recommends; humans control production changes.

Link: https://github.com/sudarshanvashisht/Kubernetes-AI-Troubleshooting-Agent

```
Engineer -> Next.js Dashboard -> FastAPI -> Kubernetes cluster
                                         -> Evidence -> AI SRE agent -> Root cause + fix + kubectl -> Dashboard
```

### EduCenter OS — Cloud-Native Deployment Platform

Problem: Run a multi-service education platform on a self-managed cluster with GitOps and observability.

Stack: Next.js, FastAPI, PostgreSQL, Docker, K3s, Helm, Argo CD, Prometheus, Grafana, Jenkins.

- Deploys frontend, backend and PostgreSQL on a self-managed K3s homelab cluster.
- GitOps via Argo CD with auto-sync and self-heal from the GitHub repo.
- Prometheus and Grafana dashboards for cluster and application metrics.

```
GitHub -> Argo CD -> K3s cluster -> Frontend + Backend + Postgres
                                 -> Prometheus + Grafana
```

Link: https://github.com/sudarshanvashisht/educenter-os

## Experience

**Technology Intern — DeHaat (Green Agrevolution Pvt Ltd), Gurugram**
Sep 2026 – Feb 2027

- Operate Snipe-IT, the company's IT asset-management platform, on Amazon EKS using Helm charts.
- Diagnosed 404 errors on uploaded files (persistent-storage failure) and HTTP 500 errors on user creation using kubectl, pod logs and events; documented root causes and fixes.
- Configured SMTP email notifications and wrote a step-by-step Helm deployment guide.
- Helped migrate 1,000+ employee asset records from Excel into Snipe-IT.
- Contributed 2 merged fixes upstream to Snipe-IT (PR #19896, PR #19906).

**IT Intern — CCRAS, Ministry of AYUSH, New Delhi**
Jun 2026 – Jul 2026

- Built backend infrastructure for a geospatial research-data platform: KoboToolbox and Enketo Express on PostgreSQL/PostGIS, with Redis caching and MinIO storage behind an Nginx reverse proxy.
- Set up asynchronous processing with Celery and Redis to speed up form submissions.
- Administered Linux development machines: SSH access, GRUB bootloader recovery, disk partition and filesystem management.

## Open source

- **Snipe-IT (grokability/snipe-it)** — 2 merged PRs: #19896, #19906.
- **Argo CD (argoproj/argo-cd)** — PR #30385 merged (docs: HTTP/2 and gRPC-Web).
- **Kubernetes (kubernetes/kubernetes)** — PR #143366 open (docs: `ContainerStatus.ImageID`).
- Exploring contributions to `prometheus-community/helm-charts` (planned).

## Currently learning / building

- AWS EKS and Helm in a production-like setting.
- Advanced Kubernetes, GitOps and observability.
- Terraform and Infrastructure as Code fundamentals.
- Linux system administration.

## GitHub stats

![GitHub metrics](./github-metrics.svg)

*Stats are generated by a GitHub Action and committed to this repo to avoid third-party rate limits.*

## Contact

- LinkedIn: https://www.linkedin.com/in/sudarshan-vashisht-249380296/
- GitHub: https://github.com/sudarshanvashisht
- Email: use the mailto badge at the top of this page.

⭐ *Build. Automate. Deploy. Monitor. Repeat.*
