# 🔐 CyberSecurity Tools

A collection of security assessment and research scripts for learning, testing, and defensive evaluation in controlled environments.

This repository focuses on understanding common attack techniques in order to improve system security and resilience.

---

## 📌 Purpose

This project is intended for:

- Security students
- Ethical hackers
- Blue team / SOC learners
- Penetration testing practice
- Lab-based security research

All tools are designed for educational and authorized testing only.

---

## 📂 Project Structure

CyberSecurity-Tools/ ├── recon/ ├── scanning/ ├── password/ ├── exploitation/ ├── utilities/ └── docs/


Each directory contains related scripts with usage instructions.

---

## 🛠 Tools Overview

| Category | Tool | Description |
|----------|------|-------------|
| Recon | dns_enum | DNS and subdomain enumeration |
| Scanning | network_scan | Network host and service discovery |
| Scanning | port_scan | Open port identification |
| Password | ftp_cracker | FTP authentication testing |
| Password | ssh_cracker | SSH authentication testing |
| Password | pass_crack | Hash cracking utility |
| Utilities | pdf_crack | PDF password recovery |
| Utilities | pdf_protect | PDF encryption |
| Research | ssh_botnet_sim | Botnet behavior simulation |
| Research | backdoor_lab | Backdoor analysis lab |
| Research | info_steal_lab | Data leakage testing |

---

## ⚙️ Requirements

- Linux (Recommended: Kali / Ubuntu)
- Python 3.8+
- Bash
- Required Python packages:

```bash
pip install -r requirements.txt



🚀 Installation

git clone https://github.com/Varun-1811/CyberSecurity-Tools.git
cd CyberSecurity-Tools


▶️ Usage

bash scanning/port_scan.sh 192.168.1.1