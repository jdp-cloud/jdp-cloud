# Hi, I'm Jacques Payne 👋

**Cloud Security Engineer and AI Platform Engineer.** I build Terraform-managed AWS and Kubernetes environments that are secure by default, and I prove each one works with real evidence: command output, screenshots and deliberate allow-and-deny tests.

My 10+ years in regulated life-sciences operations (risk management, audit readiness, vendor oversight) shaped how I build: every control is documented and every claim is tested. I'm AWS-certified in both solutions architecture and machine learning, and OCI-certified in generative AI.

📂 **[Cloud Engineering Portfolio →](https://github.com/jdp-cloud/cloud-engineering-portfolio)** · 💼 [LinkedIn](https://www.linkedin.com/in/jacques-payne-1ba7b43) · 📫 <jacques.payne@gmail.com> · 🏢 [Kumo Solutions](https://github.com/jdp-kumo)

---

### ⭐ Featured work

| | Project | In one line |
| --- | --- | --- |
| 🌏 | [**Multi-Region Hub-and-Spoke SIEM**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/03-multi-region-hub-and-spoke-web-application-with-centralized-siem) | Seven-region AWS Transit Gateway network with centralized Loki/Grafana logging, no SSH (Session Manager only), IMDSv2 and checksum-verified downloads. Terraform modules replaced six copy-pasted region files. Deployed, verified, destroyed and costed: screenshots and a cost breakdown are in the project. |
| 🛡️ | [**WAF to Bedrock to SOAR Pipeline**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/04-waf-bedrock-threat-correlation-and-soar-pipeline) | AWS WAF logs become scored findings and incidents through Lambda and EventBridge. Amazon Bedrock only explains: deterministic code decides, and containment is never automated. Cognito MFA and group-based access protect the API. 75 Terraform resources, deployed and destroyed. Based on a class group lab, with my changes and limitations documented. |
| 🔗 | [**GCP to AWS HA VPN with BGP**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/05-gcp-to-aws-ha-vpn-secure-connectivity) | 64 Terraform resources connect a Google Cloud VPC to an AWS Transit Gateway. 4 of 4 tunnels established, 4 BGP peers up, and cross-cloud ping working in both directions. Deployed and destroyed. Based on a class group lab. |
| 🔁 | [**Argo CD GitOps and RBAC**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/02-argocd-gitops) | Drift self-healing, per-environment `AppProject` boundaries, and a restricted role that is denied prod sync while admin succeeds. Real allow and deny tests. |
| ☸️ | [**Kubernetes Stateful Application**](https://github.com/jdp-cloud/cloud-engineering-portfolio/tree/main/projects/01-kubernetes-stateful-application) | Splunk as a StatefulSet with a non-root security context and a runtime-created secret. Data proven to survive pod deletion. |

### 🧰 Toolbox

| Area | Tools |
| --- | --- |
| Cloud | AWS (Transit Gateway, VPC, ALB, SSM Session Manager, IAM, WAF, Lambda, EventBridge, Cognito, Bedrock) · GCP · HA VPN · BGP |
| IaC & CI/CD | Terraform (modules, provider aliases, remote state) · Jenkins · Argo CD |
| Kubernetes | Minikube · StatefulSets · RBAC · AppProject policy |
| Security & observability | Least-privilege network design · IMDSv2 · Splunk · Grafana Loki · Promtail |

### 🎓 Certifications

- AWS Certified Solutions Architect – Associate
- AWS Certified Machine Learning Engineer – Associate
- Oracle Cloud Infrastructure 2025 Certified Generative AI Professional
- HashiCorp Terraform Associate *(in progress)*

### 🚧 In progress

Jenkins-driven Terraform pipeline with an approval gate and automated security testing, plus Kubernetes ingress, TLS and policy labs.

<sub>New projects are added to the portfolio regularly. Earlier coursework lives in [jdpayne68](https://github.com/jdpayne68).</sub>
