# 👨‍💻 Paulo Barros

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

## 🚀 DevOps & Cloud Engineer

Especialista em construção de plataformas Kubernetes com modelo GitOps e DevSecOps integrado.

---

## 🏗 Arquitetura Enterprise

```mermaid
flowchart LR
    Dev[Developer Commit] --> CI[GitHub Actions]
    CI --> Registry[Harbor Registry]
    Registry --> GitOps[GitOps Repo]
    GitOps --> ArgoCD
    ArgoCD --> Kubernetes
