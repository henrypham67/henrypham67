# Minh Hieu (Henry) Pham

**DevOps / Platform Engineer** · Ho Chi Minh City, Vietnam · open to remote roles

4+ years building and operating cloud-native platforms on AWS (EKS, ECS Fargate).
CI/CD and GitOps, Infrastructure-as-Code with Terraform Enterprise, Kubernetes
operations, and full-stack observability. CKA, CKAD, and AWS SysOps certified.

## What I've shipped

- **Greenfield EKS platform** in a new AWS account: Terraform-authored cluster,
  ArgoCD app-of-apps GitOps delivery, a tag-pinned shared CI-template library,
  Graviton/arm64 node groups. New-workload onboarding is a single commit + merge request.
- **Postgres on Kubernetes with CloudNativePG:** continuous WAL archiving with
  point-in-time recovery, RPO ≤ 5 min.
- **EC2 → EKS / ECS Fargate migration** across multiple AWS accounts, legacy
  instances and load balancers decommissioned, cloud spend cut by up to 30%.
- **Observability stack:** OpenTelemetry collectors → Mimir, Loki, Tempo, Grafana,
  Alertmanager; Istio for service-mesh telemetry.
- **Internal tooling in Go/Python:** a dependency-graph tool that generates GitLab CI
  pipelines, and AI-agent skills against the platform's REST APIs — 15% less manual ops overhead.
- **Lakehouse ingestion** with Apache Iceberg, Kafka and Debezium CDC.

## Open source

- [derailed/k9s #3756](https://github.com/derailed/k9s/pull/3756) — Flux reconcile plugin (merged)
- [derailed/k9s #3750](https://github.com/derailed/k9s/pull/3750) — Flux trace plugin shortcut fix (merged)
- [adityatelange/hugo-PaperMod #1846](https://github.com/adityatelange/hugo-PaperMod/pull/1846) — post-content hook partials (merged)
- [kolb](https://github.com/henrypham67/kolb) — Claude Code plugin: Kolb learning cycle + SM-2 spaced repetition for DevOps engineers

## Writing

- [Understanding PostgreSQL Replication Slots in CloudNativePG](https://henrypham67.github.io/posts/databases/postgres-replication-slots-cloudnativepg/)
- [Managing PostgreSQL in Kubernetes with CloudNativePG](https://henrypham67.github.io/posts/databases/db-operator/)
- [Migrating from ArgoCD App-of-Apps to ApplicationSet](https://henrypham67.github.io/posts/argo/application-set/)
- [LimitRanges and ResourceQuotas](https://henrypham67.github.io/posts/kubernetes/kubernetes-policies/)
- [Kubernetes admission controllers](https://henrypham67.github.io/posts/kubernetes/admission-controller/)

More at [henrypham67.github.io](https://henrypham67.github.io/).

## Stack

[![Skills](https://skillicons.dev/icons?i=aws,kubernetes,docker,terraform,ansible,prometheus,grafana,go,python,bash,git,gitlab,githubactions)](https://skillicons.dev)

**CI/CD & GitOps:** ArgoCD, FluxCD, GitLab CI, GitHub Actions, Jenkins, Octopus Deploy, Atlantis  
**IaC & config:** Terraform / Terraform Enterprise, Helm, Kustomize, Ansible  
**Observability:** OpenTelemetry, Prometheus, Mimir, Loki, Tempo, Grafana, Alertmanager  
**Access & mesh:** Teleport, Istio  
**Data:** PostgreSQL (CloudNativePG), MongoDB, MySQL, Kafka, Debezium  
**Languages:** Go, Python, Bash

## Certifications

- Certified Kubernetes Administrator (CKA) — CNCF, valid to 08/2028
- Certified Kubernetes Application Developer (CKAD) — CNCF, valid to 04/2028
- AWS Certified SysOps Administrator – Associate — valid to 01/2027

**Education:** B.Sc. Computer Science, Ton Duc Thang University (2017–2022)

## Contact

[minhhieu060799@gmail.com](mailto:minhhieu060799@gmail.com) · [LinkedIn](https://www.linkedin.com/in/pmhieu67/) · [Blog](https://henrypham67.github.io/)
