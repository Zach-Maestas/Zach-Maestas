# Hi, I'm Zach 👋

**Cloud & Infrastructure Engineer** · Computer Science graduate, Colorado State University (Networks & Security concentration)
**AWS Solutions Architect – Associate · HashiCorp Terraform Associate · CompTIA Security+**

I build secure cloud infrastructure and the backend services that run on it, with a focus on AWS, Terraform, and automated security controls. Previously an IT Infrastructure Intern at CSU's Division of IT, working on Azure Landing Zone Terraform, NIST-aligned control reviews, and data center operations.

Looking for early-career roles in cloud, infrastructure, platform, and DevSecOps engineering, and backend roles with an infrastructure focus. **Open to relocation** (Chicago · Austin · New York City · Washington, DC · Denver) and remote.

---

## 🔧 Projects

### AWS Security Findings Platform
**Python · FastAPI · PostgreSQL · AWS · Terraform · Docker · GitHub Actions** · [Repo](https://github.com/Zach-Maestas/aws-security-findings-platform)

Detects risky AWS changes from CloudTrail (security groups opened to the internet, admin access granted, logging disabled), tracks them as deduplicated findings, and remediates them automatically.

**v1: cloud security platform** ([archived at `v1-cloud-security`](https://github.com/Zach-Maestas/aws-security-findings-platform/tree/v1-cloud-security))
- 40+ AWS resources across 6 Terraform modules with remote state locking, plus single-command deploy and teardown
- Three-tier VPC (ALB → ECS Fargate → RDS PostgreSQL) with least-privilege security group chaining
- Event-driven auto-remediation of IAM privilege escalation and open security groups (EventBridge → Lambda → SNS)
- Keyless CI/CD via GitHub Actions OIDC, four security gates (Gitleaks, Checkov, Trivy, terraform validate), and IAM permission boundaries

**v2: findings backend (in progress)**
- Python/FastAPI service with idempotent CloudTrail ingest and deduplicated findings
- PostgreSQL schema enforced with partial unique indexes and CHECK constraints, managed with Alembic migrations
- pytest unit and integration tests against a real Postgres, enforced in CI
- Next: deploy on ECS Fargate and RDS with an EventBridge → SNS → SQS pipeline, automated remediation, API-key auth, and an audit trail
<!-- Move items up as they ship -->

### Geographic Tour Optimization Service
**Java · Spark Java · MariaDB · JDBC · JUnit · Mockito · Maven** · [Repo](REPLACE_WITH_REPO_URL)

- REST endpoints with versioned request/response contracts validated against JSON schemas
- Route optimization using nearest-neighbor construction with a 2-opt improvement pass
- SQL-backed location search with hand-written JDBC queries
- Unit and integration tests with JUnit and Mockito, with branch coverage tracked by JaCoCo in CI

---

## 🛠️ Skills

- **Cloud & Infrastructure:** AWS (VPC, ECS Fargate, ALB, RDS, Lambda, EventBridge, S3, IAM) · Terraform · Docker · Linux
- **Security:** Least-privilege IAM · OIDC federation · secrets management · CloudTrail · GuardDuty · Security Hub · Checkov · Trivy · Gitleaks
- **DevOps:** Git · GitHub Actions · CI/CD · Infrastructure as Code
- **Languages & Backend:** Python · Java · SQL · Bash · FastAPI · PostgreSQL · pytest · JUnit
- **Networking:** TCP/IP · DNS · subnetting · security groups · NACLs · VPC Flow Logs

---

## 📜 Certifications

AWS Solutions Architect – Associate · HashiCorp Terraform Associate · CompTIA Security+ · CompTIA Network+

---

## 📫 Connect

[LinkedIn](https://linkedin.com/in/zach-maestas-325a482b6) · [zacharymaestas.com](https://zacharymaestas.com)
