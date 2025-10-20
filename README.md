# Task-1-Network-Port-Scanning (Cyber Security Internship)
Nmap TCP SYN scan of local network for cybersecurity internship task

## 📌 Objective
To perform a **TCP SYN scan** on the local network to discover **active hosts** and **open ports**, helping understand network exposure and security posture.

---

## 🛠 Tools Used
- **Nmap** – for port scanning
- **ifconfig** – to find local IP range

---

## 🌐 Network Details
- **Local IP:** 10.0.2.15  
- **Network Range:** 10.0.2.0/24

Command used:
```bash
nmap -sS 10.0.2.0/24 -oN scan_results.txt
