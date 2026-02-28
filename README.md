# 👨‍💻 Paulo Henrique Barros

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

## 🚀 DevOps & Cloud Engineer

Engenheiro DevOps especializado em construção de plataformas Kubernetes com modelo GitOps e DevSecOps integrado para ambientes corporativos.

Foco em:

- Arquitetura Kubernetes HA
- CI/CD desacoplado do deploy
- Promotion controlada (dev → homol → prod)
- Segurança integrada na pipeline
- Observabilidade orientada a ação

---

## 🏗 Arquitetura GitOps Enterprise

```mermaid
flowchart LR
    Dev[Developer Commit] --> CI[GitHub Actions]
    CI --> Registry[Harbor Registry]
    Registry --> GitOps[GitOps Repository]
    GitOps --> ArgoCD
    ArgoCD --> Kubernetes Cluster


✔ Deploy determinístico
✔ Imagem imutável
✔ Sem rebuild entre ambientes
✔ Health check automatizado
✔ Força de sync controlada

🔐 DevSecOps Integrado

SAST

SCA

DAST

Trivy Container Scan

SonarQube Quality Gate

Policy as Code

Segurança implementada no modelo shift-left.

📊 Observabilidade & Operação

Prometheus (métricas)

Grafana (dashboards)

Loki (logs)

Alertas acionáveis (sem alert fatigue)

🔋 Projeto Destaque – ChargePlus

Plataforma completa baseada em GitOps:

Helm multi-environment

Post-deploy validation

Git como única fonte da verdade

Pipeline enterprise versionada

Aplicação:
https://github.com/infratrust-ti/chargeplus

GitOps:
https://github.com/infratrust-ti/gitops_rke2

🎯 Diferencial

Mentalidade de plataforma, não apenas deploy.

Construo ambientes:

Auditáveis

Escaláveis

Governáveis

Automatizados ponta a ponta
