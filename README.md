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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Druva Cyber Recovery Runbooks](https://www.druva.com/)**  
  Automated threat-aware recovery with Scheduled Cyber Recovery Testing and Live Incident Recovery, using Isolated Recovery Environment (IRE) and IOC scanning before production restore; supports VMware and Microsoft 365 workloads [citation:1][citation:12].

- **[Rubrik Surgical Recovery](https://www.rubrik.com/)**  
  Recovers the most recent compromised snapshot clean—excluding quarantined files without rolling back to a stale recovery point; available for VMware VMs and Amazon EC2 with fail-closed design [citation:2].

- **[Veeam Ransomware Recovery](https://www.veeam.com/)**  
  Combines immutable/air-gapped backups, inline threat detection, Recon Scanner (MITRE ATT&CK mapping), and Clean Rooms (DataLabs/SureBackup) for validated clean recovery [citation:14].

- **[Cohesity Clean Room](https://www.cohesity.com/)**  
  Isolated recovery environment with threat scanning, anomaly detection, and RecoveryAgent blueprints; Nutanix integration provides automated clean room instantiation and Flow-based network isolation [citation:4][citation:15].

- **[Commvault Cleanroom Recovery](https://www.commvault.com/)**  
  On-demand secure isolated environment with automated cleanroom setup, Azure/AWS threat scanning, and integrated runbooks for one-click orchestration of network, VM, and security controls [citation:5].

- **[Acronis Cyber Protect](https://www.acronis.com/)**  
  Active Protection with behavior-based ransomware detection, backup file protection, and automatic rollback of affected files; monitors network shares and NAS for ransomware activity [citation:6].

- **[Datto Ransomware Detection](https://www.datto.com/)**  
  Workplace Security Detection & Management uses complex algorithms and Symantec Endpoint Protection to detect ransomware, auto-quarantine affected devices, stop sync, and streamline file reversion [citation:7].

- **[Zerto Cyber Resilience](https://www.zerto.com/)**  
  Continuous replication with real-time encryption detection, 5–15 second recovery point granularity, and rapid multi-VM clean room recovery for on-premises and cloud workloads [citation:8].

- **[HYCU Protégé](https://www.hycu.com/)**  
  SaaS data protection with immutable air-gapped backups, one-click self-service recovery, and ransomware protection policies for on-premises and cloud workloads [citation:9].

- **[IBM FlashSystem Cyber Resilience](https://www.ibm.com/)**  
  FlashCore Module (FCM) uses ML models to detect ransomware in under one minute; immutable isolated copies enable rapid restoration with IBM Power Cyber Vault for sub-minute recovery [citation:10].

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
