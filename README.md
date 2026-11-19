# 50 Hands-On DevSecOps and CI/CD Security Projects

A progressive, lab-focused portfolio of 50 practical projects covering secure software delivery, CI/CD pipeline hardening, application security testing, secrets protection, software supply-chain security, container security, and deployment controls.

> **Safety and evidence:** Run exercises only against repositories, applications, runners, cloud accounts, and clusters you own or are explicitly authorized to test. Use disposable training secrets and isolated environments. Screenshots in this repository are clearly labeled simulated training illustrations; they are not evidence of real production assessments.

## Learning paths

| Level | Projects | Focus |
|---|---:|---|
| Beginner | 01–15 | CI fundamentals, source scanning, dependency checks, secrets hygiene, artifact basics |
| Intermediate | 16–35 | Pipeline threat modeling, DAST, IaC, containers, signing, policy gates, runner hardening |
| Advanced | 36–50 | Supply-chain assurance, provenance, Kubernetes delivery, cloud deployment, enterprise controls |

## Project index

### Beginner (01–15)
- [Project 01: Build a Secure GitHub Actions CI Pipeline](projects/01-build-a-secure-github-actions-ci-pipeline/README.md)
- [Project 02: Add Semgrep SAST to a Sample Application](projects/02-add-semgrep-sast-to-a-sample-application/README.md)
- [Project 03: Scan Dependencies with OWASP Dependency-Check](projects/03-scan-dependencies-with-owasp-dependency-check/README.md)
- [Project 04: Detect Exposed Secrets with Gitleaks](projects/04-detect-exposed-secrets-with-gitleaks/README.md)
- [Project 05: Create a Secure Branch Protection Baseline](projects/05-create-a-secure-branch-protection-baseline/README.md)
- [Project 06: Generate and Review a Software Bill of Materials](projects/06-generate-and-review-a-software-bill-of-materials/README.md)
- [Project 07: Add Trivy Filesystem Vulnerability Scanning](projects/07-add-trivy-filesystem-vulnerability-scanning/README.md)
- [Project 08: Secure CI Pipeline Permissions with Least Privilege](projects/08-secure-ci-pipeline-permissions-with-least-privilege/README.md)
- [Project 09: Validate Pull Requests with Automated Security Checks](projects/09-validate-pull-requests-with-automated-security-checks/README.md)
- [Project 10: Create a Basic Security Quality Gate](projects/10-create-a-basic-security-quality-gate/README.md)
- [Project 11: Scan Dockerfiles with Hadolint](projects/11-scan-dockerfiles-with-hadolint/README.md)
- [Project 12: Run Trivy Container Image Scans](projects/12-run-trivy-container-image-scans/README.md)
- [Project 13: Protect Build Artifacts and Workflow Outputs](projects/13-protect-build-artifacts-and-workflow-outputs/README.md)
- [Project 14: Add License and Dependency Policy Checks](projects/14-add-license-and-dependency-policy-checks/README.md)
- [Project 15: Create a DevSecOps Findings and Remediation Report](projects/15-create-a-devsecops-findings-and-remediation-report/README.md)

### Intermediate (16–35)
- [Project 16: Threat Model a CI/CD Pipeline](projects/16-threat-model-a-ci-cd-pipeline/README.md)
- [Project 17: Integrate OWASP ZAP Baseline DAST](projects/17-integrate-owasp-zap-baseline-dast/README.md)
- [Project 18: Build an IaC Security Scanning Workflow](projects/18-build-an-iac-security-scanning-workflow/README.md)
- [Project 19: Enforce Terraform Security with Checkov](projects/19-enforce-terraform-security-with-checkov/README.md)
- [Project 20: Harden Self-Hosted CI Runners](projects/20-harden-self-hosted-ci-runners/README.md)
- [Project 21: Create a Reusable Secure Workflow Template](projects/21-create-a-reusable-secure-workflow-template/README.md)
- [Project 22: Implement Secret Rotation for CI Credentials](projects/22-implement-secret-rotation-for-ci-credentials/README.md)
- [Project 23: Add Container Image SBOM and Vulnerability Gates](projects/23-add-container-image-sbom-and-vulnerability-gates/README.md)
- [Project 24: Sign Container Images with Cosign](projects/24-sign-container-images-with-cosign/README.md)
- [Project 25: Verify Artifact Signatures Before Deployment](projects/25-verify-artifact-signatures-before-deployment/README.md)
- [Project 26: Secure GitHub Actions with Pinned Dependencies](projects/26-secure-github-actions-with-pinned-dependencies/README.md)
- [Project 27: Detect Risky Workflow Changes in Pull Requests](projects/27-detect-risky-workflow-changes-in-pull-requests/README.md)
- [Project 28: Add API Security Tests to CI](projects/28-add-api-security-tests-to-ci/README.md)
- [Project 29: Deploy a Secure Preview Environment](projects/29-deploy-a-secure-preview-environment/README.md)
- [Project 30: Create a Policy-as-Code Gate with OPA](projects/30-create-a-policy-as-code-gate-with-opa/README.md)
- [Project 31: Scan Kubernetes Manifests with Kubesec](projects/31-scan-kubernetes-manifests-with-kubesec/README.md)
- [Project 32: Protect Build Caches and Artifact Stores](projects/32-protect-build-caches-and-artifact-stores/README.md)
- [Project 33: Create a Vulnerability SLA and Exception Workflow](projects/33-create-a-vulnerability-sla-and-exception-workflow/README.md)
- [Project 34: Automate Dependency Update and Risk Review](projects/34-automate-dependency-update-and-risk-review/README.md)
- [Project 35: Build a DevSecOps Metrics Dashboard](projects/35-build-a-devsecops-metrics-dashboard/README.md)

