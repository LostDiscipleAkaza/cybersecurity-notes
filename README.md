# 🛡️ Cybersecurity Master Study Notes & Certification Roadmaps

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Curriculum: CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B%20(SY0--801)-red.svg)](./01-CompTIA-Security-Plus/)
[![Curriculum: CEH v13](https://img.shields.io/badge/EC--Council-CEH%20v13-green.svg)](./02-Certified-Ethical-Hacker/)
[![Format: Markdown & Word](https://img.shields.io/badge/Format-Markdown%20%7C%20DOCX-purple.svg)](#repository-architecture)
[![Status: Complete Master Edition](https://img.shields.io/badge/Status-Complete%20Master%20Edition-brightgreen.svg)](#)

> A rigorous, comprehensive, beginner-to-analyst cybersecurity study repository and exam preparation system. Covering foundational computer science, systems engineering, network traffic analysis, global & Indian cyber regulations, threat detection & response operations, CompTIA Security+ (SY0-801), and Certified Ethical Hacker (CEH v13).

---

## 📂 Repository Architecture

```text
Cybersecurity-Study-Notes/
├── 00-Cybersecurity-Foundations/
│   ├── 00-Cybersecurity-Foundations.md     # Master Foundations Guide (23 Modules)
│   └── 00-Cybersecurity-Foundations.docx   # Formatted Word Document copy (74 Tables)
│
├── 01-CompTIA-Security-Plus/
│   ├── 01-CompTIA-Security-Plus.md         # Full CompTIA Security+ SY0-801 Study Guide
│   └── 01-CompTIA-Security-Plus.docx       # Formatted Word Document copy (38 Tables)
│
├── 02-Certified-Ethical-Hacker/
│   ├── 02-CEH.md                           # Complete CEH v13 Master Guide (Modules 1-20 + AI)
│   └── 02-CEH.docx                         # Formatted Word Document copy (53 Tables)
│
├── reference-materials/
│   └── Foundations of Cybersecurity.docx   # Original Core Curriculum Reference Text
│
├── .gitignore                              # Git exclusion rules for OS, Python & Office temp files
└── README.md                               # Project Index, Study Path, & Setup Guide
```

---

## 🎯 Curriculum Tracks & Coverage

### 📘 Track 00: Cybersecurity Foundations
*File location*: [`00-Cybersecurity-Foundations/`](./00-Cybersecurity-Foundations/)

An exhaustive 23-module curriculum taking candidates from raw computing fundamentals through enterprise detection engineering and cyber governance:

1. **Pedagogical Blueprint & Orientation**: Study methodology, mental models, and taxonomy.
2. **Computers & Operating Systems**: Von Neumann architecture, CPU registers, RAM, BIOS/UEFI boot process, and kernel rings (Ring 0 vs. Ring 3).
3. **Internet & Data Communication**: Circuit vs. packet switching, encapsulation, global network fabric, and **Cyberspace Dimensions** (Physical, Logical, Semantic, Persona layers; subsea cables, landing stations, Tier 1/2/3 ISPs, IXPs, ASNs, BGP routing, 13 Anycast Root DNS authorities, ICANN, IANA, IETF, and Regional Registries).
4. **Networking Reference Models**: OSI 7-Layer deep dive, TCP/IP suite comparison, and TCP 3-way handshake walkthrough.
5. **IP Addressing, Subnetting, and CIDR**: IPv4 classes, RFC 1918 private addressing, binary subnet math calculation engine, and IPv6 architecture.
6. **Network Protocols & Port Directory**: Core protocols (ARP, DHCP, DNS, TCP, UDP, ICMP, NAT), application protocols, and Master Port cheat sheet.
7. **Linux OS Fundamentals for Security**: Filesystem Hierarchy Standard (FHS), permissions, SUID/SGID, and essential analyst CLI commands.
8. **Windows OS Fundamentals for Security**: User Mode vs. Kernel Mode, NTFS, Alternate Data Streams (ADS), Registry hives, Active Directory, SAM, NTLM/Kerberos, and PowerShell.
9. **Command-Line, Automation, and Scripting**: CLI vs. GUI superiority, practical Bash log audit pipelines, practical Python port scanning & threat intelligence scripts, and SQL relational querying.
10. **Virtualization & Cloud Computing**: Type 1 vs. Type 2 hypervisors, VMs vs. containers, IaaS/PaaS/SaaS models, and Software-Defined Networking (SDN).
11. **Cybersecurity Core Concepts & Risk**: CIA Triad with the **Corporate Engineering Wiki Real-World Scenario**, Personal Data Taxonomy (PII vs. SPII), 4 Risk Responses (Mitigate, Transfer, Avoid, Accept), Likelihood × Impact Matrix, and Attack Surfaces.
12. **Malware Fundamentals & Historical Case Studies**: Taxonomy of malware, Morris Worm, Stuxnet, WannaCry, NotPetya, and SolarWinds.
13. **Identity & Access Management (AAA)**: Authentication, Authorization, Accounting, 5 authentication factors, MFA, Passkeys, SSO, and DAC/MAC/RBAC/ABAC models.
14. **Cryptography Fundamentals & PKI**: Kerckhoffs's principle, Symmetric vs. Asymmetric encryption, Hash functions, Salting, Rainbow tables, Digital Signatures, and PKI certificates.
15. **Security Controls Architecture & Taxonomy**: Control categories, functional types, Defense-in-Depth, Least Privilege, Zero Trust (NIST SP 800-207), and Security Audits (Internal, External, Compliance vs. Technical).
16. **Cyber Law, Regulatory Frameworks & Compliance**:
    - **Indian IT Act, 2000 & 2008 Amendment**: Sections 43, 43A, 66, 66C (identity theft), 66D (phishing), **66F (Cyber Terrorism - life imprisonment)**, 69, 70 (Critical Information Infrastructure & NCIIPC), and 79.
    - **CERT-In Directions (April 2022)**: Mandatory 6-hour incident reporting window, 5-year log retention, and NTP synchronization.
    - **Digital Personal Data Protection Act, 2023 (DPDP Act)**: Data Principal, Data Fiduciary, SDF, Consent Managers, DPBI, and penalties up to ₹250 Crore.
    - Sectoral regulations: RBI, SEBI CSCRF, IRDAI; Comparative Matrix (DPDP Act vs. EU GDPR vs. US HIPAA); Ethics & why "hacking back" is illegal.
17. **Detection, Logging, Packet Analysis & Incident Response**:
    - OS syslog, Windows Security Event Logs (**Event IDs 4624, 4625, 4688, 4720, 1102**), Apache/Nginx web logs, DNS logs, formats (Syslog, JSON, CEF, LEEF), log rotation (`logrotate`), and WORM storage.
    - `tcpdump` CLI usage & Berkeley Packet Filters (BPF); Wireshark GUI dissection, stream following, and exported objects.
    - Suricata multi-threaded IDS/IPS rule syntax (`alert tcp ...`) & `eve.json` output; EDR kernel telemetry and process-tree analysis (`winword.exe` → `powershell.exe`) vs. legacy AV.
    - SIEM correlation rules, alert fatigue tuning, and SOAR automated phishing triage/containment playbooks.
    - IoCs vs. IoAs, Threat Hunting, NIST SP 800-61 vs. SANS PICERL, triage severity matrix, Ransomware & Phishing playbooks, and CSIRT roles.
18. **Modern & Applied Cybersecurity (AppSec, Threat Modeling & CI/CD)**:
    - Cloud Shared Responsibility Model (IaaS/PaaS/SaaS), cloud hardening, SDN control plane vs. data plane, VPCs, Security Groups vs. NACLs.
    - SSDLC & Shift-Left philosophy, STRIDE Threat Modeling with countermeasures, DREAD scoring, Data Flow Diagrams (DFDs), and CI/CD security gates (**SAST, DAST, SCA, Secret Scanning**).
    - Analyst toolkit Bash pipelines and Python VirusTotal API automation script.
    - Penetration testing lifecycle, OSINT reconnaissance, BCP vs. DRP, and the complete 6-stage Data Lifecycle.
19. **Endpoint, Mobile & Organizational Security**:
    - Host-based firewalls (Windows Defender Firewall, `iptables`/`nftables`/`ufw`), CIS benchmarks, and AppLocker application control.
    - Mobile security architectures: Apple iOS Secure Enclave vs. Android Linux UID isolation & Hardware Keystore; mobile threats (sideloading, rooting/jailbreaking, smishing, IMSI catchers); MDM, MAM, and BYOD enterprise wipe.
    - Wi-Fi enterprise hardening: WPA3-Enterprise (802.1X/EAP-TLS); **The 3-2-1 Backup Rule** (3 copies, 2 media, 1 offsite/immutable); Full vs. Incremental vs. Differential backups; RPO, RTO, MTTR, MTBF, and Hot/Warm/Cold DR sites.
    - Organizational policies: Policy hierarchy (Policies, Standards, Baselines, Guidelines, Procedures), AUP, Clean Desk, vendor risk management, SOC 2 Type I/II, and SBOM.
20. **Introductory Security Tools & Building a Home Practice Lab**: Essential analyst tool directory, VirtualBox/VMware ethical isolated virtual lab setup, and the iron rule of ethics.
21. **Defensive vs. Offensive Roadmaps**: Blue Team vs. Red Team vs. Purple Team, Lockheed Martin Cyber Kill Chain, MITRE ATT&CK matrix, and CompTIA Security+ vs. CEH comparative career analysis.
22. **Master Cybersecurity Glossary of Key Terms**: Exhaustive A–Z technical dictionary containing 187 core terms with definitions and module references.
23. **Foundations Master Review & Practice Knowledge Checks**: 30 comprehensive scenario-based questions with deep technical rationales.

---

### 🛡️ Track 01: CompTIA Security+ (SY0-801)
*File location*: [`01-CompTIA-Security-Plus/`](./01-CompTIA-Security-Plus/)

Structured strictly according to the official CompTIA SY0-801 examination blueprint:
* **Domain 1: General Security Concepts (16%)**: CIA Triad with enterprise wiki scenario, AAA, Zero Trust (NIST SP 800-207), control taxonomy, change management, and PKI cryptographic lifecycle.
* **Domain 2: Threats, Vulnerabilities, and Attacks (24%)**: Threat actors, vectors, malware indicators, vulnerability scoring (CVSS v3.1), IoCs, and attacks against AI/LLM systems (prompt injection, model inversion).
* **Domain 3: Security Architecture (19%)**: Cloud models, SDN architecture, network micro-segmentation, data protection strategies, high availability, STRIDE threat modeling, and resilience planning.
* **Domain 4: Security Operations (27%)**: System hardening, asset management, vulnerability scanning, alerting & monitoring (`tcpdump`, Wireshark, Suricata, Windows Event IDs 4624/4625/4688/4720/1102), IAM solutions, SOAR automation, Incident Response execution (Phishing & Ransomware playbooks), and digital forensics preservation.
* **Domain 5: Security Program Management & Oversight (14%)**: GRC artifacts, quantitative risk formulas ($ALE = SLE \times ARO$), third-party risk & SBOM, Indian regulatory compliance (**DPDP Act 2023, CERT-In 6-hour reporting mandate, IT Act 2000**) alongside GDPR, HIPAA, PCI DSS, SOX, security audits, and awareness training.
* **Exam Prep Module**: 25 realistic scenario-based exam questions with detailed rationales, acronym directory, and cheat sheets.

---

### ⚔️ Track 02: Certified Ethical Hacker (CEH v13)
*File location*: [`02-Certified-Ethical-Hacker/`](./02-Certified-Ethical-Hacker/)

Engineered around EC-Council's CEH v13 curriculum, covering theoretical concepts and offensive tooling:
* **Modules 01–05: Reconnaissance & Enumeration**: Ethical hacking methodology, legal compliance (CFAA, CMA, and Indian IT Act 2000 Section 43/66/66F), Google Dorking operators, WHOIS/DNS interrogation, active Nmap scanning flags, SNMP/SMB enumeration (`enum4linux-ng`), and vulnerability scanning.
* **Modules 06–10: System Hacking & Network Exploitation**: Password cracking (Hydra, John the Ripper), Linux/Windows privilege escalation, malware analysis, network sniffing (`tcpdump` BPF filters, `arpspoof`, Wireshark), social engineering tactics, and DoS/DDoS attack vectors.
* **Modules 11–15: Web & Application Penetration Testing**: Session hijacking, IDS/firewall evasion (packet fragmentation, Suricata signature evasion, modern EDR process-tree detection, LOLBins), web server hacking, OWASP Top 10 web vulnerabilities, and manual & automated SQL injection (`sqlmap`).
* **Modules 16–20: Wireless, Mobile, Cloud & Cryptography**: Wi-Fi cracking (Aircrack-ng suite, WPA2 4-way handshake capture), mobile hacking (Android APK decompilation with `apktool`/`jadx`, Frida SSL pinning bypass, Apple Secure Enclave vs. Android Keystore, MDM/MAM containerization), IoT/OT security, cloud hacking (SDN attack vectors, AWS IAM privilege escalation), and cryptanalysis.
* **v13 Special Addition**: AI-driven offensive security, LLM red teaming, and adversarial prompt injection.
* **Exam Prep Module**: Practical tool command flags master table, 25 realistic CEH scenario questions, and ethical conduct guidelines.

---

## 🚀 Git Initialization & GitHub Upload Guide

Follow these simple steps in your terminal or PowerShell to initialize Git and upload this repository to your GitHub account:

### Step 1: Open PowerShell in this Directory
```powershell
cd c:\Users\LENOVO\OneDrive\Desktop\Cybersecurity-Study-Notes
```

### Step 2: Initialize Git Repository
```powershell
git init
```

### Step 3: Stage and Commit All Files
```powershell
git add .
git commit -m "feat: initial commit with cybersecurity foundations, comptia security+, and ceh v13 master guides"
```

### Step 4: Create a New Repository on GitHub
1. Go to [GitHub.com](https://github.com/new).
2. Name your repository (e.g., `Cybersecurity-Study-Notes` or `Cybersecurity-Master-Roadmap`).
3. Set visibility to **Public** or **Private** (do *not* initialize with a README since you already have this one).
4. Click **Create repository**.

### Step 5: Link Remote and Push to GitHub
```powershell
# Set default branch to main
git branch -M main

# Add your GitHub repository URL (replace with your actual GitHub username and repo name)
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/Cybersecurity-Study-Notes.git

# Push all files to GitHub
git push -u origin main
```

---

## 📖 Recommended Study Paths

```text
[Beginner / Career Switcher]
   │
   ▼
Track 00: Cybersecurity Foundations ───► Hands-on Practice Labs (Module 20)
   │
   ▼
Track 01: CompTIA Security+ (SY0-801) ──► Pass Security+ Certification
   │
   ▼
Track 02: Certified Ethical Hacker (CEH v13) ──► Penetration Testing & Red Team Operations
```

---

## 📄 License & Attribution

This study resource repository is distributed under the **MIT License**. Created for cybersecurity students, ethical hackers, and defensive analysts worldwide. Feel free to star ⭐️, fork, and use these notes for your personal studies or organizational training programs.
