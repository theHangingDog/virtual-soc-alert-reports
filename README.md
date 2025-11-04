
# 🛡️ Virtual SOC Alert Reports

This repository contains my analysis reports of security alerts generated in a **Virtual Security Operations Center (vSOC)** environment.  
Each report simulates a real-world SOC investigation — from alert triage to final remediation recommendations.

---

## ⚠️ alerts
- EventID@93 - SOC146 - Phishing Mail Detected - Excel 4.0 Macros
- EventID@234- SOC176 - RDP Brute Force Detected
- EventID@263 - SOC287 - Arbitrary File Read on Checkpoint Security Gateway - CVE-2024-24919
- EventID@235 - SOC127 - SQL Injection Detected
- EventID@316 - Lumma Stealer - DLL Side-Loading via Click Fix Phishing


Each alert report includes:

1. **Alert Summary** – Overview of what triggered the alert  
2. **Initial Triage** – Basic validation, data sources, and context gathered  
3. **Investigation Steps** – Deep dive into logs, tools, and correlation  
4. **Findings** – Root cause, impacted systems, and key indicators  
5. **Mitigation & Recommendations** – Containment, eradication, and hardening steps  
6. **MITRE ATT&CK Mapping** – Relevant techniques and tactics  
7. **Lessons Learned** – Analyst reflections and takeaways  

---

## 🧰 Tools & Platforms Used

- **SIEM:** Splunk / ELK / Azure Sentinel (varies per alert)  
- **Case Management:** TheHive  
- **Threat Intel Sources:** VirusTotal, Any.Run, AbuseIPDB, etc.  
- **Sandboxing / Analysis:** Hybrid Analysis, Joe Sandbox  
- **Custom Scripts:** Bash & Python for log enrichment  

---

## 🧩 Purpose

This project helps me:
- Strengthen blue team and incident response skills  
- Build an investigation mindset  
- Document and share analysis methodology  
- Create a portfolio showcasing SOC analysis capabilities  

---


## 📄 License

This project is for **educational and research purposes** only.  
All data used is synthetic or anonymized.  

---

## 👤 Author

**Arkaprava Goswami**  
Blue Team | SOC Analyst | Cybersecurity Enthusiast  
🔗 [LinkedIn](www.linkedin.com/in/arkaprava-goswami-953554339)

---

> “Every alert tells a story — the goal is to find what really happened.
