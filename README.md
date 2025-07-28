# 🛡️ Ragnarök Pro – Offensive Security Toolkit

**Ragnarök Pro** is a modular, web-based cybersecurity reconnaissance and simulation tool built with Python and Flask. It is designed for ethical hacking internships, penetration testers, and security researchers.

---

## 🔧 Features

- 🔍 **Recon Scanner** – Discover subdomains of a target domain  
- 🧱 **WAF Detection** – Detect if a web application firewall is present  
- 💣 **Payload Forge** – Test and encode attack payloads like XSS, SQLi  
- ⚔️ **Attack Simulator**
  - HTTP HEAD Requests  
  - HTTP/2 Latency Tests  
  - ICMP Ping (via Scapy)  
  - (Optional) Slowloris socket simulation  

---



## 🚀 Getting Started

```bash
git clone https://github.com/princy0708/ragnarok-pro.git
cd ragnarok-pro
pip install -r requirements.txt
python app.py
