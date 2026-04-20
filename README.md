# WannaCry Ransomware - STIX 2.1 Cyber Threat Intelligence Analysis

![STIX](https://img.shields.io/badge/STIX-2.1-blue)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-Used-red)
![Cyber Threat Intelligence](https://img.shields.io/badge/CTI-Advanced%20Network%20Security-green)

## 📋 Project Overview
This repository contains my **Structured Threat Intelligence eXpression (STIX 2.1)** class activity for the **WannaCry Ransomware Attack (2017)**, attributed to the **Lazarus Group (APT38)**, a North Korea-linked nation-state actor.

I extracted threat intelligence from open sources, built a complete **STIX 2.1 JSON bundle**, mapped Tactics, Techniques, and Procedures (TTPs) using **MITRE ATT&CK**, and documented everything in a detailed report.

### Key Deliverables
- **Full Analysis Report** (DOCX): Detailed cyberattack overview, threat actor profile, malware analysis, TTPs, vulnerability details (CVE-2017-0144 - EternalBlue), and IoCs.
- **STIX 2.1 Bundle** (`wannacry_stix_bundle.json`): Machine-readable threat intelligence including:
  - Threat Actor (Lazarus Group)
  - Malware (WannaCry Ransomware + Worm)
  - Vulnerability (EternalBlue)
  - Multiple Indicators (file hash, kill-switch domain, registry key)
  - Attack Patterns (T1190, T1486, etc.)
  - Course of Action (mitigations like MS17-010 patch)
  - Relationships linking all objects
- Visualization guidance using the official **STIX Viz tool**.

## 🛠 Technologies & Standards Used
- **STIX 2.1** (OASIS Standard)
- **MITRE ATT&CK Framework** (TTP mapping)
- **CVE/NVD** vulnerability data
- Cyber Kill Chain
- JSON structuring for threat intelligence sharing

## 📂 Repository Structure

## 🔍 How to Use the STIX Bundle
1. Download `wannacry_stix_bundle.json`.
2. Open the [STIX Visualization Tool](https://oasis-open.github.io/cti-stix-visualization/).
3. Upload the JSON file.
4. Explore the interactive graph showing relationships between the threat actor, malware, vulnerability, indicators, and mitigations.

The bundle is fully compliant with STIX 2.1 and can be imported into tools like **MISP**, **OpenCTI**, or any STIX-compatible platform.

## 📊 STIX Graph Visualization

![WannaCry STIX 2.1 Graph](images/stix-viz-graph.png)

The central node is the WannaCry malware object, connected to the Lazarus Group (threat-actor), EternalBlue vulnerability, multiple Indicators of Compromise, and mitigation actions.

## 🎯 Learning Outcomes
- Practical application of **STIX 2.1** for structuring CTI.
- Threat actor profiling and attribution.
- Malware reverse-engineering basics and IoC extraction.
- Mapping real-world attacks to **MITRE ATT&CK**.
- Understanding ransomware propagation (EternalBlue exploit) and kill-switch mechanisms.

## 📚 References
- MITRE ATT&CK (WannaCry & Lazarus Group)
- NIST NVD (CVE-2017-0144)
- Microsoft MS17-010 Bulletin
- Kaspersky, Symantec, and US-CERT reports

## 👤 About the Author
**Muhammad Ahmad**  
Roll No: 25I-7705  
FAST National University, Department of Cybersecurity  
Advanced Network Security (ANS) Course

This project demonstrates my ability to consume unstructured threat reports and produce high-quality, machine-readable **Cyber Threat Intelligence** using industry standards.

Feel free to explore the files, use the STIX bundle for learning/practice, or reach out for discussions on CTI, STIX, or ransomware analysis!

---

⭐ If you find this useful, please star the repository!
