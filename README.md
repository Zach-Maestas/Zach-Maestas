# Hi, I'm Zach 👋

**Software Engineer · Backend & Infrastructure** — Computer Science graduate, Colorado State University (Networks & Security concentration)

I build backend systems and the infrastructure they run on. I've written REST APIs in Java with SQL and automated testing, and built a full AWS platform with Terraform, Docker, and secure CI/CD. I'm currently building a Python/FastAPI backend with PostgreSQL.

Looking for early-career software engineering roles in backend, infrastructure, platform, and developer tooling. **Open to relocation** (Chicago · Austin · New York City · Washington, DC · Denver) and remote.

---

## 🔧 Projects

### Cloud Security Findings Platform
**Python · FastAPI · PostgreSQL · AWS · Terraform · Docker · GitHub Actions** — [Repo](https://github.com/Zach-Maestas/aws-security-ops-pipeline)

A backend service running on production-style AWS infrastructure I built with Terraform. The infrastructure layer is complete. The application layer is in progress.

**Infrastructure (complete)**
- 40+ AWS resources across 6 Terraform modules with remote state locking, with single-command deploy and teardown
- Three-tier VPC (ALB → ECS Fargate → RDS PostgreSQL) with least-privilege security group chaining
- Event-driven auto-remediation of risky IAM and security group changes (EventBridge → Lambda → SNS)
- Keyless CI/CD via GitHub Actions OIDC federation, plus four security gates (Gitleaks, Checkov, Trivy, terraform validate)

**Backend (in progress)**
- Python/FastAPI REST API that ingests cloud security findings and maps them to NIST 800-53 controls
- PostgreSQL schema with migrations, plus pytest unit and integration tests running in CI
<!-- Move completed items above and update as features ship -->


### Geographic Tour Optimization Service
**Java · Spark Java · MariaDB · JDBC · JUnit · Mockito · Maven** — [Repo](REPLACE_WITH_REPO_URL)

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
