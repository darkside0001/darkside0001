<h1>Hi, I'm Razim Kudaybergenov 👋</h1>

**MSc Cyber Security student at Asia Pacific University (Malaysia) · Fortinet NSE 1–3 · Certified Wialon Specialist L4.** I audit and harden Linux servers and web platforms, and I build the backend systems I secure.

- 🔐 Looking for a role in **cybersecurity**: security operations, pentesting, infrastructure security
- 💼 2 years as Wialon Specialist & IT Security Engineer at Track Monitoring Service (Uzbekistan)
- 🛠️ Freelance: server security audits, CRM development, Wialon GPS telematics
- 🌐 Portfolio: [darkside0001.github.io](https://darkside0001.github.io) · [CV (PDF)](https://darkside0001.github.io/Razim_Kudaybergenov_CV.pdf)
- 📫 [Email](mailto:razim200112@gmail.com) · [Telegram](https://t.me/rafael_QQ) · [Freelancer](https://www.freelancer.com/u/razimk1)

### What I work with

![Linux](https://img.shields.io/badge/Linux-111?logo=linux&logoColor=white)
![Python](https://img.shields.io/badge/Python-111?logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-111?logo=gnubash&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-111?logo=gnubash&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-111?logo=caddy&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-111?logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-111?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-111?logo=grafana&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/SQL-111?logo=postgresql&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bots-111?logo=telegram&logoColor=white)
![Git](https://img.shields.io/badge/Git-111?logo=git&logoColor=white)

### Certifications

- Fortinet NSE 1, 2 & 3 Certified in Cybersecurity (2026)
- Certified Wialon Specialist, Level 4, Gurtam (2026)
- Google: Connect and Protect: Networks and Network Security (2023)
- IBM: Introduction to Cybersecurity Careers (2024)
- Microsoft: Build a Computer Vision App with Azure Cognitive Services (2023)

### Security engineering projects

| Project | What it shows |
|---|---|
| [**infra-security-monitoring**](https://github.com/darkside0001/infra-security-monitoring) | Hardened web stack in Docker: Caddy + TLS, segmented networks, nftables firewall, Prometheus/Alertmanager, Loki log-based detections (MITRE ATT&CK), encrypted restic backups with automatic restore tests and a DR drill. STRIDE threat model, ADRs, runbook, 41 end-to-end checks in CI |
| [**CRM API pentest**](https://github.com/darkside0001/crm-demo/blob/main/docs/pentest-report.md) | Authenticated OWASP API Top 10 pentest of my own [crm-demo](https://github.com/darkside0001/crm-demo) API: 8 findings (CVSS up to 6.8), all fixed, retested to 0, with a regression test per finding |
| [**Linux hardening, before/after**](https://github.com/darkside0001/linux-hardening-audit/blob/main/docs/before-after-report.md) | `harden.sh` with dry run, backups and rollback took an insecure Ubuntu VPS lab from 44/100 to 98/100, with SSH key login checked after every run |

### Open-source security tools

| Tool | What it does |
|---|---|
| [**soc-home-lab**](https://github.com/darkside0001/soc-home-lab) | Wazuh SOC home lab in Docker: a monitored victim, a scripted SSH attack chain, and 15 custom detection rules mapped to MITRE ATT&CK, each verified against the real Wazuh engine in CI |
| [**linux-hardening-audit**](https://github.com/darkside0001/linux-hardening-audit) | Bash. CIS-style Linux audit (SSH, accounts, sudo, permissions, sysctl, firewall, updates) with a score and a fix for every finding, plus a safe `harden.sh` |
| [**ssh-bruteforce-detector**](https://github.com/darkside0001/ssh-bruteforce-detector) | Python. Detects brute force, password spraying and successful logins after failures in auth logs, mapped to MITRE ATT&CK |
| [**web-sec-check**](https://github.com/darkside0001/web-sec-check) | Python. Grades a site's TLS, certificate, security headers and cookies from A+ to F, usable as a CI gate |
| [**nmap-report**](https://github.com/darkside0001/nmap-report) | Python. Turns nmap XML into HTML/Markdown reports, flags risky exposed services (incl. CCTV DVRs) and diffs scans over time |

### Fleet telematics (Wialon)

| Tool | What it does |
|---|---|
| [**wialon-fleet-alerts**](https://github.com/darkside0001/wialon-fleet-alerts) | Python service on the Wialon Remote API (avl_evts): alerts for silent trackers, overspeed, fuel drains while parked (LLS calibration + median filter), power cuts, GPS loss and geofence exits. Outbox delivery to Telegram and HMAC-signed webhooks, FastAPI for acknowledging alerts, Prometheus metrics, Docker, 79 tests |
| [**wialon-tools**](https://github.com/darkside0001/wialon-tools) | Python CLI: fleet health checks (silent units, duplicate IMEI/SIM), fuel calibration table export/validation/conversion, report export |

### Selected work

| Project | What it is |
|---|---|
| **Server security audits** | Assessments of Linux servers and web platforms with written findings and remediation reports |
| **Retail store CRM** | Inventory, sales and customers for a menswear store, on a VPS with a Telegram bot |
| **Clothing brand CRM** | Orders and client management, from schema to deployment |
| **Fitness gym CRM** | Memberships, attendance and payments |
| **Wialon fleet telematics** | Trackers, fuel sensors and tank calibration, reports and alerts for fleet clients |

<sub>Most client work is private. Happy to walk through it in a call.</sub>
