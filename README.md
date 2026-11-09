# Awesome-Automated-Ransomware-Recovery-Rollback
# Awesome-Automated-Ransomware-Recovery-Rollback

## Top Automated Ransomware Recovery & Rollback Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Ransomware Detection, Clean Recovery & Automated Rollback Orchestration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Ransomware Recovery & Rollback**. These tools help organizations detect ransomware activity, identify clean recovery points, restore workloads into isolated environments, and roll back to a known-good state without reinfection—covering immutable backups, threat scanning, clean rooms, and orchestrated recovery workflows.

**Examples** include Druva Cyber Recovery Runbooks, Rubrik Surgical Recovery, Veeam Ransomware Recovery, Cohesity Clean Room, Commvault Cleanroom Recovery, Acronis Cyber Protect, Datto Ransomware Detection, Zerto Cyber Resilience, HYCU Protégé, and IBM FlashSystem Cyber Resilience (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted ransomware detection, file-level rollback, backup orchestration, and recovery automation—ideal for SREs, security engineers, platform teams, and developers building transparent, vendor-neutral ransomware resilience workflows.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global cyber resilience, ransomware recovery, and protection market is valued at approximately **$7B to $32B** (with recovery-specific and cyber-vault software accounting for ~$7B–$10.6B) and is projected to expand past **$28B to $136B+ by 2035** at a **CAGR of ~14.9%–16.2%**. The sector exhibits a **moderately concentrated core with a moderately fragmented perimeter**: tier-one enterprise data estates are dominated by entrenched data management and storage titans (IBM, Veeam, Rubrik, Cohesity, Commvault), while a dynamic, fragmented outer ecosystem of specialized SaaS providers, MSP tooling, and cloud-native recovery orchestrators competes across niche workloads and mid-market clean-room deployments.

## SaaS/Hosted Platforms

| Platform | Valuation / Scale | Starting Price | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[IBM FlashSystem Cyber Resilience](https://www.ibm.com/)** | ~$235B Market Cap (NYSE: IBM) | Starting at ~$10,000–$15,000 (entry-level 5015/5045 hardware array) | 14-day zero-cost on-premises test drive hardware loan; online remote PoC access | FlashCore Module (FCM) uses ML models to detect ransomware in under one minute; immutable isolated copies enable rapid restoration with IBM Power Cyber Vault for sub-minute recovery [citation:10]. |
| **[Rubrik Surgical Recovery](https://www.rubrik.com/)** | ~$22B Market Cap (NYSE: RBRK; $1.46B ARR) | Starting at ~$57,000/year (or ~$3–$6/user/month for M365; ~$80–$200/TB/year for Cloud Vault) | 30-day guided SaaS trial (workload-capped evaluation through sales representative) | Recovers the most recent compromised snapshot clean—excluding quarantined files without rolling back to a stale recovery point; available for VMware VMs and Amazon EC2 with fail-closed design [citation:2]. |
| **[Veeam Ransomware Recovery](https://www.veeam.com/)** | ~$15B Valuation ($2B+ ARR) | Starting at $95/workload/year (Veeam Data Platform Essentials 5-instance pack at $475/year) | Permanently free Community Edition (up to 10 workloads, no enterprise SLA); 30-day fully functional enterprise trial | Combines immutable/air-gapped backups, inline threat detection, Recon Scanner (MITRE ATT&CK mapping), and Clean Rooms (DataLabs/SureBackup) for validated clean recovery [citation:14]. |
| **[Cohesity Clean Room](https://www.cohesity.com/)** | ~$7B–$8B Valuation ($1.6B+ Pro Forma ARR post-Veritas) | Starting at ~$29,100/year on AWS Marketplace (DataProtect as a Service baseline ~10 BETB) | 30-day free trial of Cohesity DataProtect as a Service via cloud marketplaces | Isolated recovery environment with threat scanning, anomaly detection, and RecoveryAgent blueprints; Nutanix integration provides automated clean room instantiation and Flow-based network isolation [citation:4][citation:15]. |
| **[Commvault Cleanroom Recovery](https://www.commvault.com/)** | ~$6.8B Market Cap (NASDAQ: CVLT; $1.1B+ ARR) | Starting at $1.70/user/month (M365 backup) / $58.50/TB/month (Cleanroom Recovery sold in 10TB FETB packs) | 30-day full-feature free trial (self-service access to Commvault Cloud and Cleanroom Recovery, no credit card required) | On-demand secure isolated environment with automated cleanroom setup, Azure/AWS threat scanning, and integrated runbooks for one-click orchestration of network, VM, and security controls [citation:5]. |
| **[Datto Ransomware Detection](https://www.datto.com/)** | $6.2B Acquisition Valuation (by Kaseya) | Starting at ~$2.00–$3.00/user/month (Datto SaaS Protection via MSP channels) | 14-to-30 day sandbox free trial (provisioned evaluation tenant via MSP / sales onboarding) | Workplace Security Detection & Management uses complex algorithms and Symantec Endpoint Protection to detect ransomware, auto-quarantine affected devices, stop sync, and streamline file reversion [citation:7]. |
| **[Acronis Cyber Protect](https://www.acronis.com/)** | ~$3.5B Valuation ($400M+ Revenue; majority owned by EQT) | Starting at $85.00/workstation/year (Standard business edition) | 30-day full-access free trial (up to evaluation device capacity across cloud and local workloads) | Active Protection with behavior-based ransomware detection, backup file protection, and automatic rollback of affected files; monitors network shares and NAS for ransomware activity [citation:6]. |
| **[Druva Cyber Recovery Runbooks](https://www.druva.com/)** | ~$2.0B Valuation ($200M+ SaaS ARR) | Starting at $8.00/user/month (M365/endpoint backup); infrastructure tiers billed per TB/month | 30-day free trial (self-service onboarding across cloud workloads) | Automated threat-aware recovery with Scheduled Cyber Recovery Testing and Live Incident Recovery, using Isolated Recovery Environment (IRE) and IOC scanning before production restore; supports VMware and Microsoft 365 workloads [citation:1][citation:12]. |
| **[Zerto Cyber Resilience](https://www.zerto.com/)** | $374M Acquisition Valuation (HPE subsidiary; ~$130M run-rate) | Starting at ~$1,000–$1,400/protected VM/year (Enterprise Cloud Edition) | 14-day free trial (capped at protecting up to 15 virtual machines) | Continuous replication with real-time encryption detection, 5–15 second recovery point granularity, and rapid multi-VM clean room recovery for on-premises and cloud workloads [citation:8]. |
| **[HYCU Protégé](https://www.hycu.com/)** | ~$300M–$500M Valuation ($30M–$50M ARR) | Starting at $1.20/user/month (Identity/Okta backup) / $2.25/user/month (M365) / $5,000/year Starter Bundle | 14-to-30 day free trial (depending on connected SaaS/cloud workload) | SaaS data protection with immutable air-gapped backups, one-click self-service recovery, and ransomware protection policies for on-premises and cloud workloads [citation:9]. |

## Open-Source GitHub Projects

- **[Linux-Ransomware-Recovery](https://github.com/a1anchristy/Linux-Ransomware-Recovery)**  
  Go-based real-time file system monitor with hash-based backup, suspicious extension/content detection, automatic rollback, and Rsync over SSH remote backup for Linux environments [citation:11].

### Additional Strong Open-Source Options

- **[BorgBackup](https://github.com/borgbackup/borg)** and **[Restic](https://github.com/restic/restic)** for immutable, deduplicated, encrypted backups usable as clean recovery foundations.
- **[Velero](https://github.com/vmware-tanzu/velero)** for Kubernetes cluster backup and restore orchestration with pre/post hooks.
- **[ReaR (Relax-and-Recover)](https://github.com/rear/rear)** for Linux disaster recovery with bootable rescue images and multi-backend support.
- **[LitmusChaos](https://github.com/litmuschaos/litmus)** and **[Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh)** for recovery drill automation and failure injection testing.
- **Ransomware decryption toolkits** (e.g., **[lockbit-rescue](https://github.com/Saddytech/lockbit-rescue)**, **[c3rb3r-rescue](https://github.com/soimy/c3rb3r-rescue)**) for evidence-preserving recovery when backups are insufficient.
- Many community **file integrity monitoring** and **honeypot** projects for early ransomware detection.

**Frameworks for building custom systems**: Combine **Linux-Ransomware-Recovery** for real-time rollback, **Restic/BorgBackup** for immutable backup stores, **Velero** for Kubernetes workloads, and **GitHub Actions** with **Prometheus** for recovery validation pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Ransomware recovery tooling must be validated against your organization's RTO/RPO requirements and tested regularly for effectiveness.
- Self-hosted open-source solutions require proper isolation, access control, and immutable backup strategies to prevent reinfection during recovery.

---

**Made for SREs, security engineers, platform teams, and cyber resilience architects.**  
Let's make ransomware recovery more open, automated, and provable.
