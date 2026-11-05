# Abdul Wasea

**AWS DevOps Engineer** at [Berlin Tech Sol](https://www.linkedin.com/company/berlin-techs/) · Docker · CI/CD · Terraform · Kubernetes · Linux servers

**Available for DevOps work:** [Hire me on Upwork](https://www.upwork.com/freelancers/~010e74406bf7e5c874) · [abdul.wasea@berlintechs.com](mailto:abdul.wasea@berlintechs.com) · [LinkedIn](https://www.linkedin.com/in/m-abdul-wasea/) · [Portfolio](https://abdulwaseadev.github.io)

I fix failing deploys, SSL and DNS errors, and sites stuck on slow shared hosting, and I set up AWS and Linux infrastructure that stays up. Everything below is code you can read: pipelines, Terraform and the tests that run before anything reaches production.

---

## Featured projects

### [URL Shortener API](https://github.com/AbdulWaseaDev/url-shortener)
Serverless REST API on AWS Lambda, API Gateway and DynamoDB, live at [url-shortener.berlintechs.com](https://url-shortener.berlintechs.com).
- GitHub Actions with OIDC deploys to staging, runs integration tests there, then deploys to production
- API key auth, rate limiting and least-privilege IAM
- CloudWatch alarms, SNS alerts and X-Ray tracing
- Infrastructure in SAM and CloudFormation

### [Northstar Cloud Platform](https://github.com/AbdulWaseaDev/northstar-cloud-platform)
AWS infrastructure for containerized services, written in Terraform.
- Multi-AZ VPC with public and private subnets, per-AZ NAT gateways in prod
- Application Load Balancer in front of ECS, encrypted RDS PostgreSQL with credentials in Secrets Manager
- S3 backend with DynamoDB locking, separate dev and prod state
- GitHub Actions runs `plan` on pull requests; applies are manual and prod needs reviewer approval

### [k3s Kubernetes on EC2](https://github.com/AbdulWaseaDev/k3s-ec2-fastapi)
A FastAPI app on a single-node k3s cluster, deployed with plain YAML manifests.
- Scaling, rolling updates and rollbacks with kubectl
- Liveness and readiness probes
- Written-up diagnostics for common pod failures

### Self-hosted production platform (Berlin Tech Sol, private)
About 25 Docker containers on one Ubuntu VPS, deployed with Coolify behind Caddy with automatic HTTPS. Jenkins builds and deploys the company website; the server also runs n8n, Nextcloud, Portainer, PostgreSQL and client apps. Container ports are blocked from the internet with iptables.

---

## Stack

| Area | Tools |
|------|-------|
| AWS | Lambda, EC2, ECS, API Gateway, DynamoDB, RDS, S3, CloudWatch, X-Ray, SNS, IAM, Secrets Manager |
| Infrastructure as Code | Terraform, CloudFormation, SAM |
| Containers | Docker, Docker Compose, Coolify, k3s, kubectl, ECR |
| CI/CD | GitHub Actions (OIDC, multi-stage), Jenkins |
| Linux | Ubuntu, bash, SSH hardening, iptables, SSL/TLS, Cloudflare DNS |
| Code and testing | Python, FastAPI, JavaScript/Node.js, pytest (unit, integration, smoke) |

## Working on now

- Ingress, TLS (cert-manager) and Helm charts for the k3s setup
- Prometheus and Grafana dashboards, with Loki for centralized logs
- Ansible playbooks for server hardening

---

Have a server, pipeline or AWS setup that needs work? Send me what you have now and where you want it to end up: [Upwork](https://www.upwork.com/freelancers/~010e74406bf7e5c874) or [abdul.wasea@berlintechs.com](mailto:abdul.wasea@berlintechs.com).
