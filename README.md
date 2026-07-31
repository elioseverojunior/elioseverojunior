# Elio Severo Junior

### Senior SRE & Cloud Engineer · 20+ years building and operating large-scale, self-healing AWS estates

[![crates.io](https://img.shields.io/badge/crates.io-3%20crates-orange?logo=rust)](#open-source)
[![Terraform Registry](https://img.shields.io/badge/terraform-5%20providers-7B42BC?logo=terraform)](#open-source)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?logo=linkedin)](https://www.linkedin.com/in/elio)
[![GitHub followers](https://img.shields.io/github/followers/elioseverojunior?color=green&logo=github)](https://github.com/elioseverojunior)
[![Profile views](https://komarev.com/ghpvc/?username=elioseverojunior)](https://github.com/elioseverojunior)

Senior SRE and cloud engineering leader with 20+ years building and operating large-scale, self-healing AWS estates, with production depth across Azure and GCP. Industry coverage spans B2B SaaS, agribusiness, EdTech, quick-service restaurant e-commerce and retail banking, delivered hands-on and as manager of distributed cross-border squads. I also author and maintain published open-source infrastructure tooling in Rust and Go.

Currently **Senior SRE Cloud Engineer** at **Viafoura**.
Full résumé: [https://elioseverojunior.github.io](https://elioseverojunior.github.io)

## Impact

- **243** core applications migrated from legacy KOPS to AWS EKS 1.33 — zero customer-facing downtime via Route53 weighted routing, Argo Rollouts and Istio traffic shifting
- **35%** EC2 spend reduction — Karpenter consolidation, ARM64 Graviton node pools and automated spot execution
- **~60%** mean-time-to-detect reduction on production incidents — observability codified as infrastructure across Grafana Cloud, Loki, Prometheus, Datadog and OpenTelemetry
- **83%** deployment lead-time reduction — quarterly release batches replaced by twice-monthly production delivery

## Open source

Published libraries and providers, 29,372 downloads combined.

| Project | What it does | Downloads |
| --- | --- | --- |
| [rust-yaml](https://crates.io/crates/rust-yaml) | Fast, safe YAML 1.2 library for Rust | 23,346 |
| [terraform-provider-strcase](https://registry.terraform.io/providers/elioseverojunior/strcase) | String case conversion functions for Terraform | 3,871 |
| [terraform-provider-kind](https://registry.terraform.io/providers/elioseverojunior/kind) | Ephemeral Kubernetes-in-Docker clusters for CI and local test harnesses | 856 |
| [terraform-provider-docker](https://registry.terraform.io/providers/elioseverojunior/docker) | Declarative container lifecycle and image resources | 662 |
| [terraform-provider-dnsmasq](https://registry.terraform.io/providers/elioetibr/dnsmasq) | Local DNS record management as infrastructure as code | 417 |
| [terraform-provider-sops](https://registry.terraform.io/providers/elioetibr/sops) | Native decryption of SOPS-managed secrets inside Terraform plans | 220 |

Recently shipped: **comply** — REUSE/SPDX compliance tooling for Rust (July 2026). Crates: [comply](https://crates.io/crates/comply), [comply-cli](https://crates.io/crates/comply-cli). Source: [elioseverojunior/comply](https://github.com/elioseverojunior/comply).

## Stack

**Languages** · Rust · Go · Python · C# · Ruby · Bash · PowerShell · SQL

**Cloud** · AWS · Azure · GCP

**Orchestration** · Kubernetes · EKS · KOPS · Helm · Istio · ArgoCD · Argo Rollouts · Karpenter · Docker

**Infrastructure as Code** · Terraform · OpenTofu · Terragrunt · Pulumi

**Observability** · Grafana · Grafana Cloud · Prometheus · Loki · OpenTelemetry · Datadog · CloudWatch

**Data** · Apache Airflow · AWS Glue · Athena · Lake Formation · Step Functions · Redshift · PostgreSQL · Liquibase

**Security** · HashiCorp Vault · Consul · SOPS · SonarQube · Snyk

## Experience

**Senior SRE Cloud Engineer** — Viafoura · 2024-10 – present

- Led the KOPS to AWS EKS 1.33 migration of the core application estate using Route53 weighted routing, Argo Rollouts and Istio traffic shifting, completing cutover without customer-facing downtime.
- Containerized legacy workloads and authored Helm charts guarded by values.schema.json, rejecting invalid GitOps values before they reach a cluster.
- Provisioned data-lake and analytics infrastructure with Terraform and OpenTofu across Athena, Glue Data Catalog, Redshift, Step Functions and Airflow, applying Lake Formation column- and table-level governance for least-privilege analyst access.
- Codified observability as infrastructure in Terraform across Grafana Cloud dashboards, Loki log pipelines, Prometheus alert rules, Datadog dashboards and label-based Slack routing with OpenTelemetry.
- Standardized multi-account governance with AWS Account Factory for Terraform, Well-Architected guardrails and IAM Identity Center, and migrated legacy Jenkins jobs to declarative GitHub Actions reusable workflows with ArgoCD-centralized GitOps enabling canary and blue-green releases.

**Senior SRE Cloud Engineer** — Stanza Systems · 2023-10 – 2024-10

- Provisioned secure Amazon SageMaker and Bedrock endpoints with Terraform using scoped IAM execution roles, VPC network isolation and per-workload budget guardrails.
- Maintained multi-environment GitLab CI/CD pipelines enforcing a strict validate, plan and gated apply workflow with Jira ticket-first traceability.
- Tuned Karpenter-based autoscaling and cluster ingress to absorb variable demand without over-provisioning.
- Gated production deployment with SAST scanning, SonarQube quality gates, SOPS-encrypted Helm secrets and ArgoCD sync policies.

**SRE Cloud Engineering Manager** — Nutrien Soluções Agrícolas · 2022-04 – 2023-09

- Led the LATAM Cloud Engineering cross-squad team supporting downstream software and data engineering squads, building a high-density automation framework rather than growing headcount.
- Architected multi-account hub-and-spoke infrastructure across AWS, Azure and GCP using Transit Gateway, VPC, VPN and centralized identity, consolidating shared data platform services including data lakes, Glue, Lambda, RDS and Redshift.
- Established platform self-service patterns and GitHub Actions reusable workflows that replaced batch releases with continuous production delivery.
- Drove FinOps rightsizing, automated resource lifecycle management and decommissioning, reporting spend directly to the director.
- Mentored senior and junior engineers into end-to-end incident ownership.

**Senior SRE Cloud Engineer** — Passei Direto · 2021-11 – 2022-04

- Refactored core infrastructure and tuned application performance across AWS VPC, EC2, ECS and Lambda to defend availability under sudden enrolment-driven traffic surges.
- Implemented infrastructure as code with Terraform, Terragrunt and Pulumi, and maintained CI/CD across Jenkins and GitHub Actions.
- Hardened platform tooling including HashiCorp Vault secret delivery, Backstage service catalog and shared Jenkins libraries, instrumenting Sentry error tracking and SonarQube analysis.

---

<sub>This README is generated. Source lives in a private repository; edits made here are overwritten on the next build.</sub>
