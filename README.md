<h1 align="center">Tharaka Dissanayaka</h1>
<p align="center">
  <b>Senior Security &amp; Systems Engineer</b> · Threat Detection &amp; Endpoint Defence · Australian MSSP
</p>

<p align="center">
  <a href="https://linkedin.com/in/tharaka-dissanayaka"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://medium.com/@sandakelum.97"><img src="https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white" alt="Medium"></a>
  <a href="mailto:sandakelum.97@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://sandakelum97.github.io/"><img src="https://img.shields.io/badge/Portfolio-00ff41?logo=githubpages&logoColor=black" alt="Portfolio"></a>
</p>

---

## About

Security engineer with 8+ years across cybersecurity, enterprise infrastructure and network security. I currently run threat detection and endpoint defence for a portfolio of roughly 50 managed enterprise tenants at an Australian MSSP — which means my day is detection triage, incident response, vulnerability management and the occasional 2 a.m. containment call.

My background is unusual in that it runs both ways: I came up through infrastructure — Windows Server, Active Directory, VMware, ERP, backup and DR — before moving into security. That tends to show up in how I triage. Knowing why a line-of-business application spawns a strange-looking process is often the difference between a five-minute false positive and a three-hour incident.

Currently reading for an **Executive MSc in Information Security**.

- 🔭 Building reusable detection-triage and IR playbooks, and automating the parts of SOC work that shouldn't need a human
- 🌱 Deepening Microsoft Sentinel / KQL detection engineering and identity-centric threat detection
- 💬 Happy to talk about EDR tuning, phishing triage, vulnerability management programmes, and Zero Trust rollouts that survive contact with real users
- ⚡ Firm belief: a detection you can't explain in a ticket note isn't a detection, it's a guess

---

## Research

**Executive MSc in Information Security · Asia e University, Malaysia**

**Automating Environmental Decision Points in Stakeholder-Specific Vulnerability Categorization: A Multi-Tenant Evaluation Against CVSS-Based Remediation Baselines**

Vulnerability prioritisation still runs largely on CVSS base scores, which describe a flaw in the abstract and say nothing about whether the affected system is internet-facing, patched, or business-critical. SSVC addresses that gap, but its environmental decision points — system exposure, mission impact — are assigned by hand, which does not scale past a handful of assets. Existing automation such as CISA Vulnrichment resolves the vulnerability-specific factors and stops there, because the organisation-specific ones cannot be derived from public data.

This research asks whether those environmental factors can be derived instead from managed service provider telemetry — asset inventories, internet exposure, patch state, business criticality — completing the SSVC decision tree without manual analyst input.

**Method.** Historical backtesting against public datasets (NVD, EPSS, CISA KEV, Vulnrichment), comparing automated SSVC prioritisation with conventional CVSS severity-based remediation across three measures: exploitation coverage, efficiency, and remediation effort. The environmental model is built either from aggregated, anonymised statistics drawn from a real multi-tenant managed services environment (subject to approval) or from a fully synthetic dataset where approval is unavailable.

**The question it settles.** Whether automated, context-aware prioritisation actually produces better remediation outcomes than severity-ranked patching — or whether the added machinery buys nothing a CVSS cutoff does not already deliver.

---

## What I Work On

### Threat Detection &amp; Response
Detection triage and tuning across EDR/XDR platforms · process lineage and LOLBin analysis · false-positive adjudication and exclusion scoping · incident response and containment · phishing and BEC investigation · account-compromise response across Microsoft 365 and Entra ID · threat hunting with KQL

### Security Operations
SIEM detection engineering and rule tuning · alert triage at MSSP scale · SOC documentation and playbook development · client-facing advisories and incident reporting · post-incident review

### Vulnerability Management
Exposure analysis and asset reconciliation · CVE research and advisory writing · remediation prioritisation and closure criteria · patch cycle coordination · risk register and exception management

