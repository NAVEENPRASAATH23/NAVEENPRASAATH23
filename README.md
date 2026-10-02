<h1 align="center">Hi there, I'm Naveen Prasaath 👋</h1>

<p align="center">
  <a href="https://github.com/NAVEENPRASAATH23">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Cloud+%26+DevOps+Engineer;AWS+%C2%B7+Azure+%C2%B7+Kubernetes+%C2%B7+Terraform;Production+GitOps+%26+CI%2FCD+Automation;Infrastructure+as+Code+%26+Cloud+Security;Bridging+Cloud+Infrastructure+%26+AI+Systems" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="mailto:naveenprasaath65@gmail.com"><img src="https://img.shields.io/badge/Email-naveenprasaath65%40gmail.com-0284C7?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/NAVEENPRASAATH23"><img src="https://img.shields.io/github/followers/NAVEENPRASAATH23?label=GitHub%20Followers&style=flat-square&color=0284C7" /></a>
  <img src="https://img.shields.io/badge/Experience-3%2B%20Years-059669?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Cloud%20Architecture%20%26%20DevOps-7C3AED?style=flat-square" />
</p>

---

### 👨‍💻 Professional Summary

I am a **Cloud & DevOps Engineer** with **3+ years of hands-on experience** architecting, automating, and securing production-grade cloud environments across **AWS, Azure, and Kubernetes**. 

My core focus centers on the complete DevOps lifecycle: transforming manual workflows into **Declarative Infrastructure as Code (Terraform)**, establishing resilient **GitOps & CI/CD delivery pipelines (GitHub Actions, Argo CD, Jenkins)**, optimizing containerized workloads, and enforcing **Zero-Trust Cloud Governance (Control Tower, IAM, SOPS)**.

> ⚡ *"Automate everything that should be automated, monitor everything that matters, and build resilient, repeatable systems."*

---

## 🌟 Featured Open-Source Contribution

### 🚀 **[Laya (NandhaKishorM/laya)](https://github.com/NandhaKishorM/laya)** — High-Performance Neural Engine
> **Official Contributor to Laya v0.3.23**

