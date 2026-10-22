# 👋 Hi, I'm Abdul Wasea

**Cloud DevOps Engineer** | AWS • Kubernetes • CI/CD • GitHub Actions • Infrastructure as Code

---

## 🚀 About Me

I build scalable, secure cloud infrastructure and automated deployment pipelines. My focus is on AWS cloud services, Kubernetes orchestration, Linux server administration, and CI/CD systems. I design production-ready systems that deploy safely and scale reliably.

**Core Values:**
- Infrastructure as Code (IaC) for all infrastructure
- Comprehensive monitoring and alerting
- Multi-environment deployments (staging → production)
- Automated testing at every stage
- Security-first approach

---

## 🛠️ Tech Stack

### ☁️ Cloud & AWS
- **Compute:** Lambda, EC2, ECS
- **Database:** DynamoDB, RDS
- **API:** API Gateway, Application Load Balancer
- **Monitoring:** CloudWatch, X-Ray, SNS
- **IAM & Security:** Least-privilege access, OIDC, Secrets Manager
- **Infrastructure:** SAM, CloudFormation

### 🐳 Kubernetes & Containers
- **Kubernetes:** k3s, kubectl, Deployments, Services
- **Container Runtime:** Docker, Docker Compose, Coolify, ECR
- **Orchestration:** Rolling updates, scaling, health checks
- **Manifests:** YAML, ConfigMaps, Secrets

### ⚙️ Infrastructure as Code
- **Terraform** – AWS resource provisioning, multi-environment
- **CloudFormation** – AWS template-based IaC
- **SAM** – Serverless Application Model

### 🔄 CI/CD & Automation
- **GitHub Actions** – Workflows, OIDC authentication, multi-stage pipelines
- **Pipeline Design** – Build → Test → Staging → Production
- **Testing** – Unit tests, integration tests, smoke tests (pytest)
- **Deployment Strategies** – Rolling updates, staging → production with manual prod approval
- **Jenkins** – Self-hosted build and deploy jobs

### 🐧 Linux & Server Administration
- **System Admin:** User management, permissions, package management
- **Scripting:** bash, Python, shell scripting
- **Security:** Firewall configuration (iptables), SSH hardening, SSL/TLS, Cloudflare DNS
- **Monitoring & Logging:** CloudWatch agent, log aggregation

### 🐍 Programming Languages
- **Python** – Lambda functions, automation scripts, FastAPI
- **JavaScript/Node.js** – Frontend and backend applications
- **bash/Shell** – System administration and infrastructure scripting

---

## 📋 Featured Projects

### 🔗 [URL Shortener API](https://github.com/AbdulWaseaDev/url-shortener) ⭐
**Production-ready serverless REST API on AWS**

A fully functional URL shortener demonstrating enterprise DevOps practices:
- **Architecture:** AWS Lambda + API Gateway + DynamoDB
- **Deployment:** GitHub Actions with OIDC, multi-environment (staging/prod)
- **Monitoring:** CloudWatch alarms, SNS alerts, X-Ray tracing
- **Security:** API key authentication, rate limiting, least-privilege IAM
- **Testing:** Unit tests, integration tests, smoke tests
- **Infrastructure:** SAM and CloudFormation

**Live at:** https://url-shortener.berlintechs.com

---

### ☸️ [k3s Kubernetes on EC2](https://github.com/AbdulWaseaDev/k3s-ec2-fastapi)
**Kubernetes deployment and operational skills**

A practical Kubernetes project running a FastAPI app on k3s:
- **Infrastructure:** Single-node k3s cluster on EC2
- **Deployment:** Plain YAML manifests (Deployments, Services, ConfigMaps)
- **Operations:** kubectl commands, scaling, rolling updates, rollbacks
- **Troubleshooting:** Diagnostics for common pod failures
- **Probes:** Liveness and readiness checks
- **Container:** Docker image builds, import into k3s containerd

---

### 🏗️ [Northstar Cloud Platform](https://github.com/AbdulWaseaDev/northstar-cloud-platform)

**AWS infrastructure for containerized services, written in Terraform**

- **Network:** Multi-AZ VPC, public and private subnets, per-AZ NAT gateways in prod
- **Compute:** Application Load Balancer in front of ECS on Amazon Linux 2023
- **Database:** Encrypted RDS PostgreSQL, credentials in Secrets Manager
- **Monitoring:** CloudWatch logs and alarms with SNS alerts
- **State:** S3 backend with DynamoDB locking, separate dev and prod state
- **CI/CD:** GitHub Actions runs plan on PRs. Applies are manual, and prod needs reviewer approval

---

### 🖥️ Self-hosted production platform (Berlin Tech Sol)

**About 25 containers on one Ubuntu VPS (private, runs client apps)**

- Deployed with Coolify behind Caddy with automatic HTTPS
- Jenkins builds and deploys the company website
- Runs n8n, Nextcloud, Portainer, PostgreSQL and client apps
- Container ports blocked from the internet with iptables

---

## 📊 Skills Summary

| Area | Skills |
|------|--------|
| **Cloud Services** | AWS Lambda, EC2, API Gateway, DynamoDB, CloudWatch, X-Ray, SNS, IAM |
| **Kubernetes** | k3s, kubectl, Deployments, Services, ConfigMaps, Rolling updates |
| **Infrastructure as Code** | Terraform, CloudFormation, SAM, YAML |
| **CI/CD** | GitHub Actions, Jenkins, multi-stage workflows, OIDC auth |
| **Linux Admin** | bash scripting, SSH hardening, user management, firewall config |
| **Programming** | Python, JavaScript, Shell/bash |
| **Monitoring** | CloudWatch, logs, alarms, metrics, tracing |
| **Testing** | pytest, unit tests, integration tests, smoke tests |

---

## 🎯 Current Focus

- Adding Ingress, TLS (cert-manager), and Helm charts to the k3s setup
- Prometheus and Grafana dashboards and alerts, with Loki for centralized logs
- Ansible playbooks for server hardening and setup
- GitLab CI pipelines alongside GitHub Actions

---

## 📫 Let's Connect

- **GitHub:** [@AbdulWaseaDev](https://github.com/AbdulWaseaDev)
- **Portfolio:** [abdulwaseadev.github.io](https://abdulwaseadev.github.io)
- **Email:** [mabdulwaseasumra@gmail.com](mailto:mabdulwaseasumra@gmail.com)
- **LinkedIn:** [linkedin.com/in/m-abdul-wasea](https://www.linkedin.com/in/m-abdul-wasea/)
---

## 💡 My Approach to DevOps

1. **Infrastructure as Code** – Everything is version-controlled and reproducible
2. **Automation First** – Manual tasks are expensive and error-prone
3. **Multi-Environment** – Staging before production, always
4. **Observability** – Monitor, log, and trace everything
5. **Security** – Least privilege, defense in depth
6. **Continuous Learning** – Cloud platforms evolve, so do I

---

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=AbdulWaseaDev&show_icons=true&theme=dark)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AbdulWaseaDev&layout=compact&theme=dark)

---

**"Infrastructure is code. Code should be reliable, secure, and automated."** ✨
