<div align="center">

<img src="assets/banner.svg" alt="Pankaj Kumar Tiwari | Azure DevOps, Terraform, AKS, Helm, Argo CD" width="100%"/>

# Pankaj Kumar Tiwari

### DevSecOps Architect &nbsp;|&nbsp; Azure Platform Engineering &nbsp;|&nbsp; Infrastructure Automation

*Build · Automate · Deploy*

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pankajdsgithub)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN-ID)
[![Location](https://img.shields.io/badge/Noida-India-0078D4?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 👨‍💻 About Me

I build and standardize cloud infrastructure, platform engineering capabilities and application delivery workflows using **Microsoft Azure, Terraform, Azure DevOps, Kubernetes and GitOps**.

- 🔐 **Secure by default**: least privilege, managed identities, policy and scan gates
- ♻️ **Reusable by design**: modular Terraform, shared pipeline templates
- 🚀 **Automated delivery**: repeatable infrastructure provisioning and app deployment
- 📊 **Operationally ready**: metrics, logs, alerting and documented runbooks

---

## 🧰 Skills & Tools

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AKS](https://img.shields.io/badge/AKS-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=for-the-badge&logo=istio&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aqua&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📌 Featured Repositories

### Infrastructure as Code

| Repository | What it does | Tech | Status |
|---|---|---|---|
| [**terraform-azure-platform**](https://github.com/pankajdsgithub/terraform-azure-platform) | Modular Azure IaC, reusable patterns, per-environment tfvars | `Terraform` `Azure` | ![In Progress](https://img.shields.io/badge/-In_Progress-orange?style=flat-square) |
| **terraform-aks-cluster** | Production-style AKS cluster with node pools, networking and managed identity | `Terraform` `AKS` | ![Planned](https://img.shields.io/badge/-Planned-lightgrey?style=flat-square) |
| **azure-policy-governance** | Azure Policy and RBAC as code: tagging, allowed regions, security baselines | `Terraform` `Azure Policy` | ![Planned](https://img.shields.io/badge/-Planned-lightgrey?style=flat-square) |

### CI/CD & DevSecOps

| Repository | What it does | Tech | Status |
|---|---|---|---|
| [**azure-devops-infra-pipelines**](https://github.com/pankajdsgithub/azure-devops-infra-pipelines) | Reusable infra pipeline templates and thin consumer pipelines | `YAML` `Azure DevOps` | ![In Progress](https://img.shields.io/badge/-In_Progress-orange?style=flat-square) |
| **azure-devops-app-pipelines** | Reusable application CI/CD framework (build, test, scan, publish) | `YAML` `Docker` | ![Planned](https://img.shields.io/badge/-Planned-lightgrey?style=flat-square) |
| **devsecops-security-scanning** | Trivy image scan, secret scan and IaC scan gates for pipelines | `Trivy` `Bash` | ![Planned](https://img.shields.io/badge/-Planned-lightgrey?style=flat-square) |
| **github-actions-reusable-workflows** | Shared GitHub Actions workflows for lint, validate and release | `GitHub Actions` | ![Planned](https://img.shields.io/badge/-Planned-lightgrey?style=flat-square) |

### Kubernetes, GitOps & Observability

| Repository | What it does | Tech | Status |
|---|---|---|---|
| **kubernetes-helm-platform** | Helm charts and environment-specific deployment values | `Helm` `Kubernetes` | ![Planned](https://img.shields.io/badge/-Planned-lightgrey?style=flat-square) |
| **argocd-gitops-platform** | Declarative delivery and GitOps sync with Argo CD | `Argo CD` `Shell` | ![Planned](https://img.shields.io/badge/-Planned-lightgrey?style=flat-square) |
| **aks-observability-platform** | Monitoring, dashboards, logs and alerting for AKS | `Prometheus` `Grafana` | ![In Progress](https://img.shields.io/badge/-In_Progress-orange?style=flat-square) |
| **istio-flagger-progressive-delivery** | Canary releases with Istio traffic shifting and Flagger | `Istio` `Flagger` | ![Planned](https://img.shields.io/badge/-Planned-lightgrey?style=flat-square) |

> Repository links are added as each project goes live.

---

## 🏗️ Architecture

```mermaid
flowchart LR
    U[Engineer] -->|git push| R[Git Repository]
    R --> P[Azure DevOps Pipelines]
    P -->|fmt, validate, plan| T[Terraform Modules]
    P -->|build, scan| I[Container Image + Trivy]
    T -->|apply| A[(Azure: VNet, ACR, AKS, Key Vault)]
    I --> ACR[Azure Container Registry]
    ACR --> G[Helm charts / manifests in Git]
    G -->|sync| AC[Argo CD]
    AC -->|deploy| K[AKS Cluster]
    K --> O[Prometheus, Grafana, Logs]
```

**Delivery workflow:** `Source → Build → Secure → Package → Deploy → Operate`

---

## ✅ Build, Validation & Security

Every project follows the same quality gates:

| Gate | Tool | Purpose |
|---|---|---|
| Format | `terraform fmt -check` | Consistent code style |
| Validate | `terraform validate` | Configuration is valid |
| Plan | `terraform plan` | Review changes before apply |
| Image scan | `trivy image` | Fail on HIGH / CRITICAL vulnerabilities |
| Pipeline | Azure DevOps | Build, test, publish, deploy |

Sample output (illustrative; real run logs are added per project):

```text
$ terraform fmt -check
(no output: all files are properly formatted)

$ terraform validate
Success! The configuration is valid.

$ trivy image --severity HIGH,CRITICAL <image>:<tag>
Total: 0 (HIGH: 0, CRITICAL: 0)
```

---

## 🗺️ Roadmap

- [x] Terraform Azure platform (modular structure)
- [ ] Reusable Azure DevOps infra pipeline templates
- [ ] Reusable app CI/CD templates
- [ ] DevSecOps scanning gates (Trivy)
- [ ] Helm charts + Argo CD GitOps
- [ ] AKS observability stack (Prometheus + Grafana)
- [ ] Istio + Flagger progressive delivery
- [ ] Azure Policy governance as code

---

## 📚 Earlier Work

- [Machine Learning](https://github.com/pankajdsgithub/Machine-Learning)
- [Data Mining](https://github.com/pankajdsgithub/datamining)

---

<div align="center">

**Your GitHub profile is your digital portfolio. Make it count.**

</div>
