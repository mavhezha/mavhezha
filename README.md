# Arnold Mavhezha — Offensive Security Engineer

<div align="center">
  <img src="banner.svg" alt="Arnold Mavhezha — Offensive Security Engineer" />
</div>
<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arnold-mavhezha/)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/arnold_mavhezha)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@arnold_mavhezha)
[![Portfolio](https://img.shields.io/badge/mavhezha.com-64FFDA?style=for-the-badge&logo=firefox&logoColor=black)](https://mavhezha.com)

</div>

---

## About

Offensive security engineer based in New York. 12 years of software development experience, 8 of them in full-stack MERN development, and 4 years of enterprise security operations, spanning API endpoint security, cloud security, and incident response. Currently grinding Active Directory attack chains, Linux privilege escalation, and web application exploitation in preparation for OSCP.

I build things as much as I break them. See Breach The LLM below.

---

## Featured Project: Breach The LLM

**An open source, self-hosted AI red-teaming range.** Attack a fictional bank's fraud-review AI assistant across 7 progressively harder levels, each one a real, calibrated prompt injection technique, not a scripted demo.

[![Website](https://img.shields.io/badge/Website-breachthellm.com-64FFDA?style=for-the-badge)](https://breachthellm.com)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/breachthellm/breachthellm)

- **7 levels, 7 distinct techniques**: direct injection, instruction override, indirect injection (two data sources), tool-use injection, and a hardened capstone that chains everything together
- Every level is mapped to the **OWASP LLM Top 10** and **MITRE ATLAS**, and calibrated live against a real running model (Llama 3.1 8B via Ollama), not assumed to work
- **Context Trace**: a differentiator most red-teaming tools don't have, a real-time view into exactly what the model read and trusted, system prompt, injected content, and user input, side by side
- Fully self-hosted: Docker Compose, local model inference, no data leaves your machine unless you opt into API mode
- MIT licensed, open source, free

---

## HackTheBox

### Windows

| Machine | Difficulty | Key Techniques | Write-up |
|---|---|---|---|
| **Forest** | Easy | RPC null session, AS-REP Roasting, BloodHound, WriteDACL, DCSync | [Read](https://mavhezha.com/blog/htb-forest-writeup) |
| **Sauna** | Easy | Web OSINT, AS-REP Roasting, AutoLogon, DCSync, Pass-the-Hash | [Read](https://mavhezha.com/blog/htb-sauna-writeup) |
| **Active** | Easy | GPP credentials, Kerberoasting, psexec | [Read](https://github.com/mavhezha/oscp-journey/tree/master/htb-writeups/Active) |
| **Support** | Easy | LDAP enum, .NET reverse engineering, GenericAll, RBCD | [Read](https://github.com/mavhezha/oscp-journey/tree/master/htb-writeups/Support) |
| **Timelapse** | Easy | SMB enum, PFX cert auth, PowerShell history, LAPS | [Read](https://github.com/mavhezha/oscp-journey/tree/master/htb-writeups/Timelapse) |
| **Return** | Easy | Printer credential capture, Server Operators, service binary hijack | [Read](https://github.com/mavhezha/oscp-journey/tree/master/htb-writeups/Return) |
| **Heist** | Easy | Cisco password cracking, RID brute force, Firefox memory dump | [Read](https://github.com/mavhezha/oscp-journey/tree/master/htb-writeups/Heist) |
| **Cicada** | Easy | SMB enum, RID cycling, credential reuse, SeBackupPrivilege | [Read](https://github.com/mavhezha/oscp-journey/tree/master/htb-writeups/Cicada) |
| **Access** | Easy | ACCDB credential extraction, saved RDP creds, runas SavedCreds | [Read](https://mavhezha.com/blog/htb-access-writeup) |

### Linux

| Machine | Difficulty | Key Techniques | Write-up |
|---|---|---|---|
| **Cap** | Easy | IDOR, PCAP analysis, cap_setuid privilege escalation | [Read](https://mavhezha.com/blog/htb-cap-writeup) |
| **Nibbles** | Easy | Default creds, PHP file upload, sudo misconfiguration | [Read](https://mavhezha.com/blog/htb-nibbles-writeup) |
| **Bashed** | Easy | PHP webshell, cron job privilege escalation | [Read](https://mavhezha.com/blog/htb-bashed-writeup) |
| **Shocker** | Easy | Shellshock CGI exploit, sudo perl escalation | [Read](https://mavhezha.com/blog/htb-shocker-writeup) |
| **Lame** | Easy | Samba usermap script RCE, distcc exploit | [Read](https://mavhezha.com/blog/htb-lame-writeup) |

---

## Blog

Technical write-ups at **[mavhezha.com/blog](https://mavhezha.com/blog)**

**DFIR Challenge Series** — Self-authored, 6 challenges, 29/30 flags captured:

| # | Challenge | Evidence Type |
|---|---|---|
| 01 | Log Parsing | Syslog, auth.log, Apache access logs |
| 02 | Memory Forensics | Volatility, Cobalt Strike beacon, credential extraction |
| 03 | Network Forensics | PCAP, DNS exfiltration, Wireshark |
| 04 | Disk Forensics | Ext4, deleted file recovery, artifact analysis |
| 05 | Malware Triage | PE analysis, VBA macros, YARA-style detection |
| 06 | Incident Timeline | Full breach reconstruction, MITRE ATT&CK mapping |

Also working through HTB Academy's AI Red Teamer path — prompt injection, data poisoning, and adversarial evasion against LLMs and ML models.

---

## Speaking & Leadership

- **VP, ISACA Yeshiva University chapter**
- **Speaker, DigiSkills 2.0 Bootcamp** (July 2026)
- **Public Relations Director, JCI Capital Zimbabwe**

---

## Certifications

![CISSP](https://img.shields.io/badge/ISC2-CISSP-006400?style=flat-square&logoColor=white)
![Security+](https://img.shields.io/badge/CompTIA-Security%2B-FF0000?style=flat-square&logo=comptia&logoColor=white)
![ISC2 CC](https://img.shields.io/badge/ISC2-CC-006400?style=flat-square&logoColor=white)
![CCSK](https://img.shields.io/badge/CSA-CCSK-4B0082?style=flat-square&logoColor=white)
![ISO 27001](https://img.shields.io/badge/ISO-27001%20Lead%20Auditor-0072C6?style=flat-square&logoColor=white)
![ISO 42001](https://img.shields.io/badge/ISO-42001%20Lead%20Auditor-0072C6?style=flat-square&logoColor=white)
![OSCP](https://img.shields.io/badge/OSCP-In%20Progress-64FFDA?style=flat-square&logoColor=black)

---

## Tools

**Offensive**

![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4B8BBE?style=flat-square&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logoColor=white)
![evil-winrm](https://img.shields.io/badge/evil--winrm-cc0000?style=flat-square&logoColor=white)
![Hashcat](https://img.shields.io/badge/Hashcat-black?style=flat-square&logoColor=white)
![BloodHound](https://img.shields.io/badge/BloodHound-CC0000?style=flat-square&logoColor=white)
![Impacket](https://img.shields.io/badge/Impacket-4B8BBE?style=flat-square&logoColor=white)
![netexec](https://img.shields.io/badge/netexec-333333?style=flat-square&logoColor=white)

**Forensics & Detection**

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Volatility](https://img.shields.io/badge/Volatility-555555?style=flat-square&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![WinPEAS](https://img.shields.io/badge/WinPEAS-red?style=flat-square&logoColor=white)

**Languages & Scripting**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**Cloud & Governance**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![ISO 27001](https://img.shields.io/badge/ISO_27001-0072C6?style=flat-square&logoColor=white)
![NIST](https://img.shields.io/badge/NIST_CSF-003087?style=flat-square&logoColor=white)

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=mavhezha&hide_border=true&background=0a192f&stroke=233554&ring=64ffda&fire=64ffda&currStreakNum=ccd6f6&sideNums=ccd6f6&currStreakLabel=64ffda&sideLabels=8892b0&dates=8892b0" alt="GitHub streak" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mavhezha&bg_color=0a192f&color=64ffda&line=64ffda&point=ccd6f6&area=true&area_color=64ffda&hide_border=true" alt="Contribution graph" />

</div>

---

<div align="center">
<sub>mavhezha.com &nbsp;|&nbsp; Reconstructing Real Attacks. Building New Ones.</sub>
</div>
