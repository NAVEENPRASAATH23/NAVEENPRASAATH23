<h1 align="center">Hi, I'm Naveen Prasaath 👋</h1>

<p align="center">
  <a href="https://github.com/NAVEENPRASAATH23">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=680&lines=Cloud+%26+DevSecOps+Engineer;Kubernetes+%26+GitOps+Practitioner;Open+Source+Enthusiast+%26+Contributor;Building+Secure%2C+Automated+Cloud+Platforms" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="mailto:naveenprasaath65@gmail.com"><img src="https://img.shields.io/badge/Email-naveenprasaath65%40gmail.com-0284C7?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/NAVEENPRASAATH23"><img src="https://img.shields.io/github/followers/NAVEENPRASAATH23?label=Followers&style=flat-square&color=0284C7" /></a>
  <img src="https://img.shields.io/badge/Role-Cloud%20%26%20DevSecOps-059669?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Open%20Source%20%26%20Platform%20Eng-7C3AED?style=flat-square" />
</p>

---

### 👨‍💻 About Me

I am a **Cloud & DevSecOps Engineer** and **Open Source Enthusiast** with 3+ years of experience engineering secure, automated, and scalable platforms across **AWS, Azure, and Kubernetes**.

My work is driven by three core principles:
1. **Shift-Left Security & DevSecOps**: Baking automated security scans, secret management, and compliance directly into CI/CD pipelines and infrastructure code.
2. **Declarative Everything**: Managing cloud resources via modular **Terraform** and driving zero-drift deployments through **GitOps (Argo CD)**.
3. **Open Source Collaboration**: Actively contributing to open-source software and developer tooling to build resilient, community-first solutions.

---

## 🌟 Open Source Contributions

### 🚀 **[Laya (NandhaKishorM/laya)](https://github.com/NandhaKishorM/laya)** — High-Performance Neural Engine
> **Official Contributor · Released in v0.3.23**

- **Merged PR [#759](https://github.com/NandhaKishorM/laya/pull/759)**: Added `--calibration` post-training support to the ONNX evaluation CLI tooling.
- **Platform & DevOps Value**:
  - Engineered CLI argument validation, mutual dependency enforcement, and test suites.
  - Verified across production multilingual checkpoints with **0 decision flips** and `0.000000` max probability delta.
  - Demonstrates rigorous testing, code cleanliness, and cross-discipline collaboration on performance-critical systems.

---

## 🛡️ DevSecOps & Delivery Architecture

I focus on embedding security at every tier of the delivery pipeline rather than treating it as an afterthought:

```text
 ┌──────────────┐      Lint, SAST & Secrets Scan      ┌─────────────────────────┐
 │ Code Commit  │ ──────────────────────────────────► │ GitHub Actions / Jenkins │
 └──────┬───────┘                                     └────────────┬────────────┘
        │                                                          │
        ▼                                                          ▼ Multi-Stage Build
 ┌──────────────┐      Vulnerability Scans (Trivy)    ┌─────────────────────────┐
 │ Pull Request │ ◄────────────────────────────────── │  Secure Docker Image    │
 └──────┬───────┘                                     └────────────┬────────────┘
        │ Merged                                                   │ Signed & Pushed
        ▼                                                          ▼
 ┌──────────────┐      Declarative Sync & Drift Check ┌─────────────────────────┐
 │   Argo CD    │ ◄────────────────────────────────── │   Container Registry    │
 └──────┬───────┘                                     └─────────────────────────┘
        │
        ▼ Zero-Downtime Deployment
 ┌──────────────────────────────────────────────────────────────────────────────┐
 │                    Production Kubernetes (EKS / AKS)                         │
 │  • Zero-Trust Network Policies  • RBAC & Least-Privilege  • SOPS Encryption  │
 │  • Horizontal Pod Autoscaling   • Ingress & TLS           • Resource Quotas  │
 └──────────────────────────────────────┬───────────────────────────────────────┘
                                        │ Observability & Telemetry
                                        ▼
                 ┌──────────────────────────────────────────────┐
                 │  Prometheus · Grafana · CloudWatch & Alerts  │
                 └──────────────────────────────────────────────┘
```

---

## 🛠️ Core Capabilities & Technology Stack

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</p>

### 🛡️ DevSecOps & Security
- **Pipeline Security**: Shift-Left testing, automated dependency scanning, and container vulnerability management.
- **Identity & Access (IAM)**: Zero-Trust architectures, AWS Identity Center, Multi-Account Service Control Policies (SCPs), Azure RBAC, Kubernetes RBAC.
- **Secrets & Data Protection**: Encrypted secrets management using Mozilla SOPS, AWS Secrets Manager, and Kubernetes Secrets.
- **Cloud Governance**: Multi-account AWS Organizations & Control Tower Landing Zones, Microsoft Defender for Cloud, Network ACLs, and Security Groups.

### ☁️ Cloud Architecture & Modernization
- **Multi-Cloud Expertise**: Designing highly available, scalable infrastructure across **AWS** and **Microsoft Azure**.
- **Networking & Connectivity**: VPC / VNet design, Public/Private subnets, Transit Gateways, Direct Connect, BGP routing, and Load Balancers.
- **Cloud Migration & Modernization**: Experienced with **AWS MAP**, Migration Evaluator, and executing migration pathways using the **7Rs Framework**.

### ☸️ Kubernetes, Containers & GitOps
- **Cluster Orchestration**: In-depth administration of **EKS** and **AKS** — Pod lifecycle, Ingress controllers, Namespaces, StatefulSets, and DaemonSets.
- **Resilience & Autoscaling**: Implementing HPA, VPA, fine-tuned resource requests/limits, and scheduling strategies (Taints, Tolerations, Node Affinity).
- **GitOps Continuous Delivery**: Continuous synchronization, self-healing deployments, and declarative configuration using **Argo CD** and **Kustomize**.
- **Container Engineering**: Multi-stage Docker optimization, image slimming, and build caching.

### 🏗️ Infrastructure as Code & Automation
- **Terraform**: Modular IaC architecture, remote state locking (S3 + DynamoDB), plan/apply governance, and automated provisioning.
- **CI/CD Engineering**: Declarative GitHub Actions workflows, branch protection rules, self-hosted runners, and Docker-based Jenkins pipelines.
- **Automation & Scripting**: Infrastructure and operational automation using **Python**, **Bash / Shell**, and Linux systems diagnostics.
- **Observability**: End-to-end monitoring and alerting with **Prometheus**, **Grafana**, CloudWatch, and container health telemetry.

---

## 📈 GitHub Activity & Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NAVEENPRASAATH23&show_icons=true&theme=tokyonight&hide_border=true&title_color=38bdf8" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NAVEENPRASAATH23&layout=compact&theme=tokyonight&hide_border=true&title_color=38bdf8" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=NAVEENPRASAATH23&theme=tokyonight&hide_border=true" width="96%" />
</p>

---

## 🤝 Let's Connect

I am passionate about collaborating on **DevSecOps**, **Kubernetes & GitOps**, **Cloud Architecture**, and **Open Source Tools**.

- 📧 **Email**: [naveenprasaath65@gmail.com](mailto:naveenprasaath65@gmail.com)
- 🐙 **GitHub**: [@NAVEENPRASAATH23](https://github.com/NAVEENPRASAATH23)
- 💬 *Feel free to open an issue or reach out to discuss platform engineering, security automation, or open source!*
