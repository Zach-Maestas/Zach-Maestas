# Hi, I'm Zach 👋

**Software Engineer · Backend & Infrastructure** — Computer Science graduate, Colorado State University (Networks & Security concentration)

I build backend systems and the infrastructure they run on. I've written REST APIs in Java with SQL and automated testing, and built a full AWS platform with Terraform, Docker, and secure CI/CD. I'm currently building a Python/FastAPI backend with PostgreSQL.

Looking for early-career software engineering roles in backend, infrastructure, platform, and developer tooling. **Open to relocation** (Chicago · Austin · New York City · Washington, DC · Denver) and remote.

---

## 🔧 Projects

### Cloud Security Findings Platform *(in progress)*
**Python · FastAPI · PostgreSQL · pytest · Docker · AWS**

Backend service that ingests cloud security findings, maps them to NIST 800-53 controls, and serves them through a REST API with tests running in CI.
<!-- Add repo link and 3–4 bullets once the API, schema, and tests are working -->

### Automated AWS Infrastructure & Security Platform
**AWS · Terraform · Python · Bash · Docker · GitHub Actions** — [Repo](https://github.com/Zach-Maestas/aws-security-ops-pipeline)

- 40+ AWS resources across 6 Terraform modules with remote state locking, with single-command deploy and teardown
- Three-tier VPC (ALB → ECS Fargate → RDS PostgreSQL) with least-privilege security group chaining
- Event-driven auto-remediation of risky IAM and security group changes (EventBridge → Lambda → SNS)
- Keyless CI/CD via GitHub Actions OIDC federation, plus four security gates (Gitleaks, Checkov, Trivy, terraform validate)

### Geographic Tour Optimization Service
**Java · Spark Java · MariaDB · JDBC · JUnit · Mockito · Maven** — [Repo]((https://github.com/CSU-CS-314-Spring-2025/t16))

- REST endpoints with versioned request/response contracts validated against JSON schemas
- Route optimization using nearest-neighbor construction with a 2-opt improvement pass
- SQL-backed location search with hand-written JDBC queries
- Unit and integration tests with JUnit and Mockito, with branch coverage tracked by JaCoCo in CI

---

## 🛠️ Skills

- **Languages:** Python · Java · SQL · Bash
- **Backend:** REST APIs · FastAPI · PostgreSQL · MariaDB · JDBC · pytest · JUnit · Mockito
- **Cloud & Infrastructure:** AWS (VPC, ECS Fargate, ALB, RDS, Lambda, EventBridge, S3, IAM) · Terraform · Docker · Linux
- **DevOps:** Git · GitHub Actions · CI/CD · OIDC federation · Infrastructure as Code
- **Security & Networking:** Least-privilege IAM · secrets management · GuardDuty · Security Hub · CloudTrail · TCP/IP · DNS · subnetting

---

## 📜 Certifications

AWS Solutions Architect – Associate · HashiCorp Terraform Associate · CompTIA Security+ · CompTIA Network+

---

## 📫 Connect

[LinkedIn](https://linkedin.com/in/zach-maestas-325a482b6) · [zacharymaestas.com](https://zacharymaestas.com)
