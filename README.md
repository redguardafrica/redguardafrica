
# 🛡️ Redguard Africa — Cybersecurity Resource Hub

**Your community-curated roadmap from curious beginner to industry-ready professional.**

[![Maintained by Community](https://img.shields.io/badge/Maintained%20by-Redguard%20Africa-red?style=flat-square)](https://github.com/redguardafrica)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-blue?style=flat-square)](https://github.com/redguardafrica/resources/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

</div>

---

## 👋 Welcome to Redguard Africa

This repository is the **central knowledge base** for the Redguard Africa cybersecurity community — built by practitioners, curated for the next generation of African cyber defenders and attackers. Whether you're a student picking up your first Linux command or a transitioning IT professional eyeing a SOC role, this index meets you where you are.

Cybersecurity is not a single destination. It is a **constellation of disciplines** — and this repository maps all of them. Every resource listed here has been hand-picked for its quality, accessibility, and proven track record of producing real-world skill.

> 💬 *"The best time to start was yesterday. The second best time is now. Pick a domain, pick a resource, and go deep."*
> — Redguard Africa Community Ethos

---

## 🗺️ How to Use This Repository

| Your Profile | Recommended Approach |
|---|---|
| 🟢 **Absolute Beginner** | Start at **Domain 1** (Fundamentals). Work through it linearly before touching anything else. |
| 🟡 **IT Professional Transitioning** | Skim Domain 1 to fill gaps, then go deep in whichever specialization (D2, D3, or D4) aligns with your target role. |
| 🔵 **Student with Some Experience** | Use this as a pick-and-choose menu. Jump between domains as your curiosity leads. |
| 🔴 **Preparing for Certifications** | Use the cert-specific resources tagged within each domain to guide your prep. |

> 💡 **Pro Tip:** Don't consume passively. For every tutorial you watch, spend **twice** the time in a lab (TryHackMe, HackTheBox, or your own homelab). Watching is learning. Doing is mastery. [Bonus roadmap](https://roadmap.sh/cyber-security)

---

## 📂 Repository Structure

```
redguard-africa/resources
│
├── Domain 1 — Cybersecurity Fundamentals (The Launchpad)
├── Domain 2 — Defensive Security & SOC Operations
├── Domain 3 — Offensive Security & Ethical Hacking
├── Domain 4 — Digital Forensics & Incident Response (DFIR)
└── Community & Contribution Guide
```

---

<br>

## 🚀 Domain 1: Cybersecurity Fundamentals
### *The Launchpad — Core Networking, OS Administration & Security Basics*

> 🎯 **Goal:** Build an unshakeable foundation. Every elite penetration tester, SOC analyst, and forensic investigator started here. Don't skip this.

This domain covers the bedrock knowledge every cybersecurity professional must kown: **how networks communicate, how operating systems work under the hood, and what the core security principles actually mean in practice.** Without this, everything downstream is fragile.

**Key topics covered:** TCP/IP, DNS, HTTP/S, OSI Model, Linux CLI, Windows Internals, Active Directory basics, CompTIA Security+ & Network+ concepts.

---

### 🌐 Networking Foundations

- **[NetworkChuck](https://www.youtube.com/watch?v=S7MNX_UD7vY&list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P)** — *Skill Level:* Beginner | The most energetic networking teacher on YouTube; his free CCNA course and networking fundamentals series make subnetting, VLANs, and routing instantly click for complete beginners.

- **[Professor Messer — CompTIA Network+ Course](https://www.youtube.com/playlist?list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8)** — *Skill Level:* Beginner | The gold standard free CompTIA Network+ prep course; methodical, thorough, and fully aligned to the exam objectives — use this to pass N+ or simply to master networking theory.

- **[PowerCert Animated Videos](https://www.youtube.com/@PowerCertAnimatedVideos)** — *Skill Level:* Beginner | Beautifully animated explanations of networking concepts (DNS, DHCP, VPNs, firewalls) that make abstract protocols visually intuitive and permanently memorable.

- **[David Bombal](https://www.youtube.com/@davidbombal)** — *Skill Level:* Beginner–Intermediate | Covers practical networking with Cisco Packet Tracer, Python automation, and ethical hacking fundamentals; ideal for learners who want theory immediately backed by hands-on labs.

---

### 🔐 Security Fundamentals & Certifications

- **[Professor Messer — CompTIA Security+ Course (SY0-701)](https://www.youtube.com/playlist?list=PLG49S3nxzAnl4QDVqK-hOnoqcSKEIDDuv)** — *Skill Level:* Beginner | The definitive free Security+ video course; covers every exam domain from threats and vulnerabilities to cryptography and identity management — the single best starting point for security fundamentals.
  
- **[Simply Cyber — Gerald Auger](https://www.youtube.com/@SimplyCyber)** — *Skill Level:* Beginner–Intermediate | Daily cybersecurity career content, GRC fundamentals, and mindset coaching; uniquely valuable for understanding the *business* of cybersecurity and what hiring managers actually want.

- **[The Cyber Mentor — Practical Ethical Hacking Prerequisites](https://www.youtube.com/watch?v=3FNYvj2U0HM)** — *Skill Level:* Beginner | Heath Adams' free 15-hour course covering networking, Linux, Python, and hacking foundations; the perfect bridge between "complete beginner" and "ready for offensive security."

---

### 🐧 Linux & Windows Operating Systems

- **[NetworkChuck — Linux for Hackers](https://www.youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL)** — *Skill Level:* Beginner | A fast-paced, hacker-focused Linux series that teaches the terminal commands, file system navigation, and scripting skills every cybersecurity professional uses daily.

- **[HackerSploit — Linux Essentials for Ethical Hackers](https://www.youtube.com/playlist?list=PLBf0hzazHTGMh2fe2MFf3lCgk0rKmS2by)** — *Skill Level:* Beginner | Structured Linux series from a security-first perspective; covers everything from basic commands to shell scripting and service hardening.

- **[John Hammond — Windows Privilege Escalation Techniques](https://www.youtube.com/@_JohnHammond)** — *Skill Level:* Intermediate | Deep dives into Windows internals, registry abuse, service misconfigurations, and Active Directory basics; essential watching for anyone building a security career on Windows-dominated enterprise networks.

- **[TCM Security — Practical Ethical Hacking (Windows AD Section)](https://www.youtube.com/watch?v=VXxH4n684HE)** — *Skill Level:* Intermediate | Hands-on walkthrough of Active Directory attacks and defenses; teaches you how Windows enterprise environments are structured — and how they break.

---

<br>

## 🛡️ Domain 2: Defensive Security & Security Operations (SOC)
### *Blue Teaming, Threat Detection & Incident Response*

> 🎯 **Goal:** Become the person organizations trust to detect, investigate, and contain threats before they become catastrophes.

The Security Operations Center (SOC) is the heartbeat of enterprise defense. This domain builds the skills for **Tier 1, 2, and 3 SOC roles** — log analysis, SIEM tuning, traffic analysis, threat intelligence, and incident response workflows.

**Key topics covered:** SIEM (Splunk, Microsoft Sentinel, Elastic), Wireshark, log analysis, intrusion detection, threat intelligence, SOC workflows, and homelab design.

---

### 📡 SIEM, Log Analysis & SOC Workflows

- **[MyDFIR](https://www.youtube.com/@MyDFIR)** — *Skill Level:* Beginner–Intermediate | The most practical SOC and DFIR channel available for free; renowned for step-by-step SOC homelab build guides (Elastic SIEM, Splunk, Microsoft Sentinel) that give you actual hands-on experience hiring managers respect.

- **[John Hammond — SOC & Malware Analysis Playlist](https://www.youtube.com/playlist?list=PL1H1sBF1VAKVoU6Q2u7BBGPsnkn-rajlp)** — *Skill Level:* Intermediate | Real-world CTF and malware analysis walkthroughs that simulate actual SOC alert triage; exceptionally good at building the investigative mindset required for Tier 2+ analyst work.

- **[Simply Cyber — SOC Analyst Career Path](https://www.youtube.com/playlist?list=PL4Q-ttyNIRAomhB6uWAob2RWMwCNlQ6UY)** — *Skill Level:* Beginner | Gerald Auger's curated guidance on breaking into the SOC field, understanding GRC frameworks (NIST, ISO 27001), and positioning yourself for your first security operations role.

- **[Cybersecurity Meg](https://www.youtube.com/@CybersecurityMeg)** — *Skill Level:* Beginner | Focuses on the human side of SOC careers — resume building, interview preparation, and day-in-the-life content for aspiring analysts; excellent companion to technical learning.

- **[Day Cyberwox](https://www.youtube.com/@DayCyberwox)** — *Skill Level:* Beginner–Intermediate | SOC and cloud security homelab tutorials with a strong focus on Azure Sentinel and Microsoft Defender for Endpoint; highly relevant for learners targeting Microsoft-stack enterprise environments.

---

### 🔭 Traffic Analysis & Network Monitoring

- **[Chris Greer — Wireshark Master Class](https://www.youtube.com/playlist?list=PLW8bTPfXNGdC5Co0VnBK1yVzAwSSphzpJ)** — *Skill Level:* Beginner–Intermediate | The definitive free Wireshark resource on YouTube; teaches packet capture, protocol dissection, and detecting anomalous traffic patterns that are core to both SOC analysis and network forensics.

- **[TCM Security — Practical Network Analysis](https://www.youtube.com/@TCMSecurityAcademy)** — *Skill Level:* Intermediate | Covers Wireshark, Zeek, and Suricata in attacker-aware defensive contexts; teaches analysts to read traffic not just technically, but strategically — understanding what adversaries are trying to hide.

- **[HackerSploit — Snort IDS/IPS Tutorial](https://www.youtube.com/watch?v=Gh0sweT-G30&t=8s)** — *Skill Level:* Intermediate | Hands-on configuration of Snort rules for intrusion detection; directly applicable to SOC homelab setups and real-world network monitoring deployments.

---

### 🧪 Homelab Building

- **[MyDFIR — SOC Homelab Series](https://www.youtube.com/playlist?list=PLG6KGSNK4PuBWmX9NykU0wnWamjxdKhDJ)** — *Skill Level:* Beginner–Intermediate | A complete guided series for building a functional SOC lab at home using free tools; covers Elastic SIEM deployment, agent installation, and creating your first detection rules — the #1 recommended homelab guide in the community.

- **[Defensive Security Homelab](https://www.youtube.com/playlist?list=PL3ljjyal211AbTqlxSo6CGBiVqsXw8wrp)** — *Skill Level:* Intermediate | Detailed guides for building Purple Team labs with both attacker simulation and detection logging; ideal for analysts wanting to understand both sides of the incident response equation.

---

<br>

## ⚔️ Domain 3: Offensive Security & Ethical Hacking
### *Penetration Testing, Vulnerability Assessment & Red Teaming*

> 🎯 **Goal:** Learn to think, move, and operate like an adversary — so you can build defenses that actually hold.

Offensive security is the art of **authorized adversarial simulation.** This domain teaches the methodologies, tools, and mindset of penetration testers and red teamers — from initial reconnaissance through full domain compromise.

**Key topics covered:** Hacking methodology (PTES, OWASP), web application exploitation, network exploitation, privilege escalation, Active Directory attacks, post-exploitation, and CTF techniques.

---

### 🔥 Core Penetration Testing

- **[The Cyber Mentor (Heath Adams) — Practical Ethical Hacking Full Course](https://www.youtube.com/watch?v=3FNYvj2U0HM)** — *Skill Level:* Beginner–Intermediate | The most comprehensive free ethical hacking course on YouTube; a 15-hour zero-to-hero journey covering networking, Linux, Python, web app hacking, and Active Directory exploitation — the definitive starting point for aspiring penetration testers.

- **[TCM Security Academy](https://www.youtube.com/@TCMSecurityAcademy)** — *Skill Level:* Intermediate | The official channel of TCM Security with free content on OSCP prep, Active Directory attacks, red teaming concepts, and hacking methodology; the content quality rivals paid platforms.

- **[HackerSploit — Ethical Hacking Course](https://www.youtube.com/playlist?list=PLBf0hzazHTGOepimcP15eS6Y-aR4m6ql3)** — *Skill Level:* Beginner–Intermediate | A structured, module-by-module ethical hacking course covering reconnaissance, scanning, exploitation, and post-exploitation using Kali Linux; excellent pacing for self-study learners.

- **[David Bombal — Ethical Hacking Playlist](https://www.youtube.com/playlist?list=PLhfrWIlLOoKMe1Ue0IdeULQvEgCgQ3a1B)** — *Skill Level:* Beginner–Intermediate | Practical hacking demonstrations paired with essential theory on attack tools, network exploitation, and security testing methodologies.

---

### 🏹 Active Directory & Advanced Exploitation

- **[Active Directory Attacks](https://www.youtube.com/playlist?list=PLM1644RoigJvm0L7RcK-64aVTp1vZkDv5)** — *Skill Level:* Intermediate | Heath Adams' legendary AD attack course covering LLMNR poisoning, Pass-the-Hash, Kerberoasting, DCSync, and lateral movement — compulsory viewing for anyone targeting enterprise penetration testing roles.

- **[TCM Security — Movement, Pivoting & Persistence](https://www.youtube.com/watch?v=_8xJaaQlpBo)** — *Skill Level:* Advanced | In-depth coverage of post-exploitation tradecraft: lateral movement techniques, credential dumping, pivoting through network segments, and establishing persistent access — essential for OSCP and red team certifications.

---

### 🚩 CTF Walkthroughs & Skill Building

- **[IppSec — Hack The Box Walkthroughs](https://www.youtube.com/@ippsec)** — *Skill Level:* Intermediate–Advanced | The undisputed king of HTB walkthroughs; IppSec's methodical, deeply explained approach to every machine teaches not just *what* to do but *why* — indispensable for OSCP preparation and building real hacking intuition.

- **[NahamSec](https://www.youtube.com/@NahamSec)** — *Skill Level:* Intermediate | Premier resource for web application hacking, bug bounty hunting, and live hacking events; Ben Sadeghipour's content bridges the gap between CTF skills and real-world bug bounty earning.

- **[John Hammond — CTF Walkthroughs & Malware Analysis](https://www.youtube.com/@_JohnHammond)** — *Skill Level:* Intermediate | Engaging, educational CTF solutions covering web exploitation, reverse engineering, cryptography, and forensics challenges; John's enthusiasm and clarity make complex techniques genuinely approachable.

- **[LiveOverflow](https://www.youtube.com/@LiveOverflow)** — *Skill Level:* Intermediate–Advanced | Deep technical content on binary exploitation, memory corruption, CTF methodology, and security research; for learners ready to move beyond surface-level hacking into the underlying mechanics of vulnerabilities.

---

### 🌐 Web Application Security

- **[PortSwigger Web Security Academy — Official YouTube](https://portswigger.net/web-security)** — *Skill Level:* Beginner–Advanced | Official companion channel to the free PortSwigger Web Security Academy; covers OWASP Top 10 vulnerabilities (SQLi, XSS, SSRF, XXE, IDOR) with lab-based learning — the industry standard for web app security education.

- **[STÖK](https://www.youtube.com/@STOKfredrik)** — *Skill Level:* Intermediate | Bug bounty hunting culture, recon methodology, and web hacking techniques from a professional hacker; combines technical depth with inspiration for building a career in offensive security.

---

<br>

## 🔬 Domain 4: Digital Forensics & Incident Response (DFIR)
### *Artifact Analysis, Memory/Disk Forensics & Threat Hunting*

> 🎯 **Goal:** Become the investigator who reconstructs exactly what happened, how attackers moved, and what evidence they left behind — then eradicates them.

DFIR sits at the intersection of detective work and deep technical expertise. This domain builds the skills to **respond to live incidents, analyze compromised systems, hunt for threats, and produce forensic-quality evidence** that supports both remediation and legal proceedings.

**Key topics covered:** Memory forensics (Volatility), disk imaging (FTK Imager, Autopsy), Windows artifact analysis, malware analysis (static and dynamic), threat hunting, and incident response frameworks.

---

### 🧠 Memory & Disk Forensics

- **[13Cubed](https://www.youtube.com/@13Cubed)** — *Skill Level:* Intermediate–Advanced | **The single most important DFIR channel on YouTube.** Richard Davis delivers forensic-grade content on Windows memory analysis, Volatility framework, disk artifacts, and threat hunting with a precision and depth that rivals professional training courses — mandatory for any serious DFIR practitioner.

- **[13Cubed — Introduction to Memory Forensics with Volatility 3](https://www.youtube.com/watch?v=Uk3DEgY5Ue8)** — *Skill Level:* Intermediate | A focused, hands-on walkthrough of memory acquisition, Volatility plugin usage, and extracting attacker artifacts from RAM; the best single video to watch before attempting memory forensics for the first time.

- **[MyDFIR — Disk Forensics & Incident Response Series](https://www.youtube.com/@MyDFIR)** — *Skill Level:* Beginner–Intermediate | Practical walkthroughs of disk imaging with FTK Imager, artifact carving, and building complete IR timelines; builds the foundational workflow every junior DFIR analyst needs to internalize.

- **[HackerSploit — Digital Forensics with Autopsy](https://www.youtube.com/watch?v=o6boK9dG-Lc)** — *Skill Level:* Beginner–Intermediate | Step-by-step forensic investigation using Autopsy and the Sleuth Kit; covers disk image mounting, file recovery, browser artifact analysis, and evidence reporting — the complete beginner's introduction to disk forensics.

---

### 🦠 Malware Analysis & Reverse Engineering

- **[John Hammond — Malware Analysis Playlist](https://www.youtube.com/watch?v=fV-pTu5T59M&list=PL1H1sBF1VAKWMn_3QPddayIypbbITTGZv)** — *Skill Level:* Intermediate | Hands-on malware triage, static and dynamic analysis, sandbox usage, and YARA rule writing delivered in John's trademark clear and engaging style; excellent for analysts wanting to level up from alert triage to actual malware investigation.

- **[OALabs](https://www.youtube.com/@OALabs)** — *Skill Level:* Intermediate–Advanced | Professional-grade malware analysis and reverse engineering content covering unpacking, deobfuscation, C2 infrastructure analysis, and IDA Pro/Ghidra techniques; trusted by industry malware analysts worldwide.

- **[MalwareTech](https://www.youtube.com/@MalwareTechBlog)** — *Skill Level:* Advanced | Deep technical content from a seasoned malware researcher covering reverse engineering, vulnerability analysis, and threat intelligence; content for analysts ready to go beyond tools into the underlying assembly and OS internals.

- **[HackerSploit — Reverse Engineering & Malware Analysis](https://www.youtube.com/watch?v=uHhKkLwT4Mk&list=PLBf0hzazHTGMSlOI2HZGc08ePwut6A2Io)** — *Skill Level:* Intermediate | Structured introduction to static analysis with pestudio and Ghidra, and dynamic analysis with x64dbg and Cuckoo Sandbox; builds the complete malware analyst toolkit methodically.

---

### 🕵️ Threat Hunting & Incident Response

- **[13Cubed — Windows Forensics & Threat Hunting](https://www.youtube.com/playlist?list=PLlv3b9B16ZadqDQH0lTRO4kqn2P1g9Mve)** — *Skill Level:* Intermediate–Advanced | Richard Davis' comprehensive series on hunting adversaries using Windows event logs, Sysmon, registry artifacts, prefetch, and AmCache analysis — the essential curriculum for any threat hunter or IR responder operating in Windows environments.

- **[Blue Team Labs Online — Official YouTube](https://www.youtube.com/playlist?list=PLqyUgadpThTIK7yJqXuyzA9GGw3YrtOL0)** — *Skill Level:* Intermediate | Walkthrough-style video content accompanying Blue Team Labs Online's free investigative challenges; teaches structured incident investigation methodology using real log data, PCAP files, and memory images.

- **[The DFIR Report](https://thedfirreport.com)** — *Skill Level:* Advanced | Not a YouTube channel — this is the **community's most trusted published resource** for real-world incident response case studies; every report documents a complete attack chain from initial access to ransomware deployment with full IOC lists and detection opportunities.

> 🔎 **Field Note:** The DFIR Report is essential reading. Pick one published case study per week, map it to the MITRE ATT&CK framework, and build a detection rule for it. This single habit separates competent analysts from exceptional ones.

---

<br>

## 🧰 Essential Platforms & Practice Labs

> *Learning without practice is theory. Practice without structure is chaos. Use these platforms to apply every concept from the domains above.*

| Platform | Focus | Cost | Link |
|---|---|---|---|
| **TryHackMe** | Guided learning paths (SOC, Pentesting, DFIR) | Free + Paid | [tryhackme.com](https://tryhackme.com) |
| **Hack The Box** | Intermediate–Advanced machine challenges | Free + Paid | [hackthebox.com](https://www.hackthebox.com) |
| **Blue Team Labs Online** | Defensive security investigations | Free + Paid | [blueteamlabs.online](https://blueteamlabs.online) |
| **PortSwigger Web Academy** | Web application security labs | **Free** | [portswigger.net/web-security](https://portswigger.net/web-security) |
| **DFIR.training** | Curated DFIR tools and resources | **Free** | [dfir.training](https://www.dfir.training) |
| **Cybrary** | Structured cybersecurity courses | Free + Paid | [cybrary.it](https://www.cybrary.it) |
| **LetsDefend** | SOC analyst simulation platform | Free + Paid | [letsdefend.io](https://letsdefend.io) |
| **MITRE ATT&CK** | Adversary tactics & techniques framework | **Free** | [attack.mitre.org](https://attack.mitre.org) |

---

<br>

## 🤝 Community & Contribution Guide

This repository is **community-owned.** Every resource here was added by someone who found it valuable and decided to give back. You can do the same.

### How to Contribute

1. **Fork** this repository to your GitHub account.
2. **Create a new branch** with a descriptive name:
   ```bash
   git checkout -b add/domain2-siem-resource
   ```
3. **Add your resource** following the exact format used throughout this document:
   ```
   - **[Resource Name/Channel]** (URL) — *Skill Level:* [Beginner/Intermediate/Advanced] | 
     One sentence on what learners will gain and why it matters.
   ```
4. **Open a Pull Request** with a brief description of what you're adding and why it belongs here.
5. A community maintainer will review and merge within **72 hours**.

### Contribution Standards

- ✅ Resource must be **free** or have a substantial free tier
- ✅ Content must be **currently active and accessible**
- ✅ Must clearly fit one of the four defined domains
- ✅ No duplicate entries — search before adding
- ❌ No paid course advertising or promotional content
- ❌ No resources behind paywalls without a meaningful free option

### Found a Broken Link?

Open an **Issue** with the title format: `[BROKEN LINK] Resource Name — Domain X` and we'll fix it within 48 hours.

---

<br>

<div align="center">

## 🌍 Built for Africa. Shared with the World.

*Redguard Africa exists to ensure that world-class cybersecurity education is accessible to every aspiring professional on the continent — regardless of geography or financial circumstance.*

**The continent needs defenders. Be one.**

---

[![Join Our Community](https://img.shields.io/badge/Join-Redguard%20Africa-red?style=for-the-badge)](https://github.com/redguardafrica)
[![Follow on Twitter](https://img.shields.io/badge/Follow-%40RedguardAfrica-1DA1F2?style=for-the-badge&logo=twitter)](https://x.com/redguardafrica)
[![Star This Repo](https://img.shields.io/badge/⭐%20Star-This%20Repository-yellow?style=for-the-badge)](https://github.com/redguardafrica/resources)

---



</div>