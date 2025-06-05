#  Network-and-CyberSecurity.2

## Cybersecurity Incident Response and Analysis

This repository provides hands-on implementation and analysis of common cyber threats, along with defensive configurations using industry-standard tools.

---

## Introduction

This project demonstrates how to detect, prevent, and respond to various cybersecurity incidents using real-world tools like:

- **Wazuh** (SIEM & log analysis)
- **ModSecurity** (Web Application Firewall)
- **Snort** (Intrusion Detection System)
- **Hydra** (Brute-force attack tool)
- **MXToolBox** (Email spoofing analysis)
- **Fail2Ban** (SSH intrusion prevention)

Each tool is configured and tested against specific attack scenarios to evaluate their effectiveness in real-time incident response.

---

##  Tools Overview

| Tool         | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| **Wazuh**    | Open-source platform for log data analysis and threat detection.           |
| **ModSecurity** | Web Application Firewall to protect against OWASP Top 10 threats.       |
| **Snort**    | Network-based IDS for traffic monitoring and signature-based detection.     |
| **Hydra**    | Password-cracking tool for brute-force attacks on various protocols.        |
| **MXToolBox**| Online tool for email header and DNS analysis, useful for spoofing detection.|
| **Fail2Ban** | Monitors logs and bans IPs after malicious activity (e.g., failed SSH logins).|

---

##  Incidents Covered

### Incident 1: Wazuh and SQL Injection
- Wazuh installation & dashboard configuration  
- DVWA setup for SQL injection simulation  
- Detection and alerting of SQLi in real time

###  Incident 2: ModSecurity and SQL Injection
-  Simulating SQL injection attacks  
-  Blocking malicious requests with ModSecurity

###  Incident 3: Snort and Hydra (Brute-Force Detection)
-  Simulating SSH brute-force attacks using Hydra  
-  Detecting brute-force attempts via Snort rules

### Incident 4: MXToolBox and Email Spoofing
-  Overview of email spoofing techniques  
-  Using MXToolBox to analyze spoofed headers

### Incident 5: Fail2Ban and SSH Intrusion Prevention
-  Monitoring SSH logs  
-  Automatically banning suspicious IPs using Fail2Ban

###  Bonus: Medusa Brute-Force Attack
-  Executing dictionary attacks  
-  Comparing detection with Hydra attacks

---

##  Challenges & Learnings

Throughout this project, we:
- Gained practical knowledge of attack vectors like **SQLi**, **brute-force**, and **spoofing**
- Learned to implement and tune defensive tools
- Understood alerting mechanisms and traffic inspection
- Faced real-world issues in log parsing, rule conflicts, and IDS configuration

---

##  Conclusion

This project emphasizes the importance of layered security. From web firewalls to log analyzers and IDS systems, every layer adds crucial protection against modern cyber threats.

Cybersecurity is not just about tools—it's about how we **configure**, **monitor**, and **respond** to threats proactively.

---

## References

You can find all references, guides, and documentation links used throughout this project in the [References](./references.md) section.

---

##  How to Use This Repository

1. **Clone the repository**:
   git clone https://github.com/Bakhtawar12384/Network-and-CyberSecurity.2

