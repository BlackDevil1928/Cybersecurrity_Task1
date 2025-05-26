Cyber Security Internship – Task 1

## 📌 Task: Scan Your Local Network for Open Ports

### 🎯 Objective:
To understand network exposure by discovering open ports on devices within your local network using **Nmap** and optionally analyzing packets using **Wireshark**.

---

## 🧰 Tools Used:
- **Nmap** – for port scanning
- **Wireshark** *(optional)* – for packet capture and traffic analysis
- **Command Prompt / Terminal** – for networking commands

Saved in scan_results.txt.
Example findings:

    192.168.1.1 – Ports: 80 (HTTP), 443 (HTTPS)

    192.168.1.10 – Ports: 22 (SSH)

    192.168.1.15 – Ports: 3389 (RDP)

🕵️ Services Identified:
Port	Service	Description

22	SSH	Remote shell access

80	HTTP	Web server (unsecured)

443	HTTPS	Secure web server

3389	RDP	Windows Remote Desktop
