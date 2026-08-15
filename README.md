<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080c09,50:00994a,100:00ff41&height=180&section=header&text=Tharaka%20Dissanayaka&fontSize=42&fontColor=f0fff5&fontAlignY=32&desc=Senior%20Security%20%26%20Systems%20Engineer&descSize=16&descAlignY=52" alt="header"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2600&pause=900&color=00FF41&center=true&vCenter=true&width=560&lines=Threat+Detection+%26+Endpoint+Defence;SOC+Operations+%C2%B7+~50+Managed+Tenants;Incident+Response+%C2%B7+Threat+Hunting;Vulnerability+Management+Research" alt="roles"/>

<br/>

<a href="https://sandakelum97.github.io/"><img src="https://img.shields.io/badge/Portfolio-00ff41?style=for-the-badge&logo=githubpages&logoColor=black"/></a>
<a href="https://linkedin.com/in/tharaka-dissanayaka"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://medium.com/@sandakelum.97"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/></a>
<a href="mailto:sandakelum.97@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<table>
<tr>
<td align="center" width="180">
<h2>8+</h2>
<sub><b>YEARS IN SECURITY</b></sub>
</td>
<td align="center" width="180">
<h2>~50</h2>
<sub><b>MANAGED TENANTS</b></sub>
</td>
<td align="center" width="180">
<h2>17</h2>
<sub><b>CERTIFICATIONS</b></sub>
</td>
<td align="center" width="180">
<h2>MSc</h2>
<sub><b>IN PROGRESS</b></sub>
</td>
</tr>
</table>

</div>

---

## `01` · About

Security engineer with 8+ years across cybersecurity, enterprise infrastructure and network security. I run threat detection and endpoint defence for roughly 50 managed enterprise tenants at an Australian MSSP — detection triage, incident response, vulnerability management, and the occasional 2 a.m. containment call.

My background runs both ways. I came up through infrastructure — Windows Server, Active Directory, VMware, ERP, backup and DR — before moving into security. That shows up in how I triage: knowing why a line-of-business application spawns a strange-looking process is often the difference between a five-minute false positive and a three-hour incident.

> **Working belief** — a detection you can't explain in a ticket note isn't a detection, it's a guess.

---

## `02` · Research

<table>
<tr><td>

**Executive MSc in Information Security** · Asia e University, Malaysia · Nov 2025 – Dec 2026

### Automating Environmental Decision Points in Stakeholder-Specific Vulnerability Categorization
*A Multi-Tenant Evaluation Against CVSS-Based Remediation Baselines*

</td></tr>
</table>

**The gap.** Vulnerability prioritisation still runs on CVSS base scores, which describe a flaw in the abstract and say nothing about whether the affected system is internet-facing, patched, or business-critical. SSVC addresses that, but its environmental decision points — system exposure, mission impact — are assigned by hand and don't scale past a handful of assets. Existing automation such as CISA Vulnrichment resolves the vulnerability-specific factors and stops, because the organisation-specific ones can't be derived from public data.

**The question.** Whether those environmental factors can instead be derived from managed service provider telemetry — asset inventories, internet exposure, patch state, business criticality — completing the SSVC decision tree without manual analyst input.

<details>
<summary><b>Method and evaluation</b></summary>

<br/>

Historical backtesting against public datasets — **NVD**, **EPSS**, **CISA KEV**, **Vulnrichment** — comparing automated SSVC prioritisation against conventional CVSS severity-based remediation across three measures:

| Measure | What it captures |
|---|---|
| Exploitation coverage | Share of actually-exploited CVEs caught by each prioritisation scheme |
| Efficiency | Precision of the remediation queue — how much effort goes to vulnerabilities that mattered |
| Remediation effort | Total volume of work each approach demands |

The environmental model is built either from aggregated, anonymised statistics drawn from a real multi-tenant managed services environment (subject to approval) or from a fully synthetic dataset where approval is unavailable.

**What it settles:** whether automated, context-aware prioritisation produces better remediation outcomes than severity-ranked patching — or whether the added machinery buys nothing a CVSS cutoff doesn't already deliver.

</details>

---

## `03` · What I Do

<table>
<tr>
<td width="50%" valign="top">

### Threat Detection &amp; Response
Detection triage and tuning across EDR/XDR · process lineage and LOLBin analysis · false-positive adjudication and exclusion scoping · incident response and containment · phishing and BEC investigation · account-compromise response across M365 and Entra ID · KQL threat hunting

</td>
<td width="50%" valign="top">

### Security Operations
SIEM detection engineering and rule tuning · alert triage at MSSP scale · SOC documentation and playbook development · client-facing advisories and incident reporting · post-incident review

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Vulnerability Management
Exposure analysis and asset reconciliation · CVE research and advisory writing · remediation prioritisation and closure criteria · patch cycle coordination · risk register and exception management

