# Hi, I'm Jacques Payne 👋

Clinical operations leader (former Associate Director) with 15+ years running Phase I–III trials for sponsors and CROs, now building secure cloud and AI automation for clinical research.

I've led global Phase III oncology trials, first-in-human studies and CRO oversight, and kept trials inspection-ready. Since 2024 I've built hands-on cloud, AI and security skills, and I use them to automate the oversight work I used to do by hand: eTMF completeness checks, study metrics and risk-based monitoring. Every project here runs on synthetic data and shows its evidence: test results, pipeline runs, screenshots and stated limitations.

AWS Certified Solutions Architect – Associate · AWS Certified Machine Learning Engineer – Associate · OCI 2025 Generative AI Professional

📍 Little Rock, AR · open to fully remote clinical operations roles (Associate Director, Study Lead, Senior CTM) and clinical systems / cloud automation roles

📂 [Cloud Engineering Portfolio](https://github.com/jdp-cloud/cloud-engineering-portfolio) · 💼 [LinkedIn](https://www.linkedin.com/in/jacques-payne-1ba7b43) · 📫 jacques.payne@gmail.com

## ⭐ Featured work

Eight projects, each with its own README, evidence and stated limitations.

| | Project | In one line |
| --- | --- | --- |
| 📋 | [eTMF Inspection Readiness Checker](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/08-etmf-readiness-checker) | Checks a synthetic eTMF index against DIA TMF Reference Model rules and flags missing, expired and late documents by severity, with site, country and study readiness scores. Serverless on AWS (S3, Lambda, EventBridge) in Terraform, 17 passing tests. Built from my Merck eTMF inspection-readiness work. |
| 🚀 | [**GitHub Actions to ECS CI/CD Pipeline**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/07-github-actions-ecs-cicd-pipeline) | GitHub Actions workflows that build the API and web images once and promote the same digest from ECS staging to production behind a required reviewer, using OIDC instead of stored AWS keys. Pull requests must pass tests, Checkov, gitleaks and a Trivy image scan, which blocked a real HIGH apt CVE in the base image that I patched and documented. Staging was stood up in Terraform and torn down; I traced a failed Fargate web deployment to the task hostname breaking the container health check. The end-to-end pipeline deploy is not yet demonstrated. |
🛡️ | [**WAF to Bedrock to SOAR Pipeline**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/04-waf-bedrock-threat-correlation-and-soar-pipeline) | AWS WAF logs become scored findings and incidents through Lambda and EventBridge. Amazon Bedrock only explains: deterministic code decides, and containment is never automated. Cognito MFA and group-based access protect the API. 75 Terraform resources, deployed and destroyed. Based on a class group lab, with my changes and limitations documented. |
| 🔍 | [**Local DevSecOps Pipeline with Jenkins**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/06-jenkins-devsecops-ci-cd-pipeline) | A 12-stage Jenkins pipeline with SonarQube, gitleaks, Trivy and OWASP ZAP. One run was blocked by Trivy with 5 HIGH findings, and the fixed run passed all 12 stages on 2026-10-03. A rerun on 2026-10-04 was blocked by a new Trivy finding in the base image; after a Dockerfile fix it passed all 12 stages again ([details](https://github.com/jdp-cloud/cloud-engineering-portfolio/blob/main/projects/06-jenkins-devsecops-ci-cd-pipeline/evidence/base-image-fix-2026-10-04/README.md)). Local lab, deployed and torn down. Based on a class exercise. |
| 🌏 | [**Multi-Region Hub-and-Spoke SIEM**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/03-multi-region-hub-and-spoke-web-application-with-centralized-siem) | Seven-region AWS Transit Gateway network with centralized Loki/Grafana logging, no SSH (Session Manager only), IMDSv2 and checksum-verified downloads. Terraform modules replaced six copy-pasted region files. Deployed, verified, destroyed and costed: screenshots and a cost breakdown are in the project. |
| 🔗 | [**GCP to AWS HA VPN with BGP**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/05-gcp-to-aws-ha-vpn-secure-connectivity) | 64 Terraform resources connect a Google Cloud VPC to an AWS Transit Gateway. 4 of 4 tunnels established, 4 BGP peers up, and cross-cloud ping working in both directions. Deployed and destroyed. Based on a class group lab. |
| 🔁 | [**Argo CD GitOps and RBAC**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/02-argocd-gitops) | Drift self-healing, per-environment `AppProject` boundaries, and a restricted role that is denied prod sync while admin succeeds. Real allow and deny tests. |
| ☸️ | [**Kubernetes Stateful Application**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/01-kubernetes-stateful-application) | Splunk as a StatefulSet with a non-root security context and a runtime-created secret. Data proven to survive pod deletion. |

### 🧰 Toolbox

| Area | Tools |
| --- | --- |
| Cloud | AWS (Transit Gateway, VPC, ALB, ECS Fargate, ECR, SSM Session Manager, IAM, WAF, Lambda, EventBridge, S3, Cognito, Bedrock) · GCP · HA VPN · BGP |
| IaC & CI/CD | Terraform (modules, provider aliases, remote state) · GitHub Actions (OIDC, environments, required reviewers) · Jenkins (configuration as code) · Argo CD · Docker Compose |
| Kubernetes | Minikube · StatefulSets · RBAC · AppProject policy |
| Security & observability | Least-privilege network design · IMDSv2 · SonarQube · Trivy · gitleaks · Checkov · OWASP ZAP · Splunk · Grafana Loki · Promtail |

### 🎓 Certifications

[![AWS Certified Solutions Architect – Associate, issued Apr 2025, valid through Apr 2028](https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20Associate-FF9900)](https://www.credly.com/badges/3a8289fa-4c39-4954-801f-9a3079484eeb/public_url) [![AWS Certified Machine Learning Engineer – Associate, issued Nov 2025, valid through Nov 2028](https://img.shields.io/badge/AWS%20Certified-Machine%20Learning%20Engineer%20Associate-FF9900)](https://www.credly.com/badges/82c5d1cf-0482-4426-92ef-51bdb033300c) [![Oracle Cloud Infrastructure 2025 Certified Generative AI Professional, issued Dec 2025, valid through Dec 2027](https://img.shields.io/badge/Oracle%20Certified-OCI%202025%20Generative%20AI%20Professional-C74634)](https://catalog-education.oracle.com/pls/certview/sharebadge?id=4C8A3CBFEFCE3AB5BB5403DB801A12A274F898F40B5F9C933545107C7A0C5033)

- AWS Certified Solutions Architect – Associate
- AWS Certified Machine Learning Engineer – Associate
- Oracle Cloud Infrastructure 2025 Certified Generative AI Professional
- HashiCorp Terraform Associate *(in progress)*

### 🚧 Next

Extending the Jenkins pipeline with dependency scanning (Snyk) and automatic ticket creation when a gate fails, plus Kubernetes ingress, TLS and policy labs.

<sub>New projects are added to the portfolio regularly. Earlier coursework lives in [jdpayne68](https://github.com/jdpayne68).</sub>
