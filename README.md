<div align="center">

```
██████╗ ███████╗███╗   ██╗████████╗███████╗███████╗████████╗██╗███╗   ██╗ ██████╗ 
██╔══██╗██╔════╝████╗  ██║╚══██╔══╝██╔════╝██╔════╝╚══██╔══╝██║████╗  ██║██╔════╝ 
██████╔╝█████╗  ██╔██╗ ██║   ██║   █████╗  ███████╗   ██║   ██║██╔██╗ ██║██║  ███╗
██╔═══╝ ██╔══╝  ██║╚██╗██║   ██║   ██╔══╝  ╚════██║   ██║   ██║██║╚██╗██║██║   ██║
██║     ███████╗██║ ╚████║   ██║   ███████╗███████║   ██║   ██║██║ ╚████║╚██████╔╝
╚═╝     ╚══════╝╚═╝  ╚═══╝   ╚═╝   ╚══════╝╚══════╝   ╚═╝   ╚═╝╚═╝  ╚═══╝ ╚═════╝ 
```

# 🛡️ Advanced Red Teaming Methodology

### *A Comprehensive Penetration Testing Reference & Interactive Knowledge Base*

[![Live Site](https://img.shields.io/badge/🌐_Live_Site-pentesting--methodology.netlify.app-00D4FF?style=for-the-badge)](https://pentesting-methodology.netlify.app/)
[![Netlify Status](https://img.shields.io/netlify/your-site-id?style=for-the-badge&logo=netlify&label=Netlify)](https://pentesting-methodology.netlify.app/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge&logo=github)](https://github.com/rohit-1006/pentesting-methodology/pulls)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Netlify](https://img.shields.io/badge/Hosted_on-Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)](https://netlify.com)

---

> **⚠️ LEGAL DISCLAIMER:** This resource is intended strictly for **authorized security testing**, **ethical hacking education**, and **bug bounty research**. Always obtain written permission before testing any system. Unauthorized access is illegal and unethical.

---

</div>

## 📖 Table of Contents

- [About The Project](#-about-the-project)
- [Live Demo](#-live-demo)
- [Methodology Phases](#-methodology-phases)
- [Topics Covered](#-topics-covered)
- [Who Is This For](#-who-is-this-for)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Tools Referenced](#-tools-referenced)
- [Contributing](#-contributing)
- [Author](#-author)
- [Connect With Me](#-connect-with-me)
- [License](#-license)

---

## 🎯 About The Project

**Penetration Testing // Advanced Red Teaming Methodology** is a professional, interactive web-based reference guide covering the complete lifecycle of a penetration test — from initial reconnaissance to final reporting. Built for security professionals, bug bounty hunters, CTF players, and aspiring ethical hackers, this resource consolidates industry-standard techniques, commands, and workflows into a structured, accessible format.

This project aims to serve as:

- 📚 A **quick-reference cheatsheet** for active engagements
- 🧠 A **learning resource** for those breaking into offensive security
- 🔧 A **methodology framework** aligned with real-world red team workflows
- 🏹 A **bug bounty hunting companion** for structured vulnerability hunting

### ✨ Key Highlights

| Feature | Description |
|---|---|
| 🌐 **Interactive UI** | Clean, hacker-themed interface designed for fast navigation |
| 📋 **Phase-Based Structure** | Organized by the standard pentest lifecycle |
| ⚡ **Command References** | Ready-to-use commands for popular tools |
| 🔍 **Vulnerability Coverage** | OWASP Top 10 and beyond |
| 🎯 **Bug Bounty Focused** | Techniques tailored for real-world program hunting |
| 📱 **Responsive Design** | Accessible on desktop and mobile |

---

## 🌐 Live Demo

🔗 **[https://pentesting-methodology.netlify.app/](https://pentesting-methodology.netlify.app/)**

The site is live and continuously updated. No installation required — open it in any browser during your engagements.

---

## 🔄 Methodology Phases

This project follows the industry-standard penetration testing lifecycle:

```
┌─────────────────────────────────────────────────────────────────┐
│                  PENETRATION TESTING LIFECYCLE                  │
├──────────────┬──────────────────────────────────────────────────┤
│  Phase 1     │  📝 RECONNAISSANCE                               │
│              │  Passive & Active Information Gathering           │
│              │  OSINT, DNS Enumeration, Subdomain Discovery      │
├──────────────┼──────────────────────────────────────────────────┤
│  Phase 2     │  🔍 SCANNING & ENUMERATION                        │
│              │  Port Scanning, Service Detection, Banner Grab    │
│              │  Directory Bruteforcing, Technology Fingerprinting│
├──────────────┼──────────────────────────────────────────────────┤
│  Phase 3     │  💥 EXPLOITATION                                  │
│              │  Vulnerability Exploitation, Payload Delivery      │
│              │  Web App Attacks, Network Attacks                 │
├──────────────┼──────────────────────────────────────────────────┤
│  Phase 4     │  🏴 POST-EXPLOITATION                             │
│              │  Privilege Escalation, Lateral Movement           │
│              │  Persistence, Data Exfiltration                   │
├──────────────┼──────────────────────────────────────────────────┤
│  Phase 5     │  📊 REPORTING                                     │
│              │  Findings Documentation, Risk Rating              │
│              │  Remediation Recommendations                      │
└──────────────┴──────────────────────────────────────────────────┘
```

---

## 📚 Topics Covered

### 🌐 Web Application Security
- SQL Injection (Error-based, Blind, Time-based, Out-of-band)
- Cross-Site Scripting (Reflected, Stored, DOM-based)
- SSRF — Server-Side Request Forgery
- IDOR — Insecure Direct Object References
- Authentication & Session Management Flaws
- Business Logic Vulnerabilities
- XXE — XML External Entity Injection
- SSTI — Server-Side Template Injection
- Broken Access Control
- File Upload Vulnerabilities
- API Security Testing

### 🔎 Reconnaissance & OSINT
- Passive Reconnaissance Techniques
- Google Dorking / Advanced Search Operators
- Subdomain Enumeration & Takeover
- DNS Reconnaissance
- Email Harvesting
- Shodan / Censys / FOFA Usage
- GitHub Dorking for Sensitive Data

### 🛡️ Network Penetration Testing
- Network Scanning & Host Discovery
- Service and Version Enumeration
- SMB / FTP / SSH Exploitation
- Active Directory Attacks (Pass-the-Hash, Kerberoasting)
- Man-in-the-Middle (MitM) Attacks
- Firewall Evasion Techniques

### ⬆️ Privilege Escalation
- Linux PrivEsc (SUID, Cron Jobs, Misconfigurations)
- Windows PrivEsc (Token Impersonation, Registry, Services)
- Automated Enumeration with LinPEAS / WinPEAS

### 🏆 Bug Bounty Hunting
- Program Selection & Scope Analysis
- High-Impact Vulnerability Chains
- Reporting Best Practices
- P1/P2 Finding Strategies
- Bypassing WAF & Filters

---

## 👥 Who Is This For

| Audience | Use Case |
|---|---|
| 🎓 **Students & Beginners** | Structured learning path for offensive security |
| 🐛 **Bug Bounty Hunters** | Quick-reference during active hunting |
| 🔴 **Red Teamers** | Methodology checklist during engagements |
| 🏆 **CTF Players** | Technique reference for challenges |
| 🔐 **Security Researchers** | Consolidated knowledge base |
| 💼 **Security Professionals** | Client engagement methodology guide |

---

## 🚀 Getting Started

### Option 1: Use the Live Site (Recommended)
Simply visit **[pentesting-methodology.netlify.app](https://pentesting-methodology.netlify.app/)** — no setup needed.

### Option 2: Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/rohit-1006/pentesting-methodology.git

# 2. Navigate to the project directory
cd pentesting-methodology

# 3. Open in browser
# Option A: Direct open
open index.html

# Option B: Using Python HTTP Server
python3 -m http.server 8080
# Then visit http://localhost:8080

# Option C: Using VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge, Brave)
- No additional dependencies required

---

## 📁 Project Structure

```
pentesting-methodology/
│
├── index.html              # Main entry point
├── README.md               # Project documentation
│
├── assets/
│   ├── css/
│   │   ├── style.css       # Main stylesheet (hacker theme)
│   │   └── responsive.css  # Mobile responsiveness
│   ├── js/
│   │   └── main.js         # Navigation & interactivity
│   └── images/
│       └── ...             # Icons and visuals
│
├── sections/
│   ├── recon.html          # Reconnaissance phase
│   ├── scanning.html       # Scanning & enumeration
│   ├── exploitation.html   # Exploitation techniques
│   ├── post-exploit.html   # Post-exploitation
│   └── reporting.html      # Report writing guide
│
└── LICENSE
```

---

## 🛠️ Tools Referenced

This methodology covers usage and commands for the following tools:

**Reconnaissance**

![Amass](https://img.shields.io/badge/Amass-black?style=flat-square)
![Subfinder](https://img.shields.io/badge/Subfinder-blue?style=flat-square)
![theHarvester](https://img.shields.io/badge/theHarvester-orange?style=flat-square)
![Shodan](https://img.shields.io/badge/Shodan-red?style=flat-square)
![Recon-ng](https://img.shields.io/badge/Recon--ng-purple?style=flat-square)

**Scanning & Enumeration**

![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square&logo=nmap&logoColor=white)
![Gobuster](https://img.shields.io/badge/Gobuster-green?style=flat-square)
![Nikto](https://img.shields.io/badge/Nikto-grey?style=flat-square)
![Feroxbuster](https://img.shields.io/badge/Feroxbuster-orange?style=flat-square)
![WPScan](https://img.shields.io/badge/WPScan-blue?style=flat-square)

**Exploitation**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![SQLMap](https://img.shields.io/badge/SQLMap-CC0000?style=flat-square&logoColor=white)
![XSSer](https://img.shields.io/badge/XSSer-yellow?style=flat-square)
![ffuf](https://img.shields.io/badge/ffuf-teal?style=flat-square)

**Post-Exploitation**

![LinPEAS](https://img.shields.io/badge/LinPEAS-orange?style=flat-square)
![WinPEAS](https://img.shields.io/badge/WinPEAS-blue?style=flat-square)
![Mimikatz](https://img.shields.io/badge/Mimikatz-red?style=flat-square)
![BloodHound](https://img.shields.io/badge/BloodHound-purple?style=flat-square)

**Network Analysis**

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![tcpdump](https://img.shields.io/badge/tcpdump-black?style=flat-square)
![Responder](https://img.shields.io/badge/Responder-darkred?style=flat-square)

---

## 🤝 Contributing

Contributions make this resource better for the entire security community. All contributions are welcome!

### How to Contribute

```bash
# 1. Fork the repository
# Click "Fork" on the top right of this page

# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/pentesting-methodology.git

# 3. Create a feature branch
git checkout -b feature/add-technique-name

# 4. Make your changes & commit
git add .
git commit -m "feat: add [technique/tool/section] to [phase]"

# 5. Push and open a Pull Request
git push origin feature/add-technique-name
```

### Contribution Guidelines

- ✅ Add new techniques with working command examples
- ✅ Fix typos, broken links, or outdated information
- ✅ Improve explanations and add context
- ✅ Add new tools with usage examples
- ❌ Do not add illegal or unethical content
- ❌ Do not add content targeting specific organizations

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

---

## 📊 Project Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/rohit-1006/pentesting-methodology?style=social)
![GitHub forks](https://img.shields.io/github/forks/rohit-1006/pentesting-methodology?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/rohit-1006/pentesting-methodology?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/rohit-1006/pentesting-methodology?style=flat-square&color=green)
![GitHub repo size](https://img.shields.io/github/repo-size/rohit-1006/pentesting-methodology?style=flat-square)

</div>

---

## 👨‍💻 Author

<div align="center">

<img src="https://avatars.githubusercontent.com/u/207909852?v=4" width="120" style="border-radius: 50%" alt="Rohit10"/>

### **Rohit10** (rohit-1006)

*Security Researcher · Penetration Tester · Bug Bounty Hunter · CTF Player*

[![GitHub](https://img.shields.io/badge/GitHub-rohit--1006-181717?style=for-the-badge&logo=github)](https://github.com/rohit-1006)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Rohit10-212C42?style=for-the-badge&logo=tryhackme)](https://tryhackme.com/p/Rohit10)
[![HackerOne](https://img.shields.io/badge/HackerOne-Profile-494649?style=for-the-badge&logo=hackerone)](https://hackerone.com)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-Profile-F26822?style=for-the-badge&logo=bugcrowd)](https://bugcrowd.com)

</div>

### 🗂️ Other Projects by Rohit10

| Project | Description | Stars |
|---|---|---|
| [🔧 Ultimate-Security-Tools-Installer](https://github.com/rohit-1006/Ultimate-Security-Tools-Installer) | Automated security tools installation framework | ⭐ |
| [🏹 Bug-Bounty-Hunting-Guide](https://github.com/rohit-1006/Bug-Bounty-Hunting-Guide) | Advanced methodology, commands & techniques | ⭐ |
| [🔭 ReconX](https://github.com/rohit-1006/ReconX) | GUI-based recon framework for bug bounty | ⭐ |
| [🎯 SSRF-Hunter](https://github.com/rohit-1006/SSRF-Hunter) | Comprehensive SSRF detection tool | ⭐ |

---

## 🔗 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rohit-1006)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Rohit10-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Rohit10)

</div>

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Rohit10 (rohit-1006)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## ⚠️ Legal & Ethical Notice

<div align="center">

```
┌─────────────────────────────────────────────────────┐
│                  ⚠️  IMPORTANT                       │
│                                                     │
│  This resource is for EDUCATIONAL purposes only.    │
│                                                     │
│  ✅ Use only on systems you OWN or have             │
│     EXPLICIT WRITTEN PERMISSION to test.            │
│                                                     │
│  ✅ Always operate within the SCOPE defined         │
│     by bug bounty programs.                         │
│                                                     │
│  ❌ Unauthorized access is ILLEGAL under            │
│     the Computer Fraud and Abuse Act (CFAA)         │
│     and equivalent laws worldwide.                  │
│                                                     │
│  The author assumes NO liability for misuse.        │
└─────────────────────────────────────────────────────┘
```

</div>

---

<div align="center">

**⭐ If this resource helped you, consider giving it a star!**

*Built with ❤️ for the security community by [Rohit10](https://github.com/rohit-1006)*

[![Visit Site](https://img.shields.io/badge/🔗_Visit_Live_Site-pentesting--methodology.netlify.app-00D4FF?style=for-the-badge)](https://pentesting-methodology.netlify.app/)

</div>
