# Gabriel Eweka — DevOps Engineer

> Building infrastructure that ships fast and stays secure.

<a href="https://www.linkedin.com/in/gabriel-eweka/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:oseweka2@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/Eweka01"><img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://medium.com/@oseweka1"><img src="https://img.shields.io/badge/-Medium-000000?style=for-the-badge&logo=medium&logoColor=white" /></a>
<a href="https://gabrieleweka.dev"><img src="https://img.shields.io/badge/-Portfolio-2ea44f?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>

---

## 👋 About Me

DevOps engineer with a cybersecurity background. I spend my time building cloud-native platforms, CI/CD pipelines, and the kind of guardrails that let developers move fast without breaking production. I care a lot about the overlap between DevOps and security — supply chain integrity, policy as code, and the boring-but-critical stuff that keeps systems trustworthy.

When I'm not shipping infra, I'm usually writing about it on [Medium](https://medium.com/@oseweka1) or hanging out in engineering Slack communities.

---

## 🛠 Core Expertise

**Cloud & Infrastructure**
AWS (VPC, EC2, EKS, ECS, Lambda, S3, RDS, Route 53, CloudFront, IAM) · Azure · Multi-cloud DR · HA patterns

**Infrastructure as Code**
Terraform · Terragrunt · CloudFormation · Helm · Ansible

**CI/CD & GitOps**
GitHub Actions · Jenkins · GitLab CI · Argo CD · CodePipeline · Blue-green & canary releases · Promote-to-prod workflows

**Containers & Orchestration**
Docker · Kubernetes · EKS · ECS Fargate · Helm charts · Backstage

**Security & Supply Chain**
Trivy · SonarQube · Cosign · SLSA provenance · SBOM generation · Kyverno · Keyless signing via OIDC

**Observability & Ops**
CloudWatch · Prometheus · Grafana · Runbooks · Incident response · Cost optimization

**Languages & Scripting**
Bash · Python · Go (learning) · YAML wizardry

---

## 🚀 Featured Projects

### 🛡 KubeGuardian
AI-powered Kubernetes incident response system with MCP integration. Automates triage, root-cause analysis, and remediation suggestions for cluster incidents.

`Kubernetes` `Python` `MCP` `AI/LLM`

---

### 🎯 Backstage Self-Service Developer Platform
Production-style internal developer portal that lets teams scaffold and ship services without bothering platform engineers.

- Backstage software catalog with component registration and ownership tracking
- TechDocs (MkDocs) rendered inside the portal
- Software templates that scaffold repos with Dockerfile, CI pipeline, K8s manifests, Helm chart, and Argo CD config
- GitHub OAuth authentication with RBAC
- Backstage + PostgreSQL deployed on Kubernetes via Helm
- Full CD pipeline: GitHub Actions → Docker Hub → Kubernetes (raw manifests, Helm, and Argo CD)

`Backstage` `Kubernetes` `Helm` `Argo CD` `GitHub Actions` `Docker` `PostgreSQL`

---

### 🏭 Enterprise CI/CD Delivery Platform
**Repo:** `Corporate-Style-CI-CD-Pipeline`

Production-grade pipeline modeled after enterprise delivery workflows.

- Jenkins pipeline with SonarQube quality gates, Nexus artifact management, and Trivy security scanning
- Docker containerization with ECR image versioning
- Kubernetes deployment on AWS EKS
- Automated test → build → promote-to-prod workflow
- Reduced deployment times by 60–80%

`Jenkins` `Docker` `Kubernetes` `SonarQube` `Nexus` `Trivy` `AWS EKS` `ECR`

---

### 🌍 Multi-Cloud Disaster Recovery
**Repo:** `multi-cloud-dr`

Automated DR solution with failover across AWS and Azure — entire environment reproducible in minutes.

- Terraform-managed infrastructure across both clouds
- AWS S3 + CloudFront as primary, Azure Blob Storage as failover
- Route 53 health checks with automated DNS failover

`Terraform` `AWS` `Azure` `Route 53` `S3` `CloudFront` `Blob Storage`

---

### 🤖 AI-Assisted SRE Workflow on AWS
**Repo:** `AI-Assisted-SRE-Workflow-on-AWS`

AI-powered SRE automation deployed as a containerized service on AWS.

- ECS Fargate deployment with full Terraform IaC
- GitHub Actions CI/CD pipeline
- Automated incident triage and response workflows

`Terraform` `ECS Fargate` `GitHub Actions` `Python`

---

### ☁️ AWS Lift-and-Shift Migration
**Repo:** `vprofile-project`

Multi-tier Java web application migrated from on-prem to AWS — and then re-architected on PaaS.

- EC2 with ALB, Auto Scaling Groups, and Route 53
- S3 for artifacts, Security Groups for network isolation
- Re-architected on PaaS: Elastic Beanstalk, RDS, ElastiCache, Amazon MQ, CloudFront
- Started from local VMs (Vagrant + VirtualBox) to demonstrate the full migration path

`AWS EC2` `ALB` `Auto Scaling` `Route 53` `Elastic Beanstalk` `RDS` `Terraform`

---

## 🔧 Additional CI/CD Pipelines

| Pipeline | Tools | What It Does |
|---|---|---|
| GitHub Actions → ECS | GitHub Actions, SonarQube, Docker, ECR, ECS | Full CI/CD with quality gates, Docker build, ECR push, ECS deploy |
| Jenkins → ECS | Jenkins, Docker, ECR, ECS, IAM | Containerized build with promote-to-prod workflow |
| Jenkins → Beanstalk | Jenkins, Elastic Beanstalk, RDS | Automated testing + deployment to managed platform |
| GitLab CI → EKS | GitLab CI, Helm, SonarQube, Docker, Terraform, EKS | Helm-based pipeline with Terraform-provisioned EKS cluster |
| AWS-Native CI/CD | CodeCommit, CodeBuild, CodePipeline, SNS, SonarCloud | Fully AWS-managed pipeline with notifications |
| GitOps Workflows | GitHub Actions, Terraform | IaC workflows across staging/main branches |

---

## ✍️ Recent Writing

- [I Built an MCP-Enabled AI-Powered Kubernetes Incident Response System](https://medium.com/@oseweka1) — Mar 2026
- [How I Built an AI-Assisted SRE Workflow on AWS](https://medium.com/@oseweka1) — Mar 2026
- [I Built a Full Corporate-Style CI/CD Pipeline on AWS](https://medium.com/@oseweka1) — Mar 2026
- [Building a Complete CI/CD Pipeline with GitLab](https://medium.com/@oseweka1) — Jan 2026
- [I Built a Complete DevSecOps Pipeline With GitHub Actions](https://medium.com/@oseweka1) — Nov 2025
- [Building a Production-Grade CI/CD Pipeline with Jenkins, Docker & AWS ECS](https://medium.com/@oseweka1) — Nov 2025

More on [Medium →](https://medium.com/@oseweka1)

---

## 📫 Let's Connect

I'm currently open to DevOps / Platform / Cloud Engineering roles. If you're hiring or just want to talk shop about Kubernetes, supply chain security, or why YAML is somehow still the lingua franca of infrastructure — reach out.

📧 **oseweka2@gmail.com** · 🌐 **[gabrieleweka.dev](https://gabrieleweka.dev)** · 💼 **[LinkedIn](https://www.linkedin.com/in/gabriel-eweka/)**
