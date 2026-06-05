<div align="center">

# KAMESHWAR V

### DevOps & Cloud Engineer · Platform Engineering · Multi-Cloud Infrastructure

*Building production-grade systems that scale, self-heal, and ship faster.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kameshwar--vivekananthan-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kameshwar-vivekananthan)
[![GitHub](https://img.shields.io/badge/GitHub-kam--rep-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kam-rep)
[![Email](https://img.shields.io/badge/Email-kameshtech1@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kameshtech1@gmail.com)
[![Location](https://img.shields.io/badge/Location-Puducherry,_India-4285F4?style=flat-square&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Puducherry,India)

![AWS](https://img.shields.io/badge/AWS-Certified_Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-Multi--Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Production-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D?style=flat-square&logo=argo&logoColor=white)

</div>

---

## About Me

I'm a DevOps & Cloud Engineer with **2.7 years** of production experience designing, automating, and operating infrastructure across **AWS and GCP**. My work lives at the intersection of platform engineering and DevOps execution — I don't just build pipelines; I build the platforms that make pipelines reliable.

At **Twilight IT Solutions**, I lead infrastructure for a production healthcare platform on GKE — maintaining **99.9% uptime**, automating secrets rotation end-to-end, and reducing cloud costs by **25–30%** through FinOps practices. I've also worn the product owner hat, owning full delivery of a Medical Coding Module from stakeholder requirement to developer handoff.

Before that at **Appexperts**, I built CI/CD systems and ran DevSecOps assessments across 16+ repositories for platforms spanning real estate, fintech, and global healthcare.

What sets me apart: I think in systems. Whether it's designing event-driven secrets propagation on GCP or migrating kubectl deployments to ArgoCD-managed GitOps, I focus on building infrastructure that is **declarative, auditable, and self-healing** — not just operational.

Currently deepening expertise in **Istio service mesh**, **advanced Kubernetes observability**, and **platform engineering patterns**.

---

## Core Expertise

### Cloud Platforms

| Platform | Services |
|----------|----------|
| **AWS** | ECS · ECR · Lambda · API Gateway · Route53 · ALB/NLB · CloudWatch · SES · SNS · SQS · ACM · DocumentDB · ElastiCache · VPC |
| **GCP** | GKE · Cloud Run · Secret Manager · Pub/Sub · Cloud Logging · Cloud Armor · WAF · Dataflow |

### Containers & Kubernetes

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)

Kubernetes · Helm · Kustomize · Istio Service Mesh · HPA Autoscaling · Rolling Updates · Readiness/Liveness/Startup Probes · Multi-stage Docker Builds

### Infrastructure as Code

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

Terraform (modular, multi-cloud) · Bash scripting · YAML · Ansible (fundamentals) · Python (automation scripting)

### CI/CD & GitOps

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

GitHub Actions · GitLab CI · Jenkins · TeamCity · ArgoCD · SonarQube · SonarCloud · Approval-gated Promotion Workflows

### Monitoring & Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![ELK](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticstack&logoColor=white)

Prometheus · Grafana · Alertmanager · PromQL · ELK Stack · GCP Cloud Logging · CloudWatch · Custom Dashboards · RED Method

### Networking & Security

VPC design · Nginx (reverse proxy & LB) · Ingress Controllers · TLS/SSL lifecycle · Firewall rules · DNS · ALB/NLB · IAM · Secrets Manager · mTLS · Cloud Armor · Workload Identity Federation · OWASP ZAP · Snyk · Trivy · OWASP Dependency Check

### Databases & Messaging

MongoDB Atlas · MySQL · DocumentDB · Redis · ElastiCache · Kafka · SQS · Pub/Sub

---

## Featured Projects

### RCM Healthcare Platform — GKE · ArgoCD · Kafka · Terraform
**Twilight IT Solutions** · Production · GCP-native

> **Problem:** A healthcare Revenue Cycle Management platform needed a cloud-native microservices architecture with zero-downtime deployments, automated secrets management, and cost-efficient autoscaling — all under strict SLA requirements.

**Architecture:**
- GKE cluster with Kustomize overlays per environment; ArgoCD for declarative GitOps sync
- Event-driven secrets pipeline: `Secret Manager → Pub/Sub → Cloud Run → GKE` — secrets rotate without pod restarts
- Kafka for async processing across 5+ decoupled service dependencies
- HPA autoscaling tuned to workload patterns; MongoDB Atlas with point-in-time recovery

**Key Outcomes:**

| Metric | Result |
|--------|--------|
| Uptime | **99.9%** |
| Deployment cycle | **3–5 minutes** via ArgoCD auto-sync |
| Manual secret rotation effort | **↓ ~80%** |
| MTTD for production incidents | **↓ ~40%** |
| Cloud infrastructure cost | **↓ ~25–30%** via FinOps tuning |
| Incident repeat rate | **Zero** across 15+ post-mortems |

---

### Perla 2.0 — Multi-tenant SaaS Platform · AWS ECS · Terraform
**Twilight IT Solutions** · Production · AWS

> **Problem:** A multi-tenant SaaS platform needed automated tenant onboarding, production-grade observability across microservices, and a deployment model that could scale per tenant without manual provisioning.

**Architecture:**
- Containerised Next.js on AWS ECS with blue/green deployment strategy for zero-downtime releases
- Terraform modules provisioning ECS services, ALB target groups, and Route53 DNS per tenant
- CloudWatch monitoring with custom metric alarms across 10+ microservices
- Private subnet VPC isolation with TLS lifecycle management and API Gateway integration

**Key Outcomes:**

| Metric | Result |
|--------|--------|
| Tenant onboarding time | **2 days → under 2 hours** |
| Infrastructure cost | **↓ 22%** via right-sizing + reserved capacity |
| Microservices under observability | **10+** |

---

### Istio Service Mesh on GKE — POC
*Self-initiated · GKE · Istio · Kiali · Envoy*

Deployed Istio on a local GKE cluster to explore zero-trust networking and advanced traffic management. Configured mTLS between services, implemented traffic splitting for canary releases, and set up Envoy-based rate limiting and circuit breaking. Visualised live service topology via Kiali — learnings are being prepared for production adoption.

**Explored:** mTLS · canary traffic splitting · circuit breaking · rate limiting · Kiali observability

---

### Prometheus + Grafana Observability Stack — POC
*Self-initiated · Kubernetes · Prometheus · Grafana · Alertmanager*

Built a full observability stack from scratch on a local Kubernetes cluster using the RED method (Rate, Errors, Duration). Configured Prometheus scraping, PromQL-based custom queries, Alertmanager routing rules, and Grafana dashboards for actionable incident detection.

---

### Helm Chart Library for Microservices — POC
*Self-initiated · Helm · Kubernetes · GKE*

Designed a standardised Helm chart template library for 8+ microservices, enforcing consistent deployment patterns — configurable probes, resource limits, HPA, and ingress definitions. Reduced new service onboarding from days to hours.

---

### DevSecOps Assessment — RevCord Financial Crime Platform
*Appexperts · Snyk · SonarQube · OWASP Dependency Check*

Conducted SAST and dependency vulnerability analysis across **16 repositories** including Android and iOS codebases. Produced risk-based vulnerability reports with prioritised remediation paths — dependency upgrades, version migrations, and CVE resolution guidance.

---

## What I Build

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   Cloud Infrastructure        Kubernetes Platforms                  │
│   ─────────────────────        ───────────────────                  │
│   · Modular Terraform IaC      · GKE / ECS production clusters      │
│   · Multi-tenant AWS/GCP       · Helm chart libraries               │
│   · VPC, ALB, DNS, TLS         · HPA autoscaling policies           │
│   · FinOps cost tuning         · Kustomize env overlays             │
│                                                                     │
│   CI/CD Pipelines              GitOps Workflows                     │
│   ────────────────             ────────────────                     │
│   · GitHub Actions / GitLab    · ArgoCD declarative sync            │
│   · Multi-stage Docker builds  · Self-healing deployments           │
│   · Approval-gated promotion   · Auditable Git-as-source-of-truth   │
│   · SonarQube / Trivy / Snyk   · Automated rollback                 │
│                                                                     │
│   Monitoring & Observability   Security & DevSecOps                 │
│   ───────────────────────────  ─────────────────────                │
│   · Prometheus + Grafana       · mTLS zero-trust (Istio)            │
│   · RED method dashboards      · Secrets automation pipelines       │
│   · Alertmanager routing       · SAST, SCA, container scanning      │
│   · ELK · GCP Cloud Logging    · IAM · WIF · Cloud Armor            │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Professional Highlights

<div align="center">

| | | | |
|:---:|:---:|:---:|:---:|
| **2.7 Years** | **2 Cloud Platforms** | **10+ Projects** | **99.9% Uptime** |
| Production Experience | AWS & GCP | Delivered end-to-end | SLA maintained |
| | | | |
| **16 Repos** | **30+ CVEs** | **3–5 min** | **↓ 25–30%** |
| DevSecOps assessed | Remediated | Deployment cycles | Cloud cost reduction |

</div>

---

## Current Focus

```yaml
current_focus:
  platform_engineering:
    - Istio service mesh (mTLS, traffic management, canary releases)
    - Advanced Kubernetes observability with PromQL and Grafana
    - GitOps maturity — progressive delivery patterns

  certifications_in_progress:
    - Certified Kubernetes Administrator (CKA)
    - AWS EKS — Getting Started (AWS Skill Builder)

  exploring:
    - OpenTelemetry for distributed tracing
    - Crossplane for cloud-native IaC
    - Platform Engineering toolchains (Backstage, Port)

  philosophy: >
    DevOps is not a role. It's a way of thinking about systems — 
    declarative, observable, resilient, and continuously improving.
```

---

## Tech Stack at a Glance

**Cloud**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)

**IaC & Automation**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**CI/CD & GitOps**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![TeamCity](https://img.shields.io/badge/TeamCity-000000?style=flat-square&logo=teamcity&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white)

**Security**

![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Snyk](https://img.shields.io/badge/Snyk-4C4A73?style=flat-square&logo=snyk&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasecurity&logoColor=white)

**Databases & Messaging**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

---

## Let's Connect

I'm actively exploring **Senior DevOps**, **Cloud Engineer**, and **Platform Engineer** roles — particularly on teams building internal developer platforms, cloud-native infrastructure, or multi-cloud architectures at scale.

> *If you're building systems that need to be reliable, observable, and automated — let's talk.*

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kameshwar-vivekananthan)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kameshtech1@gmail.com)
[![GitHub](https://img.shields.io/badge/Explore_my_Work-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kam-rep)

</div>

---

<div align="center">
<sub>
Open to DevOps Engineer · Cloud Engineer · Platform Engineer · Site Reliability Engineer roles
</sub>
</div>
