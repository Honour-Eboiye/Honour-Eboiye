# Hi, I'm Honour Eboiye

<a href="https://linkedin.com/in/honour-eboiye-22a015311"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:officialhonoureboiye@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?&style=for-the-badge&logo=gmail&logoColor=white" /></a>

**Cybersecurity Student | SOC Analysis • Threat Detection • Cloud Security**

## About

I'm a cybersecurity student who learns by building and investigating. My projects focus on how attacks show up in **network traffic, logs and cloud environments**, and how to turn what I find into **detection rules, hardening steps and clear reports**.

Before security, I built web applications, so I can talk to developers and automate repetitive security work with code.

**Looking for:** SOC Analyst, Cloud Security or Incident Response roles (internship or entry-level).

## Tools I'm Hands-On With

| Area | Tools |
| :--- | :--- |
| **SIEM & Detection** | Microsoft Sentinel, Splunk, KQL, Snort (custom rules) |
| **Network Analysis** | Wireshark, PCAP analysis, Nmap, Nikto, Scapy |
| **Cloud & Identity** | Azure, Microsoft Entra ID, Active Directory, Azure Arc, RBAC, MFA |
| **Hardening** | UFW (default-deny), least privilege, egress filtering |
| **Frameworks** | MITRE ATT&CK |
| **Systems & Scripting** | Linux (Ubuntu), Windows, Python, Bash |

## Security Projects

### 1. Threat Hunting & Detection Engineering (Snort, MITRE ATT&CK, UFW)
**Snort • Wireshark • MITRE ATT&CK • UFW • Python**

Analyzed a real multi-stage attack against a web server from a public traffic capture (**Malware-Traffic-Analysis.net**), then turned the findings into detection rules and hardening recommendations.

- Mapped the attack to MITRE ATT&CK: port scanning, path traversal and PHP-CGI exploitation, router command injection, and a `tcpdump` buffer overflow aimed at blinding monitoring.
- Verified the overflow attempt **failed** by checking ICMP port-unreachable responses in the PCAP and confirming no crashes in host logs, instead of assuming the outcome.
- Wrote custom Snort rules to flag non-web TCP traffic and unexpected UDP.
- Designed a default-deny UFW baseline with restricted SSH, limited outbound DNS/NTP, and egress filtering to block reverse shells.
- Built a Python tool to redact IP addresses from the report before sharing, and manually checked AI-generated code and dependencies before running them.

[View Project](https://github.com/Honour-Eboiye/Threat-Hunting-and-Detection-Engineering)

---

### 2. HawkEye Keylogger: PCAP Analysis & Incident Response
**Wireshark • PCAP Analysis • IOC Extraction • Incident Response**

Analyzed a real HawkEye keylogger infection from a public malware traffic capture.

- Traced stolen data leaving over SMTP and the related DNS activity.
- Extracted indicators of compromise (IPs, domains, file hashes).
- Rebuilt the infection timeline and assessed potential impact.
- Wrote root cause, containment and remediation recommendations.

**Evidence in the repo:** Wireshark screenshots, IOC list, full incident report.

[View Project](https://github.com/Honour-Eboiye/hawkeye-keylogger-incident-response)

---

### 3. Hybrid Cloud Security & SIEM Monitoring Lab
**Azure • Entra ID • Active Directory • Azure Arc • Microsoft Sentinel • KQL**

Built a lab that mirrors a common real-world setup: on-premises identity plus cloud and Linux servers, all feeding one SIEM.

- Synced Active Directory to Microsoft Entra ID with Entra Connect.
- Onboarded Ubuntu Linux to Azure through Azure Arc.
- Applied least-privilege RBAC to cloud resources.
- Connected logs to Microsoft Sentinel and used KQL to investigate authentication activity.
- Documented the setup, troubleshooting and security decisions.

**Evidence in the repo:** architecture diagram, KQL screenshots, RBAC configuration.

[View Project](https://github.com/Honour-Eboiye/Hybrid-Cloud-Security-Lab-Azure-AD-Sync-Linux-Arc-Onboarding-SIEM-Telemetry)

---

### 4. Scapy Port Scanner
**Python • Scapy • TCP/UDP • Network Security**

Wrote a command-line scanner to understand how port scans work and what they look like on the wire.

- TCP SYN and UDP scanning.
- IP and port-range validation, connectivity checks and error handling.
- Interpreted network responses to tell open, closed and filtered ports apart.

[View Project](https://github.com/Honour-Eboiye/Scapy_Port_Scanner)

## Certificates & Training

- **Cisco Networking Academy: Introduction to Cybersecurity**
- **Cisco Networking Academy: Networking Basics**
- **APIsec University: API Security Fundamentals**
- **TryHackMe: Advent of Cyber 2025** (hands-on, scenario-based security challenges)
- **Deloitte (Forage) Job Simulation: [name of the simulation, e.g. Cyber / Technology]**
- **Networking, Security and Maintenance: [issuer, e.g. platform or institution]**

**In progress / planned**
- **Long-term:** CISSP, through the Associate of ISC2 pathway

Currently going deeper on detection engineering, SIEM workflows, incident response and cloud security.

## Development Background

I've built applications with **Python, TypeScript, React, Node.js and MongoDB**. That helps me spot how web applications get attacked and automate security tasks. I'm interested in growing toward security engineering and DevSecOps.

## Connect

- **Email:** [officialhonoureboiye@gmail.com](mailto:officialhonoureboiye@gmail.com)
- **LinkedIn:** [linkedin.com/in/honour-eboiye-22a015311](https://linkedin.com/in/honour-eboiye-22a015311)