</td>
<td width="50%" valign="top">

### Identity &amp; Access
Microsoft Entra ID · Conditional Access design · MFA and passwordless rollout · privileged access review · Zero Trust architecture

</td>
</tr>
</table>

---

## `04` · Stack

<details open>
<summary><b>SOC &amp; Threat Detection</b></summary>
<br/>

![Defender XDR](https://img.shields.io/badge/Microsoft_Defender_XDR-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![CrowdStrike](https://img.shields.io/badge/CrowdStrike_Falcon-E01A2B?style=flat-square&logo=crowdstrike&logoColor=white)
![Sentinel](https://img.shields.io/badge/Microsoft_Sentinel_(KQL)-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Proofpoint](https://img.shields.io/badge/Proofpoint_Email_Security-2E7D32?style=flat-square)
![ThreatLocker](https://img.shields.io/badge/ThreatLocker-1B3A5C?style=flat-square)
![DarkWeb ID](https://img.shields.io/badge/DarkWeb_ID-4A148C?style=flat-square)

</details>

<details open>
<summary><b>Incident Response &amp; Threat Hunting</b></summary>
<br/>

![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-C00?style=flat-square)
![KQL](https://img.shields.io/badge/KQL_Hunting-004B87?style=flat-square)

AiTM phishing investigation and token-theft response · EDR triage across process injection, AMSI tampering, VSS deletion and LSASS access · adversary emulation · CVE triage and threat intelligence correlation

</details>

<details open>
<summary><b>Vulnerability Management</b></summary>
<br/>

![Nessus](https://img.shields.io/badge/Tenable_Nessus-00B4A0?style=flat-square)
![Defender TVM](https://img.shields.io/badge/Defender_TVM-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Defender for Cloud](https://img.shields.io/badge/Defender_for_Cloud-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![SSVC](https://img.shields.io/badge/SSVC_%2F_EPSS_%2F_KEV-6A1B9A?style=flat-square)

Remediation tracking, closure criteria, and client-facing exposure reporting.

</details>

<details>
<summary><b>Identity &amp; Access Management</b></summary>
<br/>

![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Conditional Access](https://img.shields.io/badge/Conditional_Access-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![AD](https://img.shields.io/badge/Active_Directory_%2F_GPO-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

MFA and passwordless rollout · RBAC and least-privilege design.

</details>

<details>
<summary><b>Network &amp; Firewall</b></summary>
<br/>

![FortiGate](https://img.shields.io/badge/FortiGate-EE3124?style=flat-square&logo=fortinet&logoColor=white)
![FortiManager](https://img.shields.io/badge/FortiManager_%2F_FortiAnalyzer-EE3124?style=flat-square&logo=fortinet&logoColor=white)
![SonicWall](https://img.shields.io/badge/SonicWall-FF791A?style=flat-square)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![Auvik](https://img.shields.io/badge/Auvik-00A0DF?style=flat-square)
![Inforcer](https://img.shields.io/badge/Inforcer-263238?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![PRTG](https://img.shields.io/badge/PRTG-004C97?style=flat-square)

IPsec and SSL VPN · VLAN design and segmentation · routing and switching.

</details>

<details>
<summary><b>Tooling &amp; Automation</b></summary>
<br/>

![ConnectWise](https://img.shields.io/badge/ConnectWise_PSA_%2F_RMM_%2F_SIEM-1F4E79?style=flat-square)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=nodedotjs&logoColor=white)
![AppSheet](https://img.shields.io/badge/Google_AppSheet-4285F4?style=flat-square&logo=google&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</details>

<details>
<summary><b>Governance &amp; Compliance</b></summary>
<br/>

![ISO 27001](https://img.shields.io/badge/ISO_27001-005A9C?style=flat-square)
![NIST CSF](https://img.shields.io/badge/NIST_CSF-1B5E20?style=flat-square)
![COBIT](https://img.shields.io/badge/COBIT-37474F?style=flat-square)
![Zero Trust](https://img.shields.io/badge/Zero_Trust_Architecture-263238?style=flat-square)

Change management · security runbook authoring · policy and control documentation.

</details>

<details>
<summary><b>Infrastructure</b></summary>
<br/>

![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![VMware](https://img.shields.io/badge/VMware_ESXi-607078?style=flat-square&logo=vmware&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Dynamics](https://img.shields.io/badge/Dynamics_NAV_%2F_BC-002050?style=flat-square&logo=microsoft&logoColor=white)
![M365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoftoffice&logoColor=white)

</details>

---

## `05` · Certifications

<table>
<tr>
<td align="center" width="25%"><b>SC-100</b><br/><sub>Cybersecurity Architect Expert</sub></td>
<td align="center" width="25%"><b>SC-200</b><br/><sub>Security Operations Analyst</sub></td>
<td align="center" width="25%"><b>SC-300</b><br/><sub>Identity &amp; Access Administrator</sub></td>
<td align="center" width="25%"><b>AZ-900</b><br/><sub>Azure Fundamentals</sub></td>
</tr>
<tr>
<td align="center"><b>MS Applied Skills</b><br/><sub>Defend Against Cyberthreats · Defender XDR</sub></td>
<td align="center"><b>ISC2 CC</b><br/><sub>Certified in Cybersecurity</sub></td>
<td align="center"><b>Cisco CCNA</b><br/><sub>Enterprise &amp; Security</sub></td>
<td align="center"><b>Cisco CyberOps</b><br/><sub>CyberOps Associate</sub></td>
</tr>
<tr>
<td align="center"><b>Cisco DevNet</b><br/><sub>DevNet Associate</sub></td>
<td align="center"><b>Fortinet NSE 3</b><br/><sub>Network Security Associate</sub></td>
<td align="center"><b>SecOps CNSP</b><br/><sub>Certified Network Security Practitioner</sub></td>
<td align="center"><b>MITRE ATT&amp;CK</b><br/><sub>Defender Fundamentals</sub></td>
</tr>
<tr>
<td align="center"><b>SentinelOne</b><br/><sub>Singularity Admin Essentials</sub></td>
<td align="center"><b>Google Cybersecurity</b><br/><sub>Professional Certificate</sub></td>
<td align="center"><b>Google Workspace</b><br/><sub>Professional Administrator</sub></td>
<td align="center"><b>Google GenAI</b><br/><sub>Generative AI Leader</sub></td>
</tr>
<tr>
<td align="center"><b>KodeKloud</b><br/><sub>DevOps Engineer Level 1</sub></td>
<td align="center" colspan="3"><sub><i>No exam scores listed — credentials verifiable via the portfolio site</i></sub></td>
</tr>
</table>

**In progress** — TCM PNPT (Practical Network Penetration Tester) · Google Associate Cloud Engineer
**Planned** — ISC2 CISSP (Q3 2026) · HTB Certified Active Directory Bootcamp Expert

### Education

| Qualification | Institution | Period |
|---|---|---|
| Executive MSc in Information Security | Asia e University (AeU), Malaysia | Nov 2025 – Dec 2026 |
| Diploma in Network Engineering | National Institute of Business Management (NIBM) | 2019 – 2021 |
| Certificate in Linux Network Administration | Turnkey IT Campus | — |

---

## `06` · Selected Work

<table>
<tr>
<td width="50%" valign="top">

**[mssp-soc-playbooks](https://github.com/sandakelum97/mssp-soc-playbooks)**
KQL queries and detection playbooks from MSSP SOC operations.

</td>
<td width="50%" valign="top">

**[SC200-SC300-study-plan](https://github.com/sandakelum97/SC200-SC300-study-plan)**
Structured study plan and notes for the Microsoft SC-200 and SC-300 exams.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[security-training](https://github.com/sandakelum97/security-training)**
Gamified security awareness platform — phishing and password challenges, leaderboards, JWT auth, PostgreSQL. · [live](https://chesmi-security-training.vercel.app)

</td>
<td width="50%" valign="top">

**[prompt-engineering-trainer](https://github.com/sandakelum97/prompt-engineering-trainer)**
Hands-on tool for practising prompt patterns in security and productivity workflows.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[sandakelum97.github.io](https://github.com/sandakelum97/sandakelum97.github.io)**
Portfolio site — Three.js background, live GitHub and Medium feeds, dark/light themes.

</td>
<td width="50%" valign="top">

**[claude-skills](https://github.com/sandakelum97)** *(private)*
Version-controlled Agent Skills for SOC triage, CVE advisories and exposure analysis.

</td>
</tr>
</table>

---

## `07` · Writing

I write up the things that took me too long to work out the first time — detection triage reasoning, vulnerability management practice, and the operational side of security that rarely makes it into vendor documentation.

<a href="https://medium.com/@sandakelum.97"><img src="https://img.shields.io/badge/Read_on_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/></a>

---

<div align="center">

## `08` · Activity

<img height="160" src="https://github-readme-stats.shion.dev/api?username=sandakelum97&theme=chartreuse-dark&hide_border=true&include_all_commits=false&count_private=false"/>
<img height="160" src="https://streak-stats.demolab.com/?user=sandakelum97&theme=chartreuse-dark&hide_border=true"/>

<img height="150" src="https://github-readme-stats.shion.dev/api/top-langs/?username=sandakelum97&theme=chartreuse-dark&hide_border=true&layout=compact"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=sandakelum97&style=flat-square&color=00ff41"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff41,50:00994a,100:080c09&height=100&section=footer"/>

</div>