### Identity &amp; Access
Microsoft Entra ID · Conditional Access design · MFA and passwordless rollout · privileged access review · Zero Trust architecture

### Infrastructure &amp; Networking
Windows Server and Active Directory · VMware ESXi · hybrid backup and disaster recovery · firewall policy and segmentation · routing, switching and wireless · Microsoft Dynamics NAV / Business Central

---

## Tools &amp; Technologies

**SOC &amp; Threat Detection**

![Microsoft Defender XDR](https://img.shields.io/badge/Microsoft_Defender_XDR-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![CrowdStrike Falcon](https://img.shields.io/badge/CrowdStrike_Falcon-E01A2B?style=for-the-badge&logo=crowdstrike&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel_(KQL)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Proofpoint](https://img.shields.io/badge/Proofpoint_Email_Security-2E7D32?style=for-the-badge&logoColor=white)
![ThreatLocker](https://img.shields.io/badge/ThreatLocker-1B3A5C?style=for-the-badge&logoColor=white)
![DarkWeb ID](https://img.shields.io/badge/DarkWeb_ID-4A148C?style=for-the-badge&logoColor=white)

**Incident Response &amp; Threat Hunting**

AiTM phishing investigation and token-theft response · EDR triage across process injection, AMSI tampering, VSS deletion and LSASS access · adversary emulation · CVE triage and threat intelligence correlation

![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C00?style=for-the-badge&logoColor=white)
![KQL](https://img.shields.io/badge/KQL_Threat_Hunting-004B87?style=for-the-badge&logoColor=white)

**Vulnerability Management**

![Nessus](https://img.shields.io/badge/Tenable_Nessus-00B4A0?style=for-the-badge&logoColor=white)
![Defender TVM](https://img.shields.io/badge/Defender_Vulnerability_Mgmt-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Defender for Cloud](https://img.shields.io/badge/Defender_for_Cloud-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![SSVC](https://img.shields.io/badge/SSVC_%2F_EPSS_%2F_KEV-6A1B9A?style=for-the-badge&logoColor=white)

Remediation tracking, closure criteria, and client-facing exposure reporting.

**Identity &amp; Access Management**

![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Conditional Access](https://img.shields.io/badge/Conditional_Access-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory_%2F_GPO-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

MFA and passwordless rollout · RBAC and least-privilege design.

**Network &amp; Firewall**

![FortiGate](https://img.shields.io/badge/FortiGate-EE3124?style=for-the-badge&logo=fortinet&logoColor=white)
![FortiManager](https://img.shields.io/badge/FortiManager_%2F_FortiAnalyzer-EE3124?style=for-the-badge&logo=fortinet&logoColor=white)
![SonicWall](https://img.shields.io/badge/SonicWall-FF791A?style=for-the-badge&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Auvik](https://img.shields.io/badge/Auvik-00A0DF?style=for-the-badge&logoColor=white)
![Inforcer](https://img.shields.io/badge/Inforcer-263238?style=for-the-badge&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![PRTG](https://img.shields.io/badge/PRTG-004C97?style=for-the-badge&logoColor=white)

IPsec and SSL VPN · VLAN design and segmentation · routing and switching.

**Tooling &amp; Automation**

![ConnectWise](https://img.shields.io/badge/ConnectWise_PSA_%2F_RMM_%2F_SIEM-1F4E79?style=for-the-badge&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=nodedotjs&logoColor=white)
![AppSheet](https://img.shields.io/badge/Google_AppSheet-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Governance &amp; Compliance**

![ISO 27001](https://img.shields.io/badge/ISO_27001-005A9C?style=for-the-badge&logoColor=white)
![NIST CSF](https://img.shields.io/badge/NIST_CSF-1B5E20?style=for-the-badge&logoColor=white)
![COBIT](https://img.shields.io/badge/COBIT-37474F?style=for-the-badge&logoColor=white)
![Zero Trust](https://img.shields.io/badge/Zero_Trust_Architecture-263238?style=for-the-badge&logoColor=white)

Change management · security runbook authoring · policy and control documentation.

**Infrastructure**

![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![VMware](https://img.shields.io/badge/VMware_ESXi-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Dynamics](https://img.shields.io/badge/Dynamics_NAV_%2F_BC-002050?style=for-the-badge&logo=microsoft&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=for-the-badge&logo=microsoftoffice&logoColor=white)

---

## Certifications

**Microsoft**

- **SC-100** — Cybersecurity Architect Expert
- **SC-200** — Security Operations Analyst Associate
- **SC-300** — Identity and Access Administrator Associate
- **AZ-900** — Azure Fundamentals
- **Applied Skills** — Defend Against Cyberthreats with Microsoft Defender XDR

**Security**

- **ISC2 CC** — Certified in Cybersecurity
- **Cisco CyberOps Associate**
- **SecOps CNSP** — Certified Network Security Practitioner
- **MITRE ATT&CK Defender** — ATT&CK Fundamentals
- **Fortinet NSE 3** — Network Security Associate
- **SentinelOne** — Singularity Admin Essentials
- **Google Cybersecurity Professional Certificate**

**Network, Cloud &amp; Platform**

- **Cisco CCNA** — Enterprise and Security
- **Cisco DevNet Associate**
- **Google Professional Workspace Administrator**
- **Google Generative AI Leader**
- **KodeKloud** — DevOps Engineer Level 1

**In progress**

- **Executive MSc in Information Security** — Asia e University, Malaysia (Nov 2025 – Dec 2026) · see [Research](#research)
- **TCM PNPT** — Practical Network Penetration Tester
- **Google Associate Cloud Engineer**

**Planned**

- **ISC2 CISSP** — Q3 2026
- **HTB Certified Active Directory Bootcamp Expert**

---

## Education

- **Executive MSc in Information Security** — Asia e University (AeU), Malaysia · Nov 2025 – Dec 2026 · Advanced Cryptography, Cyber Law, Information Assurance
- **Diploma in Network Engineering** — National Institute of Business Management (NIBM) · 2019 – 2021
- **Certificate in Linux Network Administration** — Turnkey IT Campus

---

## Writing

I write up the things that took me too long to work out the first time — detection triage reasoning, vulnerability management practice, and the operational side of security that rarely makes it into vendor documentation.

[![Medium](https://img.shields.io/badge/Read_on_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@sandakelum.97)

---

## Selected Work

- **[mssp-soc-playbooks](https://github.com/sandakelum97/mssp-soc-playbooks)** — KQL queries and detection playbooks from MSSP SOC operations
- **[SC200-SC300-study-plan](https://github.com/sandakelum97/SC200-SC300-study-plan)** — Structured study plan and notes for the Microsoft SC-200 and SC-300 exams
- **[security-training](https://github.com/sandakelum97/security-training)** — Gamified security awareness platform: phishing and password challenges, leaderboards, JWT auth, PostgreSQL · [live](https://chesmi-security-training.vercel.app)
- **[prompt-engineering-trainer](https://github.com/sandakelum97/prompt-engineering-trainer)** — Hands-on tool for practising prompt patterns for security and productivity workflows
- **[sandakelum97.github.io](https://github.com/sandakelum97/sandakelum97.github.io)** — Portfolio site: Three.js background, live GitHub and Medium feeds, dark/light themes

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=sandakelum97&theme=chartreuse-dark&hide_border=false&include_all_commits=false&count_private=false" alt="stats">
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=sandakelum97&theme=chartreuse-dark&hide_border=false" alt="streak">
</p>
<p align="center">
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=sandakelum97&theme=chartreuse-dark&hide_border=false&layout=compact" alt="top languages">
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=sandakelum97&theme=radical&no-frame=false&no-bg=true&margin-w=4" alt="trophies">
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sandakelum97&icon=0&color=0" alt="profile views">
</p>
