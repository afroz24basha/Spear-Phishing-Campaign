# 🛡️ Spear-Phishing Campaign: Security Investigation & Threat Intelligence Report

---

## 📌 Executive Summary
This repository contains a comprehensive **full-lifecycle security investigation** conducted on a simulated spear-phishing campaign. The project demonstrates the application of industry-standard threat intelligence methodologies, IOC correlation, and security framework mapping to analyze and mitigate advanced persistent threats.

---

## 🚀 Key Objectives
* **Threat Intelligence Gathering:** Correlated Indicators of Compromise (IOCs) including domains, IP addresses, and file hashes across multiple industry-standard platforms.
* **TTP Analysis:** Mapped Adversary Tactics, Techniques, and Procedures (TTPs) against the **MITRE ATT&CK Framework**.
* **Remediation Planning:** Developed actionable replacement detection controls to strengthen the organization’s security posture.

---

## 🔍 Investigation Methodology

### 1. IOC Correlation & Intelligence
To ensure high-fidelity analysis, indicators were cross-referenced using the following platforms:
* **VirusTotal:** For file reputation and hash analysis.
* **AbuseIPDB:** For validating malicious IP addresses and source reputation.
* **AlienVault OTX:** For threat pulse collection and campaign context.

### 2. MITRE ATT&CK Mapping
The activity identified during the simulation was mapped to the following specific techniques:

| Technique ID | Name | Description |
| :--- | :--- | :--- |
| **T1566** | Phishing | Spear-phishing via malicious attachment/link. |
| **T1059** | Command and Scripting Interpreter | Execution of malicious payloads via scripting. |
| **T1071** | Application Layer Protocol | C2 communication via standard web protocols. |

---

## 📄 Deliverables
The core output of this investigation is a **formal analyst report** included in this repository. 
* **Verified Assertions:** Evidence-based conclusions regarding the attack vector.
* **Digital Evidence:** Logs, artifacts, and IOC snapshots.
* **Recommendations:** Proposed detection engineering strategies to mitigate similar future threats.

---

## 🛠️ Tools Used
- `VirusTotal` | `AbuseIPDB` | `AlienVault OTX` | `MITRE ATT&CK Navigator`

---

*Disclaimer: This project was conducted in a controlled, simulated environment for educational and security training purposes.*
