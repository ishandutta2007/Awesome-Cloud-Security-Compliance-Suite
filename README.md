# Awesome Cloud Security & Compliance Suite 🛡️☁️

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-Cloud-Security-Compliance-Suite/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ishandutta2007/Awesome-Cloud-Security-Compliance-Suite/graphs/commit-activity)

> A curated list of top **Cloud Security Posture Management (CSPM)**, **Cloud Workload Protection (CWPP)**, **Cloud Native Application Protection Platforms (CNAPP)**, and **Cloud Compliance & Governance** suites. Featuring both enterprise SaaS platforms and leading open-source alternatives.

---

## 📌 Table of Contents
- [Market Overview](#-market-overview)
- [SaaS & Hosted Enterprise Platforms](#-saas--hosted-enterprise-platforms)
- [Open-Source Solutions](#-open-source-solutions)
- [Comparison Matrix: SaaS vs Open-Source](#-comparison-matrix-saas-vs-open-source)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📊 Market Overview

The global Cloud Security and Compliance market was estimated at **~$36.1B – $41.0B in 2024–2025** and is projected to exceed **$100B by 2032** (growing at a CAGR of ~18–22%). The sector is **moderately fragmented**: while hyper-scalers (Microsoft, AWS, Google Cloud) and established enterprise giants (Palo Alto Networks, Salesforce, Datadog) command dominant revenue shares through unified suites, specialized CNAPP/CSPM innovators (Wiz, Orca Security) and agile open-source engines continue to hold substantial, disruptive market share across multi-cloud environments.

---

## 🏢 SaaS & Hosted Enterprise Platforms

Enterprise-grade cloud compliance, posture monitoring, and workload security platforms sorted by company valuation / market capitalization (descending).

| Platform | Company Valuation / Revenue | Primary Focus Areas | Specific Starting Tier Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Purview](https://www.microsoft.com/en-us/security/business/compliance/microsoft-purview)** | ~$3.1 Trillion Market Cap (~$245B Annual Revenue) | Data Governance, Risk Management & Regulatory Compliance | **$18.00 / user / month** (add-on to Microsoft 365 E3; or included in Microsoft 365 E5 at $57.00/user/month) | **90-day free trial** with up to 25 user licenses |
| **[Salesforce Shield](https://www.salesforce.com/products/platform/features/shield/)** | ~$280 Billion Market Cap (~$38B Annual Revenue) | Native CRM Compliance, Platform Encryption, Event Monitoring & Field Audit Trail | **Starts at 10% – 30% of net Salesforce license spend** (bundled module pricing starts at ~30% uplift on Enterprise/Unlimited edition licenses) | **30-day free trial** on Salesforce Enterprise Edition scratch/sandbox orgs |
| **[Palo Alto Networks Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud)** | ~$115 Billion Market Cap (~$8.0B Annual Revenue) | Comprehensive CNAPP, CSPM, CWPP & Code-to-Cloud Security | **Starts at $9,000 / year** (Business edition starting at ~$108 / credit / year for minimum credit bundles via AWS/Azure Marketplace) | **30-day free trial** with full CSPM scanning up to 50 cloud accounts |
| **[Datadog Cloud Security](https://www.datadoghq.com/pricing/?product=cloud-security-management)** | ~$40 Billion Market Cap (~$2.6B Annual Revenue) | Cloud Security Management (CSM), CSPM, Vulnerability Management & CIEM | **$7.50 / host / month** (CSM Pro, billed annually) | **14-day free trial** with full host and cloud environment features enabled |
| **[Check Point CloudGuard](https://www.checkpoint.com/cloudguard/)** | ~$21 Billion Market Cap (~$2.5B Annual Revenue) | Network Security, CSPM, Threat Prevention & Cloud Workload Protection | **Starts at $0.07 / gateway hour or ~$1,800 / asset bundle / year** via Cloud Marketplaces | **30-day free trial** covering unlimited scans for up to 10 cloud accounts |
| **[Trend Micro Cloud One](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-conformity.html)** | ~$7 Billion Market Cap (~$1.7B Annual Revenue) | Hybrid Cloud Security, CSPM (Conformity), Container & File Storage Security | **Starts at $299 / month** (Base package covering up to 250 cloud resources on Cloud One Conformity) | **30-day free trial** with full access across AWS, Azure, and GCP accounts |
| **[Wiz](https://www.wiz.io/)** | ~$12 Billion Valuation (~$500M+ ARR) | Agentless CNAPP, CSPM, Vulnerability Management & Cloud Compliance | **Starts at $15,000 / year** for foundational cloud workload bundles via AWS/Azure Marketplace | **14-day guided proof-of-concept (POC)** / interactive sandboxed demo environment |
| **[Sysdig Secure](https://sysdig.com/products/cloud-security/)** | ~$2.5 Billion Valuation (~$150M+ ARR) | Container & Kubernetes Security, Real-Time Runtime Threat Detection & CSPM | **Starts at $15.00 / host / month** (billed annually via AWS/GCP Marketplace) | **30-day free trial** with up to 10 nodes/hosts and container image scans |
| **[Orca Security](https://orca.security/)** | ~$1.8 Billion Valuation (~$80M+ ARR) | Agentless SideScanning™ CNAPP, Multi-Cloud Compliance & CSPM | **Starts at $12,000 / year** (entry-tier package covering up to 100 cloud workloads via AWS Marketplace) | **14-day free trial** with agentless discovery across up to 25 accounts |
| **[Lacework (Fortinet)](https://www.fortinet.com/products/lacework)** | Acquired by Fortinet ($65B Market Cap; formerly $8.3B valuation) | Polygraph Data Platform, Automated Anomaly Detection & CSPM | **Starts at $10,000 / year** (base platform fee starting tier via AWS Marketplace) | **14-day free trial** with cloud workload analysis and baseline activity profiling |

---

## 🔓 Open-Source Solutions

Battle-tested open-source security audit, compliance scanning, and policy enforcement engines sorted by GitHub stargazers count (descending).

| Tool | Stars | Primary Category | Description & Capabilities |
| :--- | :--- | :--- | :--- |
| **[Trivy](https://github.com/aquasecurity/trivy)** | [![GitHub stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social&color=white)](https://github.com/aquasecurity/trivy/stargazers) | All-in-One Vulnerability & CSPM Scanner | Comprehensive scanner for container images, file systems, Git repositories, virtual machine images, Kubernetes manifests, and AWS/Azure cloud security misconfigurations. |
| **[Wazuh](https://github.com/wazuh/wazuh)** | [![GitHub stars](https://img.shields.io/github/stars/wazuh/wazuh?style=social&color=white)](https://github.com/wazuh/wazuh/stargazers) | XDR, SIEM & Host Compliance | Unified open-source security platform for threat detection, integrity monitoring, incident response, and regulatory compliance (PCI DSS, HIPAA, CIS, NIST, GDPR). |
| **[Prowler](https://github.com/prowler-cloud/prowler)** | [![GitHub stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=social&color=white)](https://github.com/prowler-cloud/prowler/stargazers) | Multi-Cloud CSPM & Auditing | Security tool to perform AWS, Azure, Google Cloud, and Kubernetes security assessments, compliance audits (CIS Benchmarks, ISO27001, HIPAA, PCI DSS), and incident response. |
| **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)** | [![GitHub stars](https://img.shields.io/github/stars/open-policy-agent/opa?style=social&color=white)](https://github.com/open-policy-agent/opa/stargazers) | Policy-as-Code Engine | General-purpose policy engine that enables unified, context-aware policy enforcement across microservices, Kubernetes, CI/CD pipelines, API gateways, and cloud infrastructure. |
| **[Kubescape](https://github.com/armosec/kubescape)** | [![GitHub stars](https://img.shields.io/github/stars/armosec/kubescape?style=social&color=white)](https://github.com/armosec/kubescape/stargazers) | Kubernetes Security & Compliance | CNCF tool testing Kubernetes posture against NSA-CISA, MITRE ATT&CK®, and CIS benchmark standards. Includes image vulnerability scanning and RBAC visualizer. |
| **[Falco](https://github.com/falcosecurity/falco)** | [![GitHub stars](https://img.shields.io/github/stars/falcosecurity/falco?style=social&color=white)](https://github.com/falcosecurity/falco/stargazers) | Cloud-Native Runtime Security | CNCF graduated de-facto standard for runtime security and threat detection across Kubernetes, cloud containers, and Linux kernel eBPF system call monitoring. |
| **[Checkov](https://github.com/bridgecrewio/checkov)** | [![GitHub stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social&color=white)](https://github.com/bridgecrewio/checkov/stargazers) | Static Code Analysis for IaC | Static analysis tool for Infrastructure as Code (IaC) supporting Terraform, CloudFormation, Kubernetes, ARM, Bicep, Helm, and Serverless framework against compliance policies. |
| **[Kube-bench](https://github.com/aquasecurity/kube-bench)** | [![GitHub stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=social&color=white)](https://github.com/aquasecurity/kube-bench/stargazers) | CIS Benchmark Checker | Automated CIS Kubernetes Benchmark checker checking whether Kubernetes is deployed according to security best practices described in the CIS benchmark guides. |
| **[Steampipe](https://github.com/turbot/steampipe)** | [![GitHub stars](https://img.shields.io/github/stars/turbot/steampipe?style=social&color=white)](https://github.com/turbot/steampipe/stargazers) | SQL-based Cloud Querying & Compliance | Zero-ETL engine that queries cloud APIs (AWS, Azure, GCP, Alibaba, Kubernetes, GitHub) using standard SQL, with pre-built compliance benchmark suites (NIST, CIS, PCI, SOC 2). |
| **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)** | [![GitHub stars](https://img.shields.io/github/stars/cloud-custodian/cloud-custodian?style=social&color=white)](https://github.com/cloud-custodian/cloud-custodian/stargazers) | Cloud Governance & Remediation | Rules engine for cloud management and compliance with real-time enforcement, auto-remediation, cost optimization, and policy-as-code for AWS, Azure, and GCP. |
| **[ThreatMapper](https://github.com/deepfence/ThreatMapper)** | [![GitHub stars](https://img.shields.io/github/stars/deepfence/ThreatMapper?style=social&color=white)](https://github.com/deepfence/ThreatMapper/stargazers) | Attack Path Analysis & CNAPP | Open-source cloud-native security observability platform that hunts for vulnerabilities, malware, misconfigurations, and calculates visual attack paths across multi-cloud environments. |
| **[Terrascan](https://github.com/accurics/terrascan)** | [![GitHub stars](https://img.shields.io/github/stars/accurics/terrascan?style=social&color=white)](https://github.com/accurics/terrascan/stargazers) | Static IaC Scanner | Detects compliance and security violations across Infrastructure as Code (IaC) templates (Terraform, K8s, Dockerfiles, Helm) against 500+ built-in policies. |
| **[Kube-hunter](https://github.com/aquasecurity/kube-hunter)** | [![GitHub stars](https://img.shields.io/github/stars/aquasecurity/kube-hunter?style=social&color=white)](https://github.com/aquasecurity/kube-hunter/stargazers) | Kubernetes Penetration Testing | Hunts for security weaknesses in Kubernetes clusters from both inside and outside the cluster network to assess cluster exposure and attack surface. |
| **[OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper)** | [![GitHub stars](https://img.shields.io/github/stars/open-policy-agent/gatekeeper?style=social&color=white)](https://github.com/open-policy-agent/gatekeeper/stargazers) | Kubernetes Admission Controller | Validating and mutating webhook controller that enforces policies executed by Open Policy Agent (OPA) directly within Kubernetes admission control flows. |
| **[InSpec](https://github.com/inspec/inspec)** | [![GitHub stars](https://img.shields.io/github/stars/inspec/inspec?style=social&color=white)](https://github.com/inspec/inspec/stargazers) | Infrastructure Compliance as Code | Human-readable testing framework for security and compliance that turns compliance rules and security baselines into automated code tests. |
| **[Kubeaudit](https://github.com/Shopify/kubeaudit)** | [![GitHub stars](https://img.shields.io/github/stars/Shopify/kubeaudit?style=social&color=white)](https://github.com/Shopify/kubeaudit/stargazers) | Kubernetes Security Auditor | Command-line tool and Go package from Shopify that audits Kubernetes clusters against common security pitfalls and can automatically fix misconfigurations. |
| **[StackRox](https://github.com/stackrox/stackrox)** | [![GitHub stars](https://img.shields.io/github/stars/stackrox/stackrox?style=social&color=white)](https://github.com/stackrox/stackrox/stargazers) | Kubernetes-Native Security (RHACS) | Upstream open-source project behind Red Hat Advanced Cluster Security (RHACS), providing build-time scanning, deployment auditing, and runtime threat detection. |

---

## ⚖️ Comparison Matrix: SaaS vs Open-Source

| Capability | Enterprise SaaS Platforms | Open-Source Tool Suites |
| :--- | :--- | :--- |
| **Deployment Speed** | Instant setup with agentless API connectors | Requires self-hosting, pipelines, and maintenance |
| **Cost Predictability** | High starting tier cost, recurring subscription fees | Free software; compute/hosting costs only |
| **Audit & Compliance Frameworks** | Out-of-the-box audit-ready reports (SOC 2, ISO 27001, HIPAA) | Scripted benchmarks (CIS, NIST) needing custom reporting |
| **Data Privacy & Air-gapping** | Cloud-hosted telemetry (subject to compliance boundaries) | 100% self-hosted, private, and air-gap compatible |
| **Ecosystem Extensibility** | Vendor API & marketplace integrations | Full code customizability and extensible policy plugins |

---

## 🤝 Contributing

Contributions are welcome! If you know of an awesome open-source project or notable cloud security suite that should be included:

1. Fork this repository.
2. Add the tool to the appropriate table. For open-source tools, include the social star badge linking to `/stargazers`.
3. Submit a pull request with a brief summary of the changes.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