### Advanced (36–50)
- [Project 36: Design a Software Supply-Chain Security Architecture](projects/36-design-a-software-supply-chain-security-architecture/README.md)
- [Project 37: Implement SLSA-Aligned Build Provenance](projects/37-implement-slsa-aligned-build-provenance/README.md)
- [Project 38: Create an Isolated Ephemeral Build Runner Platform](projects/38-create-an-isolated-ephemeral-build-runner-platform/README.md)
- [Project 39: Build an Attested Multi-Stage Release Pipeline](projects/39-build-an-attested-multi-stage-release-pipeline/README.md)
- [Project 40: Enforce Kubernetes Admission Policies for Deployments](projects/40-enforce-kubernetes-admission-policies-for-deployments/README.md)
- [Project 41: Secure GitOps Delivery with Signed Manifests](projects/41-secure-gitops-delivery-with-signed-manifests/README.md)
- [Project 42: Implement Runtime Verification for Deployed Containers](projects/42-implement-runtime-verification-for-deployed-containers/README.md)
- [Project 43: Build a Cloud Workload Identity Deployment Pipeline](projects/43-build-a-cloud-workload-identity-deployment-pipeline/README.md)
- [Project 44: Create a Production-Grade Secrets Broker Integration](projects/44-create-a-production-grade-secrets-broker-integration/README.md)
- [Project 45: Automate Risk-Based Release Authorization](projects/45-automate-risk-based-release-authorization/README.md)
- [Project 46: Build a Multi-Repository Dependency Governance Program](projects/46-build-a-multi-repository-dependency-governance-program/README.md)
- [Project 47: Design a Secure Artifact Promotion Architecture](projects/47-design-a-secure-artifact-promotion-architecture/README.md)
- [Project 48: Run a CI/CD Compromise Tabletop and Recovery Exercise](projects/48-run-a-ci-cd-compromise-tabletop-and-recovery-exercise/README.md)
- [Project 49: Create an End-to-End Secure SDLC Assurance Case](projects/49-create-an-end-to-end-secure-sdlc-assurance-case/README.md)
- [Project 50: Build an Enterprise DevSecOps Reference Pipeline](projects/50-build-an-enterprise-devsecops-reference-pipeline/README.md)

## Standard project structure
Each project includes objectives, authorized scope, prerequisites, lab setup, implementation steps, commands/configuration examples, expected observations, risk interpretation, remediation, validation, evidence/reporting guidance, and three project-specific simulated training illustrations.

## Suggested lab stack
GitHub Actions, GitLab CI, Semgrep, Gitleaks, Trivy, OWASP ZAP, Checkov, Hadolint, Syft, Cosign, OPA/Conftest, Kubernetes, and disposable sample applications. Tool versions and CI syntax should be checked against the current vendor documentation before use.

## Progress
- [x] Beginner: 15/15
- [x] Intermediate: 20/20
- [x] Advanced: 15/15
- [x] Overall: 50/50

## Disclaimer
This repository is for education and defensive engineering. Never test third-party systems or production pipelines without written authorization. Do not commit real credentials, private keys, customer data, or sensitive logs.
