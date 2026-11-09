# Awesome-Automated-Ransomware-Recovery-Rollback
# Awesome-Automated-Ransomware-Recovery-Rollback

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **pricing is scattered across marketplace listings and promotional PDFs**, and the open-source side is essentially empty.

## The data problems

**Rubrik's ransomware recovery is bundled into Enterprise Edition.** Microsoft Marketplace lists Enterprise Edition at **$90,000/month**, **$100,000/year**, **$200,000/2 years**, **$300,000/3 years**, or **$400,000 one-time** . A separate listing shows **$110,300/year** . These are marketplace prepay listings, not vendor rate cards. The product includes **200TB of Rubrik Cloud Vault** and ransomware remediation features .

**Veeam's ransomware recovery is a Premium Edition feature.** The Veeam store lists Premium at **$2,275 per pack per year** (1 pack = 10 instances) . The BRL store shows **R$13,899 per pack** for Premium . Ransomware response and recovery is a Premium feature, not available on Essentials or Foundation .

**Cohesity's clean room is a managed service via 11:11 Systems, priced per-terabyte on a monthly recurring basis** with no upfront capital . No rate card surfaced.

**Commvault's Cleanroom Recovery is sold as a 3-month subscription per 10TB recovery group.** A Polish reseller lists it at **26,802.98 zł net** (~$6,800 USD) for 3 months . This is a reseller listing, not a global rate card.

**Zerto's fast-track promotion is for 25 VM enterprise replication, valid through October 31, 2026.** It delivers continuous data protection with RPO in seconds and RTO in minutes . **This is a promotional offer, not a list price.**

**Acronis Active Protection is included in Cyber Protect Standard.** Advanced plans start at **€70.99/year** . Active Protection is the anti-ransomware component, not a standalone product.

**Datto ALTO 5 includes ransomware detection and Rapid Rollback.** Pricing is quote-only via resellers; no public rate . Datto SIRIS 6 is the larger option.

**HYCU Protégé has no pricing surfaced.** Usage-based pricing by VM, TiB, or GiB; contact HYCU for details .

**IBM FlashSystem's ransomware detection is a storage feature, not a recovery rollback platform.** FCM4 monitors I/O statistics with machine learning to detect anomalies "in less than a minute" . No pricing for the ransomware feature surfaced—it is part of the FlashSystem array.

## Open-source: what actually exists

**tibet-snap** is the only open-source project surfaced: **MIT licensed**, Python, creates **cryptographically sealed snapshots** of system state with SHA-256 hashes, compares snapshots to see what changed, and **auto-generates a rollback plan** with restore/remove/revert actions .

**tibet-snap is a filesystem snapshot and diff tool, not a ransomware recovery platform.** It does not detect ransomware, isolate infected systems, or orchestrate mass recovery. It generates a rollback plan for file changes you have already snapshotted. **Do not present it as a replacement for Rubrik or Veeam.**

**No star count surfaced.** Do not invent one.

## What I recommend

**Split into two honest categories:**

**1. Cyber Recovery & Ransomware Rollback Platforms** (proprietary, enterprise-priced):
- **Rubrik** — Enterprise Edition $90K/mo to $400K one-time; includes 200TB Cloud Vault 
- **Veeam** — Premium $2,275/pack/year (10 instances) 
- **Cohesity** — Clean Room via 11:11 Systems; per-TB monthly managed 
- **Commvault** — Cleanroom Recovery; ~$6,800 USD per 10TB for 3 months (reseller) 
- **Zerto** — CDP with seconds RPO; promotional 25-VM offer through Oct 31, 2026 
- **Acronis** — Active Protection included; from €70.99/year 
- **Datto ALTO 5** — Rapid Rollback; quote-only 
- **HYCU** — usage-based, no rate surfaced 
- **IBM FlashSystem** — ransomware detection in storage; no standalone price 

**2. Open-Source (filesystem snapshot only):**
- **tibet-snap** — MIT, cryptographic snapshots, diff, rollback plan generation 

**Mark all commercial entries as "pricing not surfaced" or cite the specific marketplace/reseller/promotional figure with its caveat.** Do not present Veeam's BRL store prices, Rubrik's prepay listings, or Zerto's promotional offer as standard USD list pricing.

**State plainly that no open-source ransomware recovery rollback platform surfaced.** tibet-snap generates rollback plans for file changes—it does not detect or recover from ransomware .

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate open-source platform entries, present IBM's storage detection as a recovery platform, or cite reseller/promotional figures as standard list prices.