- **Merged PR [#759](https://github.com/NandhaKishorM/laya/pull/759)**: Added `--calibration` support to the ONNX evaluation CLI pipeline.
- **DevOps & Platform Impact**:
  - Implemented CLI argument validation, mutual dependency enforcement, and test harness execution for post-training calibrated ONNX models.
  - Added comprehensive test suites ensuring zero regression, zero decision flips, and `0.000000` max probability delta across production multilingual checkpoints.
  - Bridges Cloud/DevOps infrastructure practices with machine learning inference workflows.

---

## 🏗️ End-to-End DevOps & Delivery Workflow

```text
  Developer Push
        │
        ▼
 ┌──────────────┐     Automated CI Checks     ┌────────────────┐
 │ GitHub / Git │ ──────────────────────────► │ GitHub Actions │
 └──────────────┘                             │   or Jenkins   │
        │                                     └───────┬────────┘
        │ Declarative GitOps                          │ Build & Scan
        ▼                                             ▼
 ┌──────────────┐    Sync Manifests / Kustomize  ┌────────────────┐
 │   Argo CD    │ ◄───────────────────────────── │ Docker Registry│
 └──────┬───────┘                                └────────────────┘
        │
        ▼ Automated Deployment
 ┌─────────────────────────────────────────────────────────────┐
 │            Production Kubernetes (EKS / AKS)                │
 │  Ingress ──► Services ──► Pods (HPA / Resource Limits)      │
 └──────────────────────────────┬──────────────────────────────┘
                                │ Telemetry
                                ▼
         ┌───────────────────────────────────────────┐
         │ Prometheus & Grafana / CloudWatch Monitor │
         └───────────────────────────────────────────┘
```

---

## 🛠️ Technical Competencies

### ☁️ Cloud Architecture & Governance
<table>
  <tr>
    <td width="20%"><b>Amazon Web Services (AWS)</b></td>
    <td>
      <b>Core Compute & Containers:</b> EC2, EKS, ECS, Lambda, Auto Scaling<br/>
      <b>Networking & Hybrid:</b> VPC, Transit Gateway, Route 53, CloudFront, Direct Connect, BGP, NAT, Peering<br/>
      <b>Storage & Databases:</b> S3, EBS, EFS, RDS, Aurora, DynamoDB<br/>
      <b>Enterprise Governance:</b> AWS Organizations, Control Tower, Multi-Account Structure, SCPs, IAM Identity Center, Security Groups, NACLs<br/>
      <b>Migration & Discovery:</b> AWS MAP, Migration Evaluator, 7Rs Migration Strategy
    </td>
  </tr>
  <tr>
    <td width="20%"><b>Microsoft Azure</b></td>
    <td>
      <b>Compute & Platforms:</b> Azure Kubernetes Service (AKS), Azure Container Apps<br/>
      <b>Networking & Security:</b> Virtual Networks (VNets), Azure Load Balancers, Azure RBAC, Microsoft Defender for Cloud<br/>
      <b>Data & Integration:</b> Storage Accounts, Azure Data Factory, Database Migration Service (DMS), Integration Runtime
    </td>
  </tr>
</table>

### ☸️ Containers, Kubernetes & GitOps
<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon_EKS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure_AKS-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" />
  <img src="https://img.shields.io/badge/Kustomize-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
</p>

- **Cluster Architecture & Administration**: Control plane components, Kubelet, Kube-proxy, Node scheduling, Taints & Tolerations.
- **Workload Management**: Deployments, StatefulSets, DaemonSets, ConfigMaps, Secrets, Namespaces, Ingress (NGINX), Jobs/CronJobs.
- **Autoscaling & Resilience**: Horizontal Pod Autoscaler (HPA), Vertical Pod Autoscaler (VPA), Resource requests & limits, OOMKilled troubleshooting.
- **GitOps Delivery**: Continuous synchronization, drift detection, and declarative cluster manifests using **Argo CD** & **Kustomize**.
- **Container Engineering**: Multi-stage Docker builds, layer caching, image minimization, vulnerability mitigation.

### 🔄 CI/CD & Infrastructure as Code (IaC)
<p>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

- **Terraform**: Reusable modular architecture, state management (remote S3/DynamoDB locks), plan/apply governance, multi-environment isolation.
- **CI/CD Pipelines**: Declarative GitHub Actions workflows, branch protection integration, self-hosted runner infrastructure, Docker-based Jenkins pipelines.
- **Configuration & OS**: Ansible playbooks and inventory automation, Linux system administration, shell scripting, process & network diagnostics.

### 📊 Observability, Security & Scripting
<table>
  <tr>
    <td width="25%"><b>Monitoring & Metrics</b></td>
    <td>Prometheus, Grafana (custom dashboards & alerts), AWS CloudWatch, Azure Monitor, Container & Cluster Telemetry</td>
  </tr>
  <tr>
    <td><b>Security & Secrets</b></td>
    <td>AWS IAM Least-Privilege, Kubernetes RBAC, Mozilla SOPS, AWS Secrets Manager, Defender for Cloud, Network ACLs & Security Groups</td>
  </tr>
  <tr>
    <td><b>Scripting & Languages</b></td>
    <td>Python, Bash / Shell, C, Java, Perl, TCL, SQL</td>
  </tr>
  <tr>
    <td><b>Emerging Interests</b></td>
    <td>Platform Engineering, Internal Developer Platforms (IDP), AI Agents for Infrastructure Automation, Kubernetes AI/ML Workloads</td>
  </tr>
</table>

---

## 🎯 Engineering Philosophy

```text
 1. Understand Problem & Requirements
        │
 2. Design Secure Multi-Tier Cloud Architecture
        │
 3. Codify with Infrastructure as Code (Terraform)
        │
 4. Automate Delivery with CI/CD & GitOps
        │
 5. Enforce Least-Privilege Security & Compliance
        │
 6. Monitor, Alert & Observe (Prometheus / Grafana)
        │
 7. Continuously Optimize Performance, Reliability & Cost
```

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NAVEENPRASAATH23&show_icons=true&theme=tokyonight&hide_border=true&title_color=38bdf8" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NAVEENPRASAATH23&layout=compact&theme=tokyonight&hide_border=true&title_color=38bdf8" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=NAVEENPRASAATH23&theme=tokyonight&hide_border=true" width="96%" />
</p>

---

## 🤝 Connect & Collaborate

I'm always keen to exchange ideas around **Cloud Architecture**, **Kubernetes**, **GitOps**, **Platform Engineering**, and **Cloud Modernization**.

- 📧 **Email**: [naveenprasaath65@gmail.com](mailto:naveenprasaath65@gmail.com)
- 🐙 **GitHub**: [@NAVEENPRASAATH23](https://github.com/NAVEENPRASAATH23)
- 💬 *Feel free to reach out to discuss scalable infrastructure or open-source collaborations!*
