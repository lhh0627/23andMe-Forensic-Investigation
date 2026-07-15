# 23andMe-Forensic-Investigation
Digital forensic investigation and legal analysis of the 2023 23andMe data breach


# 23andMe Data Breach Forensic Investigation 🧬🔍

*Disclaimer: This report is a simulated digital forensic investigation created for educational and portfolio purposes. All analysis, logs, and findings discussed within are based entirely on publicly available threat intelligence, regulatory reports, and news articles regarding the 2023 23andMe data breach. No active penetration testing, unauthorized access, or internal system interaction was performed on any corporate infrastructure.*

## 📄 Executive Summary
This repository contains a comprehensive digital forensic investigation and legal analysis of the 2023 23andMe data breach. The report examines how attackers executed a "low-and-slow" credential stuffing attack to compromise 18,450 accounts, and subsequently exploited the platform's "DNA Relatives" feature to scrape the highly sensitive genetic and profile data of approximately 6.9 million users worldwide. 

The investigation details the attack methodology, evaluates the digital evidence (server logs, dark web intelligence), and maps the incident to both international data protection standards and Malaysian cybercrime legislation.

[**👉 Read the Full Digital Forensic Investigation Report (PDF)**](23andMe_Digital_Forensic_Investigation.pdf)

## 🎯 Key Investigative Findings
* **The Attack Vector:** Threat actors utilized automated "credential stuffing" techniques using compromised credentials from unrelated breaches.
* **The Detection Gap:** The "low-and-slow" nature of the attack allowed it to blend with legitimate traffic, bypassing automated WAF alerts for over five months.
* **The Amplification:** The lack of mandatory Multi-Factor Authentication (MFA) combined with the interconnected data-sharing architecture of the "DNA Relatives" feature allowed a small number of breached accounts to expose millions of global profiles.

## ⚖️ Legal & Regulatory Context
This report analyzes the breach through the lens of international and local cybersecurity law:
* **International Governance:** Evaluated compliance failures under **UK GDPR** and Canada's **PIPEDA**.
* **Malaysian Legal Mapping:** Mapped the attackers' technical actions to specific offenses under the **Malaysian Computer Crimes Act 1997 (CCA 1997)** (Sections 3, 4, 5, and 7).
* **Court Admissibility:** Structured evidence handling according to the **Malaysian Evidence Act 1950** (Section 90A/90B) to ensure the findings represent court-ready expert testimony.

## 🛠️ Methodologies & Tools Demonstrated
The following standards and tools were applied to ensure the integrity of the digital evidence:
* **Forensic Standards:** Strict adherence to **ISO 27037** (Identification, Collection, Acquisition, Preservation) and SWGDE guidelines.
* **Evidence Integrity:** Utilized **SHA-256 Cryptographic Hashing** and maintained rigorous Chain of Custody (CoC) administrative logs.
* **Analytical Techniques:** Time-Window Event Correlation, Bespoke Log Analysis, Dark Web Threat Intelligence monitoring (Hydra Market, BreachForums).
* **Simulated Toolset:** Splunk Enterprise Security, FTK Imager, Wireshark, Autopsy Digital Forensic Platform.
