# Awesome-Multi-Account-Governance-Landing-Zone

## Top Multi-Account Governance & Landing Zone Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Landing Zone Automation, Guardrails & Self-Hosted Multi-Account Governance*  

**Last updated: October 2026**



This repository tracks notable **commercial multi-account governance platforms** and **open-source projects** that establish secure, compliant, and well-architected landing zones across cloud accounts — automating account vending, policy enforcement, networking, and security baselines.



**Examples** include AWS Control Tower, Azure Landing Zones, Google Cloud Landing Zone, Turbot Guardrails, Gruntwork Pipelines, Terraform Cloud, Spacelift, StackZone, CoreStack, and Meshcloud (the category leaders).



**Open-source emphasis**: Multi-account governance and landing zones are anchored by **Terraform** and **OpenTofu** as the IaC standard, with **Gruntwork** open-sourcing its account factory patterns, **Crossplane** providing Kubernetes-native control planes, and **Open Policy Agent** enforcing guardrails. **Cloud Custodian** handles governance rules, **CloudQuery** and **Steampipe** provide cross-account visibility, and **Atlantis**/**Digger** enable PR-based Terraform workflows. **Terragrunt** orchestrates complex multi-account deployments. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Control Tower](https://aws.amazon.com/controltower/)**

  **AWS's landing zone automation** — sets up and governs multi-account AWS environments with best-practice blueprints . **Account Factory, guardrails, and dashboard** . **Best for AWS multi-account governance** .



- **[Azure Landing Zones](https://azure.microsoft.com/en-us/solutions/cloud-scale-analytics/)**

  **Microsoft's landing zone architecture** — scalable, secure Azure environments with policy-driven governance . **Best for Azure multi-subscription governance** .



- **[Google Cloud Landing Zone](https://cloud.google.com/architecture/landing-zones)**

  **Google's landing zone framework** — organization, folder, and project hierarchy with guardrails . **Best for GCP multi-project governance** .



- **[Turbot Guardrails](https://turbot.com/)**

  **Cloud governance platform** — policy enforcement and resource sharing across accounts . **Best for enterprise multi-cloud governance** .



- **[Gruntwork Pipelines](https://gruntwork.io/)**

  **IaC foundation and pipelines** — battle-tested Terraform modules for landing zones . **Best for Terraform-based landing zones** .



- **[Terraform Cloud](https://www.terraform.io/cloud)**

  **HashiCorp's managed IaC platform** — remote state, policy enforcement, and CI/CD . **Best for Terraform governance** .



- **[Spacelift](https://spacelift.io/)**

  **IaC orchestration platform** — Terraform, OpenTofu, Pulumi, CloudFormation, and Kubernetes . **Best for complex multi-IaC workflows** .



- **[StackZone](https://stackzone.com/)**

  **AWS landing zone automation** — pre-built guardrails and compliance . **Best for AWS landing zone** .



- **[CoreStack](https://www.corestack.io/)**

  **Multi-cloud governance platform** — continuous compliance and cost optimization . **Best for enterprise multi-cloud** .



- **[Meshcloud](https://meshcloud.io/)**

  **Multi-cloud management platform** — self-service cloud accounts with governance . **Best for enterprise multi-cloud** .



## Open-Source GitHub Projects



### Landing Zone & Account Factory



- **[Gruntwork Terraform Modules](https://github.com/gruntwork-io/terraform-aws-service-catalog)**

  **Battle-tested Terraform modules for AWS landing zones**, Apache-2.0 licensed . **Account factory, VPC baselines, security baselines, and compliance modules** . **The foundation for many AWS landing zones** . **Best for Terraform-based landing zones** .



- **[AWS Control Tower Account Factory for Terraform (AFT)](https://github.com/aws-ia/terraform-aws-control_tower_account_factory)**

  **AWS's official Terraform-based account factory**, Apache-2.0 licensed . **Automates account provisioning with Control Tower** . **Best for AWS Control Tower automation** .



- **[Azure Landing Zones (ALZ) Terraform](https://github.com/Azure/terraform-azurerm-caf-enterprise-scale)**

  **Microsoft's official Azure landing zone Terraform module**, MIT licensed . **Enterprise-scale architecture with management groups, policies, and networking** . **Best for Azure landing zones** .



- **[Google Cloud Foundation Toolkit](https://github.com/terraform-google-modules/terraform-google-cloud-foundation)**

  **Google's official landing zone modules**, Apache-2.0 licensed . **Organization, folder, project, and networking baselines** . **Best for GCP landing zones** .



### Multi-Cloud Control Planes



- **[Crossplane](https://github.com/crossplane/crossplane)**

  **Kubernetes-native cloud resource management**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Extends Kubernetes API to manage cloud resources** . **Compositions for reusable infrastructure patterns** . **Best for platform teams building internal developer platforms** .



- **[AWS Controllers for Kubernetes (ACK)](https://github.com/aws-controllers-kustomize/ack)**

  **AWS-native Kubernetes controllers**, Apache-2.0 licensed . **Manage AWS resources from Kubernetes** . **Best for AWS-centric Kubernetes** .



- **[Azure Service Operator](https://github.com/Azure/azure-service-operator)**

  **Azure-native Kubernetes controllers**, MIT licensed . **Manage Azure resources from Kubernetes** . **Best for Azure-centric Kubernetes** .



### Infrastructure as Code Orchestration



- **[Terragrunt](https://github.com/gruntwork-io/terragrunt)**

  **Terraform wrapper for DRY configurations**, MIT licensed with **8,000+ GitHub stars** . **Orchestrates Terraform across accounts and environments** . **Best for complex multi-account deployments** .



- **[Terramate](https://github.com/terramate-io/terramate)**

  **Orchestration and code generation for Terraform**, MPL-2.0 licensed . **Adds stacks, orchestration, and GitOps to Terraform** . **Best for scaling Terraform deployments** .



- **[Atlantis](https://github.com/runatlantis/atlantis)**

  **Terraform pull request automation**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Collaborative IaC via pull requests** . **Best for Terraform collaboration** .



- **[Digger](https://github.com/diggerhq/digger)**

  **Open-source Terraform Cloud alternative**, MIT licensed . **CI/CD-native IaC orchestration** . **Best for Terraform in CI/CD** .



- **[OpenTofu](https://github.com/opentofu/opentofu)**

  **Open-source Terraform fork**, MPL-2.0 licensed with **25,000+ GitHub stars** . **Community-driven under Linux Foundation** . **Best for Terraform without BSL concerns** .



- **[Pulumi](https://github.com/pulumi/pulumi)**

  **IaC with real programming languages**, Apache-2.0 licensed with **22,000+ GitHub stars** . **TypeScript, Python, Go, .NET, Java** . **Best for developer-centric IaC** .



### Policy & Governance



- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**

  **General-purpose policy engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Unified policy enforcement across cloud, Kubernetes, and CI/CD** . **Best for cross-account guardrails** .



- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)**

  **Rules engine for cloud security and cost management**, Apache-2.0 licensed . **Policy-as-code for AWS, Azure, GCP** . **Best for multi-account governance** .



- **[Kyverno](https://github.com/kyverno/kyverno)**

  **Kubernetes-native policy management**, Apache-2.0 licensed with **6,000+ GitHub stars** . **Policy as Kubernetes resources** . **Best for Kubernetes policy** .



- **[Gatekeeper](https://github.com/open-policy-agent/gatekeeper)**

  **OPA-based Kubernetes policy controller**, Apache-2.0 licensed . **Policy enforcement for Kubernetes** . **Best for Kubernetes admission control** .



- **[CloudQuery](https://github.com/cloudquery/cloudquery)**

  **Open-source cloud asset inventory**, MPL-2.0 licensed with **6,000+ GitHub stars** . **Extracts, transforms, and loads cloud configuration** across accounts . **Best for multi-account asset visibility** .



- **[Steampipe](https://github.com/turbot/steampipe)**

  **Zero-ETL cloud API querying with SQL**, AGPL-3.0 licensed with **7,000+ GitHub stars** . **Query cloud resources with SQL** across accounts . **Best for multi-account resource exploration** .



### Additional Strong Open-Source Options



- **Terraform** — The IaC standard for landing zones .

- **Ansible** — Configuration management across accounts .

- **Pulumi** — IaC with programming languages .

- **Crossplane** — Kubernetes-native cloud resources .

- **OpenTofu** — Community Terraform fork .

- **OPA** — Policy-as-code enforcement .

- **Cloud Custodian** — Cloud governance rules .

- **CloudQuery** — Cloud asset inventory .

- **Steampipe** — SQL-based cloud querying .

- **Terragrunt** — Terraform orchestration .

- **Atlantis** — Terraform PR automation .

- **Digger** — Terraform in CI/CD .



**Frameworks for building custom multi-account governance and landing zone solutions**: Combine **Gruntwork Terraform Modules** or **AWS Control Tower AFT** for AWS landing zones . Use **Azure Landing Zones Terraform** for Azure . Deploy **Google Cloud Foundation Toolkit** for GCP . Integrate **Crossplane** for Kubernetes-native multi-cloud resource management . Use **Terragrunt** or **Terramate** for Terraform orchestration across accounts . Choose **Atlantis** or **Digger** for PR-based IaC workflows . Enforce guardrails with **Open Policy Agent** and **Cloud Custodian** . Monitor with **CloudQuery** and **Steampipe** . Note that true enterprise landing zones with managed infrastructure, compliance certifications, and vendor-supported SLAs (Turbot, Spacelift, CoreStack) remain primarily commercial territory; open-source stacks provide strong account factory, IaC orchestration, and policy enforcement foundations that require integration for complete multi-account governance.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Multi-account governance platforms manage access to critical cloud resources and infrastructure. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **Landing zones require careful planning** — organizational hierarchy, networking, identity, and security baselines must be designed before deployment. Mistakes are costly to remediate .

- **State management is critical for IaC** — remote state backends (S3, GCS, Azure Blob) with locking are essential for team collaboration across accounts. Never commit state files to Git .

- **License considerations**: Gruntwork modules use Apache-2.0, AWS AFT uses Apache-2.0, Azure ALZ uses MIT, Crossplane uses Apache-2.0, OPA uses Apache-2.0, and OpenTofu uses MPL-2.0. Verify licensing against your use case before committing.

- The open-source ecosystem provides strong account factory, IaC orchestration, and policy enforcement foundations, but **managed infrastructure, compliance certifications, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for platform engineers, cloud architects, and organizations seeking multi-account governance sovereignty.**

Let's make multi-account governance and landing zones more open, transparent, and secure.
