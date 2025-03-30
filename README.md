# 🎬 FlixFlow - Cloud-Native Streaming Platform

**FlixFlow** is a modern, DevOps-focused video streaming platform inspired by Netflix and Amazon Prime. It simulates real-world streaming infrastructure while focusing on automation, scalability, observability, and availability using AWS and open-source tools.

---

## 🚀 Project Goals

- Build a production-grade streaming platform architecture.
- Demonstrate DevOps practices: IaC, CI/CD, monitoring, autoscaling, disaster recovery.
- Showcase container orchestration using Amazon EKS.
- Use Terraform for infrastructure automation.

---

## 🧱 Tech Stack

| Layer              | Tech/Service                     |
|-------------------|----------------------------------|
| Infrastructure     | Terraform (modularized)          |
| Compute            | AWS Lambda, Amazon EKS           |
| Storage            | Amazon S3, CloudFront            |
| Database           | Amazon Aurora Serverless v2      |
| Authentication     | Amazon Cognito                   |
| CI/CD              | GitHub Actions, Argo CD          |
| Monitoring/Logging | Prometheus, Grafana, OpenSearch  |

---

## 📦 Phases

| Phase | Description |
|-------|-------------|
| ✅ Phase 1 | VPC, EKS, Aurora, S3, CloudFront provisioning via Terraform |
| 🔄 Phase 2 | CI/CD pipelines and GitOps with ArgoCD |
| 🔄 Phase 3 | Observability stack (Prometheus, Grafana, OpenSearch) |
| 🔄 Phase 4 | Auto-scaling, performance testing, disaster recovery simulation |

---

## 📁 Repo Structure (Planned)

