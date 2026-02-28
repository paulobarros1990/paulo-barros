<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:326CE5&height=200&section=header&text=Paulo%20Henrique%20Barros&fontSize=35&fontColor=ffffff&animation=fadeIn" width="100%"/>

# 👋 Olá, eu sou o Paulo

DevOps & Cloud Engineer especializado em Kubernetes, GitOps e DevSecOps para ambientes enterprise.

---

## 🚀 Sobre mim

Engenheiro DevOps com experiência na construção de plataformas Kubernetes altamente disponíveis, pipelines CI/CD desacopladas do deploy e modelo GitOps com governança via Git.

Transformo requisitos complexos em ambientes:

- Escaláveis  
- Determinísticos  
- Auditáveis  
- Automatizados ponta a ponta  

---

## 🛠 Tech Stack & Ferramentas

| Categoria | Tecnologias |
|------------|-------------|
| Orquestração & Cluster | Kubernetes, RKE2, Rancher |
| GitOps & Deploy | ArgoCD, Helm |
| CI/CD | GitHub Actions |
| Containers & Registry | Docker, Harbor |
| Infraestrutura como Código | Terraform, Ansible |
| Sistemas & Automação | Linux, Bash |
| Linguagens | Python |
| DevSecOps | SonarQube, Trivy, OWASP ZAP |
| Observabilidade | Prometheus, Grafana, Loki |
| Cloud | AWS |

---

## 🏗 Arquitetura GitOps

```mermaid
flowchart LR
    Dev[Developer Commit] --> CI[GitHub Actions]
    CI --> Registry[Harbor Registry]
    Registry --> GitOps[GitOps Repository]
    GitOps --> ArgoCD
    ArgoCD --> Kubernetes[Cluster Kubernetes]
