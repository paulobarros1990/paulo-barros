<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:326CE5&height=200&section=header&text=Paulo%20Henrique%20Barros&fontSize=35&fontColor=ffffff&animation=fadeIn" width="100%"/>

# 👋 Olá, eu sou o Paulo

DevOps & Cloud Engineer especializado em Kubernetes, GitOps e DevSecOps para ambientes enterprise.

---

## 🚀 Sobre mim

- 🛠 **Atualmente:** Engenheiro DevOps focado em Kubernetes, CI/CD e Infraestrutura como Código. Construo plataformas escaláveis, determinísticas e auditáveis utilizando modelo GitOps e pipelines desacopladas do deploy.

- 🎯 **Especialidades:**
  - Arquitetura Kubernetes em alta disponibilidade (RKE2 / Rancher)
  - GitOps com ArgoCD e promotion controlada (dev → homol → prod)
  - Infraestrutura como Código com Terraform e Ansible
  - Automação e scripting com Bash e Python
  - DevSecOps com SAST, DAST e container scanning
  - Observabilidade com Prometheus, Grafana e Loki

- 🏗 **Experiência prática:** Implementação de pipelines CI/CD enterprise, integração com registry privado (Harbor), Helm multi-environment e validação pós-deploy automatizada.

- 📚 **Interesses:** Arquitetura Cloud Native, Platform Engineering, Automação avançada, Segurança shift-left e Governança via Git.

- 🌎 **Idiomas:** Português (nativo), Inglês (intermediário).

---

## 🛠 Tech Stack & Ferramentas

| Categoria | Tecnologias |
|------------|-------------|
| Orquestração & Cluster | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![RKE2](https://img.shields.io/badge/RKE2-0075A8?style=flat-square&logo=rancher&logoColor=white) ![Rancher](https://img.shields.io/badge/Rancher-0075A8?style=flat-square&logo=rancher&logoColor=white) |
| GitOps & Deploy | ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) |
| CI/CD | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) |
| Containers & Registry | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Harbor](https://img.shields.io/badge/Harbor-60B932?style=flat-square&logo=harbor&logoColor=white) |
| Infraestrutura como Código | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) |
| Sistemas & Automação | ![Linux](https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnu-bash&logoColor=white) |
| Linguagens | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| DevSecOps | ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square) ![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-000000?style=flat-square) |
| Observabilidade | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-000000?style=flat-square) |
| Cloud | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) |

---

## 🏗 Arquitetura GitOps

```mermaid
flowchart LR
    Dev[Developer Commit] --> CI[GitHub Actions]
    CI --> Registry[Harbor Registry]
    Registry --> GitOps[GitOps Repository]
    GitOps --> ArgoCD
    ArgoCD --> Kubernetes[Cluster Kubernetes]
