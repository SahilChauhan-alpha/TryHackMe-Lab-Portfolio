# ⚔️ Offensive Pentesting & Jr. Penetration Tester Portfolio
> A curated compilation of simulated engagements, advanced exploitation methodologies, and technical walkthroughs from TryHackMe labs.

---

## ⚡ Technical Skill Matrix

```text
  [ Reconnaissance ] ────► [ Vulnerability Analysis ] ────► [ Exploitation ] ────► [ Privilege Escalation ]
  └─ Nmap, Gobuster,       └─ Searchsploit, Nessus,         └─ Metasploit, Netcat,  └─ SUID/SGID, Capabilties,
     Enum4linux, DNS Tools    OWASP ZAP, Manual Review         Reverse Shells, Payload   Automated Scripts (LinPeas)
     Domain,Core Toolset,Competency Areas

Information Gathering,Nmap Gobuster Nikto WhatWeb,"Active/Passive Recon, Subdomain Brute-forcing, OSINT"
Web Exploitation,Burp Suite SQLmap Hydra,"OWASP Top 10, Injection Flaws, Broken Authentication"
System Exploitation,Metasploit Netcat Msfvenom,"Shell Stabilization, Payload Generation, Buffer Overflows"
Privilege Escalation,LinPEAS WinPEAS GTFOBins,"SUID Abuse, Kernel Exploits, Misconfigured Cron Jobs"

📂 Active Learning Tracks & Showcases
🛠️ 1. Information Gathering & Reconnaissance
🌐 Active Directory Enumeration - Documenting structural domain mapping, Kerberoasting attacks, and BloodHound network visualization.

🔍 Advanced Nmap Strategies - Utilizing tailored script scans (-sC) and version detections (-sV) to uncover vulnerable legacy infrastructure components.

💀 2. Weaponization & Initial Access
🌐 Web Application Exploitation - Step-by-step walkthroughs bypassing client-side validation to execute Remote Code Execution (RCE) via malicious file uploads.

📦 Custom Payload Generation - Using msfvenom to compile staged vs. unstaged reverse shells adapted for specific target operating systems.

📈 3. Privilege Escalation & Post-Exploitation
🐧 Linux Privilege Escalation - Practical exploitation tracking of weak file permissions, SUID binaries, and abusing sudo rights via GTFOBins.

🪟 Windows Privilege Escalation - Identifying unquoted service paths, token impersonation exploits, and vulnerable registry keys.

🧠 Methodology Mindset
Every lab included in this portfolio is broken down into four distinct analytical phases to showcase real-world analytical skills:

1. Scope & Enumeration: Defining the target footprint, active services, and potential attack vectors.

2. Vulnerability Assessment: Mapping discovered services to known CVEs or structural logical flaws.

3. Controlled Exploitation: Gaining a footfold while documenting precise commands, payload adjustments, and stabilization.

4. Remediation Advisory: Writing professional defensive recommendations (e.g., implementing strict RBAC, applying patches, or setting firewalls inline) to close the attack surface.

🎯 TryHackMe Badges & Certifications
Profile Link: [https://tryhackme.com/p/GreyROse]