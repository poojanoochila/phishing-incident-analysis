# Phishing Incident Investigation (SOC-Style Analysis)

## Overview

This project presents a **SOC-style investigation** of a multi-vector phishing and ad-fraud campaign targeting job seekers. The analysis focuses on identifying attack patterns, extracting indicators of compromise (IOCs), and profiling adversary infrastructure and behavior.

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

* **Email Header Analysis** – Tracing sender origin and authentication (DKIM, SMTP)
* **Browser DevTools** – HTML source code and script analysis
* **Hashing Tools** (HashCalc, certutil, PowerShell Get-FileHash) – Integrity concepts
* **Nmap (Conceptual)** – Network reconnaissance understanding
* **OSINT Techniques** – Domain and infrastructure profiling

---

## Methodology

### 1. Email Analysis

* Examined email headers to trace origin and verify authentication mechanisms
* Identified suspicious sender domains and social engineering patterns

### 2. URL & Payload Inspection

* Analyzed embedded links and redirection behavior
* Identified parameterized URLs and tracking indicators

### 3. Web & Source Code Analysis

* Inspected HTML source code of landing pages
* Identified CMS platform, advertising scripts, and tracking mechanisms
* Detected monetization and user-tracking components

### 4. IOC Extraction & Correlation

* Extracted indicators including:

  * Malicious URLs
  * Suspicious domains
  * Associated IP addresses
* Correlated indicators to understand campaign infrastructure

### 5. Threat Mapping

* Mapped observed techniques to **MITRE ATT&CK**
* Identified tactics such as:

  * Initial Access (Phishing)
  * Resource Development / Infrastructure Setup
  * Command & Control (suspicious domains)

### 6. Reporting & Disclosure

* Created a structured SOC-style incident report
* Documented findings, impact, and remediation strategies
* Reported phishing infrastructure to relevant organizations

---

## Key Outcomes

* Identified a coordinated phishing and ad-fraud campaign targeting job seekers
* Extracted and analyzed **15+ IOCs**
* Identified tracking and monetization mechanisms (AdSense, analytics scripts)
* Mapped attacker behavior to MITRE ATT&CK techniques
* Produced a professional incident report aligned with SOC workflows

---

## Skills Demonstrated

* Threat Detection & Analysis
* Incident Investigation & Reporting
* IOC Extraction & Correlation
* Web Application & Source Code Analysis
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
│   ├── landing-page.png
│   ├── adsense-script.png
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
