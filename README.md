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

## 📁 Project Structure

ragnarok_extended/
│
├── app.py # Flask web server
├── requirements.txt # Dependencies
├── README.md # Project info
│
├── templates/ # Web interface (HTML)
│ ├── index.html
│ └── results.html
│
├── core/ # Simulation modules
│ └── simulate_attack.py
│
├── modules/ # Recon modules, payload tools
│ └── subdomain_recon.py
│
├── config/ # Config settings
│ └── settings.py
│
├── logs/ # Logging engine
│ └── logger.py
│
└── reports/
└── logs.json # Scan log history

yaml
Copy
Edit

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/ragnarok-pro.git
cd ragnarok-pro
pip install -r requirements.txt
python app.py
