# Phishing Incident Investigation (SOC-Style Analysis)

## Overview

This project presents a **SOC-style investigation** of a multi-vector phishing and ad-fraud campaign targeting job seekers. The analysis focuses on identifying attack patterns, extracting indicators of compromise (IOCs), and mapping adversary behavior to industry-standard frameworks.

---

## Objectives

* Analyze phishing emails and identify malicious components
* Extract and correlate IOCs (domains, URLs, IPs)
* Understand attacker tactics and delivery mechanisms
* Map findings to MITRE ATT&CK framework
* Document the investigation in a structured SOC report
* Support responsible disclosure by reporting findings

---

## Tools & Technologies

* **Wireshark** – Network traffic and packet analysis
* **Email Header Analysis** – Tracing sender and relay paths
* **Hashing Tools** (HashCalc, certutil, PowerShell Get-FileHash) – Integrity verification
* **Nmap** – Network reconnaissance (lab validation)
* **Autopsy / FTK Imager (Conceptual)** – Forensics workflow understanding

---

## Methodology

### 1. Email Analysis

* Examined email headers to trace origin and identify spoofing attempts
* Identified suspicious sender domains and anomalies in routing paths

### 2. URL & Payload Inspection

* Analyzed embedded links and redirection behavior
* Flagged malicious domains and phishing landing patterns

### 3. IOC Extraction & Correlation

* Extracted indicators including:

  * Malicious URLs
  * Suspicious domains
  * Associated IP addresses
* Correlated indicators to understand campaign infrastructure

### 4. Network Analysis

* Inspected packet captures (PCAP) using Wireshark
* Identified anomalous DNS queries and HTTP traffic patterns

### 5. Threat Mapping

* Mapped observed techniques to **MITRE ATT&CK**
* Identified tactics such as:

  * Initial Access (Phishing)
  * Command & Control (suspicious domains)

### 6. Reporting & Disclosure

* Created a structured SOC-style incident report
* Documented findings, impact, and remediation strategies
* Reported phishing infrastructure to relevant organizations

---

## Key Outcomes

* Identified a coordinated phishing campaign targeting job seekers
* Extracted and analyzed **15+ IOCs**
* Mapped attacker behavior to MITRE ATT&CK techniques
* Produced a professional incident report aligned with SOC workflows
* Contributed to mitigation through responsible disclosure

---

## Skills Demonstrated

* Threat Detection & Analysis
* Incident Investigation & Reporting
* IOC Extraction & Correlation
* Network Traffic Analysis
* Digital Forensics Fundamentals
* Security Framework Mapping (MITRE ATT&CK)

---

## Repository Structure

```
phishing-incident-analysis/
│
├── README.md
├── report.pdf
├── iocs.txt
├── screenshots/
│   ├── email-header-analysis.png
│   ├── wireshark-analysis.png
│
└── notes.md
```

---

## Disclaimer

This project is created for **educational and cybersecurity research purposes only**.
All sensitive information has been **anonymized or redacted**.
This work does not support or promote malicious activity.

---

## Author

Pooja Noochila
Aspiring SOC Analyst | Cybersecurity Enthusiast

---
