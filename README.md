# 🔐 SOC Labs

<div align="center">

# Enterprise Security Operations Center (SOC) Laboratory

### Blue Team • Threat Detection • SIEM • Incident Response • Threat Hunting

![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-0264C8?style=for-the-badge)
![Suricata](https://img.shields.io/badge/Suricata-IDS-EA4335?style=for-the-badge)
![pfSense](https://img.shields.io/badge/pfSense-Firewall-212121?style=for-the-badge)
![VirusTotal](https://img.shields.io/badge/VirusTotal-Threat%20Intel-394EFF?style=for-the-badge)

![Ubuntu](https://img.shields.io/badge/Ubuntu-Linux-E95420?style=for-the-badge)
![Windows](https://img.shields.io/badge/Windows-Endpoint-0078D6?style=for-the-badge)
![MITRE](https://img.shields.io/badge/MITRE-ATT%26CK-red?style=for-the-badge)
![Blue Team](https://img.shields.io/badge/Blue-Team-blue?style=for-the-badge)

![Incident Response](https://img.shields.io/badge/Incident-Response-success?style=for-the-badge)
![Threat Hunting](https://img.shields.io/badge/Threat-Hunting-orange?style=for-the-badge)
![Log Analysis](https://img.shields.io/badge/Log-Analysis-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</div>

---

# 📖 Overview

This repository documents my **6-week Security Operations Center (SOC) internship** completed at **Cyberster**, where I designed, deployed, and operated a hands-on enterprise-style Blue Team laboratory.

The objective of this repository is to demonstrate practical SOC skills by documenting every lab, investigation, and technical report completed throughout the internship. The environment was built using industry-standard security technologies including **Wazuh SIEM**, **Suricata IDS**, **pfSense Firewall**, **Windows Event Logging**, and **MITRE ATT&CK** methodologies.

Throughout the internship, I performed security monitoring, alert investigation, log analysis, detection engineering, vulnerability assessment, threat hunting, and incident response while maintaining professional technical documentation for every completed lab.

Rather than serving as a collection of notes, this repository represents a structured portfolio of practical SOC investigations that reflect real-world Security Operations Center workflows.

---

# 🎯 Repository Objectives

- Build an enterprise-style SOC laboratory
- Deploy and configure Wazuh SIEM
- Centralize Windows event collection
- Develop detection rules for security events
- Monitor endpoint and network activity
- Perform alert triage and investigation
- Conduct vulnerability assessments
- Integrate threat intelligence sources
- Map attacker behavior using MITRE ATT&CK
- Practice incident response procedures
- Produce professional technical documentation

---

# 🏗️ SOC Lab Architecture

```

```
                    Internet
                        │
                        ▼
                 pfSense Firewall
                        │
          ┌─────────────┴─────────────┐
          │                           │
          ▼                           ▼
    Ubuntu Server               Windows Endpoint
   (Wazuh Manager)                 (Sysmon)
          │                           │
          └─────────────┬─────────────┘
                        ▼
                 Security Monitoring
                        │
          ┌─────────────┴─────────────┐
          ▼                           ▼
     Suricata IDS              VirusTotal
          │                           │
          └─────────────┬─────────────┘
                        ▼
                 Threat Detection
                        │
                        ▼
                Incident Response

```

---

# 🛠️ Technologies

| Category | Technologies |
|-----------|-------------|
| SIEM | Wazuh |
| IDS | Suricata |
| Firewall | pfSense |
| Operating Systems | Ubuntu Linux, Windows |
| Endpoint Monitoring | Sysmon |
| Threat Intelligence | VirusTotal |
| Framework | MITRE ATT&CK |
| Methodology | NIST Incident Response |
| Virtualization | Oracle VirtualBox |

---

# 💻 Core Skills Demonstrated

| Blue Team Operations | Detection Engineering | Incident Response |
|----------------------|----------------------|-------------------|
| Security Monitoring | Detection Rules | Alert Investigation |
| Log Analysis | Event Correlation | Incident Triage |
| Threat Hunting | IOC Identification | Evidence Collection |
| Vulnerability Assessment | MITRE ATT&CK Mapping | Technical Reporting |

---

# 🎓 Learning Outcomes

Throughout this internship I gained practical experience in:

- Enterprise SIEM Deployment
- Windows Log Collection
- Linux Administration
- Security Event Monitoring
- Threat Detection
- Detection Rule Development
- Network Security Monitoring
- Threat Intelligence Integration
- Vulnerability Assessment
- Threat Hunting
- MITRE ATT&CK Mapping
- Incident Response
- Technical Documentation
