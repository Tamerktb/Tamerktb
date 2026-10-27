<div align="center">

# Tamer Al-Khatib

**Cybersecurity Analyst — Detection Engineering · SOC Operations · Security Automation**

📍 Amman, Jordan &nbsp;·&nbsp; ✉️ [tamerktb2003@gmail.com](mailto:tamerktb2003@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/tamer-al-khatib/)

</div>

---

I build detection and response systems, not slide decks — and I make them run.

My projects deploy real infrastructure: a **Splunk app** that catches SSH credential-stuffing and impossible-travel logins against *live* threat-intel feeds, a **self-provisioning AWS SOC lab** built with Terraform, and a **Zero Trust gateway** that inspects every API call an AI agent makes.

Hands-on experience at Jordan's **National Cyber Security Center (NCSCJO)** and **Green Circle for Cybersecurity**, spanning SOC operations, penetration testing, GRC compliance, and AI-driven security automation.

---

## 🔬 Featured work

| Project | What it does | Proof |
|---|---|---|
| **[ZT-Agent-Proxy](https://github.com/Tamerktb/ZT-Agent-Proxy)** | Transparent HTTP proxy that inspects, rate-limits, and audits every AI-agent API call. 27 detection rules (prompt injection, secrets, PII, injection), tamper-evident hash-chain audit log, HTML dashboard. | `33/33` tests pass · CI on Python 3.11–3.13 |
| **[SSH Log Analysis — Splunk](https://github.com/Tamerktb/SSH-Log-Analysis-using-Splunk)** | Deployable Splunk app: 9 correlation searches (brute force, credential stuffing, impossible travel, dormant accounts), CIM-mapped, fed by **live** Tor / abuse.ch / Spamhaus intel. Full Elastic 8.15 + ElastAlert 2 port included. | Verified end-to-end against real Hydra brute-force traffic |
| **[Cloud Security Monitoring Lab](https://github.com/Tamerktb/cloud-security-monitoring-lab)** | Self-provisioning AWS SOC — Terraform builds VPC, EC2, CloudTrail and VPC Flow Logs; Wazuh SIEM, Cowrie honeypot, and custom detection rules on top. | `terraform apply` → running detections |
| **[SASE Deployment Lab](https://github.com/Tamerktb/sase-deployment-lab)** | Cloudflare Zero Trust + WireGuard multi-site mesh with device posture checks and split-tunneling. Entirely Infrastructure-as-Code. | CI green · Docker sim + optional real EC2 mesh |
| **[IOC Enrichment Pipeline](https://github.com/Tamerktb/ioc-enrichment-pipeline)** | Multi-API threat-intel enrichment with SQLite caching, weighted risk scoring, retry/backoff, and Splunk-ready output. CLI + Streamlit UI. | Graceful degradation + dead-letter logging |
| **[EDR Home Lab](https://github.com/Tamerktb/EDR-Home-Lab)** | Sliver C2 vs. LimaCharlie EDR attack-and-defense simulation — LSASS access, ransomware behavior, lateral movement — with detection & response rules for each. | 8 rules · Vagrant-automated VMs |

---

## 🧰 Toolkit

| Area | Tools |
|---|---|
| **Detection & Response** | Splunk (SPL · CIM · correlation searches), Wazuh, LimaCharlie, Sysmon, ElastAlert 2, Elastic 8.x |
| **Offensive Security** | Kali Linux, Sliver C2, Hydra, Burp Suite, OWASP Top 10 web-app testing |
| **Cloud & Network** | AWS (CloudTrail · VPC · IAM), Terraform, Cloudflare Zero Trust, WireGuard, pfSense, Suricata IDS/IPS |
| **Automation & Code** | Python, PowerShell, Bash, Docker, Git / GitHub Actions, REST APIs |
| **Governance & Risk** | ISO 27001, NIST CSF control mapping, risk documentation |

---

## 📫 Let's talk

I'm open to **SOC analyst, security engineer, and GRC** roles, and to security-automation work.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tamer-al-khatib/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tamerktb2003@gmail.com)

*"Security is not a product, but a process." — Bruce Schneier*

</div>
