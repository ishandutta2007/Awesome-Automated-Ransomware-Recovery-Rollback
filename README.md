# Awesome-Automated-Ransomware-Recovery-Rollback

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **pricing is scattered across marketplace listings and promotional PDFs**, and the open-source side is essentially empty.

## The data problems

**Druva's ransomware recovery is a quarantine workflow, not an automated rollback.** The documentation describes manually quarantining snapshots from a date you specify, or bulk-quarantining via CSV, with a system-defined floor of January 6, 2020 . Druva's starting price is **$4 per user per month** , but that is the backup platform, not ransomware recovery specifically.

**Veeam's ransomware recovery is bundled into Data Platform editions.** The Brazilian store lists Essentials at R$2,899/year, Foundation R$9,199, Advanced R$11,299, and Premium R$13,599 (1 pack = 10 instances) . Ransomware response and recovery is a Premium feature. **Do not present these BRL figures as USD list prices.**

**Cohesity's clean room is a managed service via 11:11 Systems, priced per-terabyte on a monthly recurring basis** . No rate card surfaced.

**Commvault's Cleanroom Recovery is enterprise-only.** An independent review states implementation complexity is "significant" and the platform is "not appropriate for organisations without that expertise" . Pricing is front-end-terabyte based; a global enterprise programme typically lands at **$400K–$3M+ annually**, with five-year TCO **$3M–$7M** for a 1,000-workload estate .

**Rubrik's Enterprise Edition includes ransomware remediation and 200TB of Cloud Vault.** Microsoft Marketplace lists **$90,000/month, $100,000/year, $200,000/2 years, $300,000/3 years** for Enterprise Edition . A separate listing shows **$110,300/year** for Enterprise Edition . These are marketplace prepay listings, not vendor rate cards.

**Acronis Active Protection is a feature of Cyber Protect, not a standalone product.** Advanced plans start at **€70.99/year** . Active Protection is included in all plans as the anti-ransomware component.

**Datto EDR is not ransomware recovery.** The pricing page describes endpoint detection and response at **$2.99–$30/endpoint/month**, explicitly noting EDR is not a firewall and supplements antivirus . **Do not present it as a ransomware rollback tool.**

**Zerto's fast-track promotion is for 25 VM enterprise replication, valid through October 31, 2026.** It delivers continuous data protection with RPO in seconds and RTO in minutes . **This is a promotional offer, not a list price.**

**HYCU Protégé has no pricing surfaced.** The disaster recovery page describes immutable air-gapped backups and one-click restoration, with pay-as-you-go SaaS pricing . No dollar figure.

**IBM FlashSystem Ransomware Recovery did not surface at all.** No product page, no pricing, no feature detail.

## Open-source: what actually exists

**Nothing.** The search results contain no open-source ransomware recovery or rollback project. The only open-source-adjacent mention is a Datto FAQ noting "open EDR" may have lower initial costs but "can come with costly risks and complexity" . That is not a ransomware recovery tool.

**Do not fabricate an open-source section.** If you want one, the honest statement is: no mature open-source equivalent to commercial ransomware recovery rollback exists in these results.

## What I recommend

**Split into two honest categories:**

**1. Cyber Recovery & Clean Room Platforms** (proprietary, enterprise-priced):
- **Commvault** — Cleanroom Recovery; $400K–$3M+/year enterprise, 1,000-workload TCO $3M–$7M 
- **Rubrik** — Enterprise Edition with ransomware remediation; $90K/month to $300K/3-year prepay 
- **Cohesity** — Clean Room via 11:11 Systems; per-TB monthly managed service 
- **Veeam** — Premium edition includes ransomware response; BRL pricing only 
- **Zerto** — CDP with seconds RPO; promotional 25-VM offer through Oct 31, 2026 
- **Druva** — Quarantine workflow; $4/user/month platform 
- **HYCU** — One-click recovery; pay-as-you-go, no rate surfaced 
- **Acronis** — Active Protection included in Cyber Protect; Advanced from €70.99/year 

**2. Not Ransomware Recovery:**
- **Datto EDR** — endpoint detection, not rollback 
- **IBM FlashSystem** — no data surfaced

**Mark all commercial entries as "pricing not surfaced" or cite the specific marketplace/promotional figure with its caveat.** Do not present Veeam's BRL store prices, Rubrik's prepay listings, or Zerto's promotional offer as standard USD list pricing.

**State plainly that no open-source ransomware recovery rollback tool surfaced.** That is the honest finding.

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate open-source entries, present Datto EDR as ransomware rollback, or cite promotional/marketplace figures as standard list prices.
