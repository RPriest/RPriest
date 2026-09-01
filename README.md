# Hi, I'm Samuel Bamgbose 👋
## 🛡️ DevSecOps Engineer | Penetration Tester | Cisco Certified
I'm a Computer Engineer with a background in penetration testing,
currently specializing in DevSecOps — building automated security
pipelines that embed security directly into the software delivery process.
---
## 🔧 What I Build
- ✅ CI/CD security pipelines with GitHub Actions & Jenkins (20+ stage pipelines)
- ✅ SAST automation with Semgrep & CodeQL
- ✅ DAST scanning with ZAP by Checkmarx on AWS
- ✅ Software Supply Chain Security with Dependabot & Dependency Review
- ✅ SBOM generation with CycloneDX & osv-scanner
- ✅ Kubernetes deployment security with EKS, ArgoCD & GitOps workflows
- ✅ Branch protection, CODEOWNERS & repository security controls
- ✅ Infrastructure as Code with Terraform
---
## 🧰 Tools & Technologies
| Security | Cloud & Infra | CI/CD |
|---|---|---|
| Semgrep | AWS EC2 | GitHub Actions |
| CodeQL | AWS IAM | Jenkins |
| ZAP by Checkmarx | AWS EKS | ArgoCD |
| CycloneDX | AWS ECR | Gitleaks |
| osv-scanner | AWS Secrets Manager | SonarQube |
| OpenSSF Scorecard | AWS KMS | Trivy |
| DefectDojo | CloudFormation / Terraform | Docker |
| | Security Groups | |
---
## 🏆 Certifications
- 🎓 **DevSecOps Pro** — Mission InfoSec Academy (June 2026) • 11 CPE Hours
- 🏗️ **Terraform** — KodeKloud (June 2026) • [View Certificate](https://learn.kodekloud.com/user/certificate/87c86b2c-40fa-498c-a18c-a73e102c10a1)
- 🌐 **Cisco Certified** — Networking Fundamentals
---
## 📌 Featured Projects

### 🎬 End-to-End DevSecOps Pipeline on AWS EKS (Netflix Clone)
A 4-phase build: AWS account hardening → a 20+ stage Jenkins pipeline
with 8+ security scanners → ArgoCD GitOps deployment to Kubernetes →
DefectDojo vulnerability management → Prometheus/Grafana monitoring.

[View Repository](https://github.com/RPriest/Netflix-Clone-K8S-End-to-End-Project) · [Phase 1 Write-up](https://rpriest0.medium.com/%EF%B8%8F-end-to-end-devsecops-kubernetes-project-phase-1-of-4-7b870ce22666) · [Phase 2 Write-up](https://rpriest0.medium.com/end-to-end-devsecops-kubernetes-project-phase-2-of-4-07d6b4da0ed6)

**Security controls implemented:**
- 🔴 113 findings aggregated in DefectDojo across 8+ scanners (SonarQube, NJSScan, Semgrep, Trivy, OWASP Dependency-Check, RetireJS, ZAP, osv-scanner)
- 🔴 16 ZAP DAST alerts caught against the live AWS deployment
- 🔴 100 known CVEs surfaced across 34 dependencies via CycloneDX SBOM
- 🟡 OpenSSF Scorecard improved 2.6 → 2.8
- ✅ Zero long-lived AWS credentials — OIDC end to end for CI/CD, no static access keys
- ✅ GitOps deployment — Jenkins never touches the cluster directly, only ArgoCD does
- ✅ Image signing with Cosign, SSM Session Manager instead of SSH, encrypted everything at rest

### 🔐 PyGoat DevSecOps Pipeline
A fully automated security pipeline built on a deliberately
vulnerable Python application, demonstrating real-world DevSecOps
controls from SAST to SBOM generation on AWS.

[View Repository](https://github.com/RPriest/pygoat)

**Security controls implemented:**
- 🔴 SAST: 199 code scanning findings identified by CodeQL (Code Injection, SSRF, Uncontrolled Command Line)
- 🔴 DAST: 16 alerts detected by ZAP baseline scan on live AWS deployment
- 🔴 SBOM: 100 known vulnerabilities across 34 packages — 99 with available fixes
- 🟡 OpenSSF Scorecard improved from 2.6 → 2.8 after implementing branch protection
- ✅ Branch protection + CODEOWNERS enforcing secure code review on every PR
- ✅ Dependency Review blocking vulnerable packages at PR level (caught GitPython 3.1.29 — Critical)
- ✅ Dynamic AWS Security Group IP allow-listing for secure GitHub Actions runner access
---
## 📝 Follow My Journey
I document my DevSecOps learning publicly on LinkedIn —
lab screenshots, lessons learned, and real pipeline builds.

[Connect on LinkedIn](https://www.linkedin.com/in/samuel-tofunmi-bamgbose-283405116/)
---
## 📫 Get In Touch
Open to DevSecOps internship and entry-level opportunities.
Feel free to connect on LinkedIn or explore my repositories!
