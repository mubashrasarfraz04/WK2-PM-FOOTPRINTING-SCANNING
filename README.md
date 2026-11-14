  # 🔐 Cybersecurity Lab Environment Setup

### Building an isolated virtual lab for OSINT Footprinting and Network Scanning

![Skill: Cybersecurity](https://img.shields.io/badge/Skill-Cybersecurity-red?style=for-the-badge)
![Tool: Maltego CE](https://img.shields.io/badge/Tool-Maltego_CE-yellow?style=for-the-badge)
![Tool: Zenmap](https://img.shields.io/badge/Tool-Zenmap%20Nmap-blue?style=for-the-badge)
![Version: Nmap v7.95](https://img.shields.io/badge/Ver-Nmap_v7.95-lightblue?style=for-the-badge)
![Network: 192.168.18.0/24](https://img.shields.io/badge/Network-192.168.18.0%2F24-orange?style=for-the-badge)
![Skill: OSINT](https://img.shields.io/badge/Skill-OSINT-green?style=for-the-badge)
![Skill: Virtualization](https://img.shields.io/badge/Skill-Virtualization-purple?style=for-the-badge)
![Platform: GitHub](https://img.shields.io/badge/Platform-GitHub-black?style=for-the-badge)
![Lab: NetworkWalks](https://img.shields.io/badge/Lab-NetworkWalks-red?style=for-the-badge)
![Topic: Ethical Hacking](https://img.shields.io/badge/Topic-Ethical_Hacking-orange?style=for-the-badge)

---

### ✨ Project Overview
This project focuses on setting up a virtual cybersecurity lab for OSINT Footprinting and Network Scanning using Maltego CE and Zenmap.

The purpose of this lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely.

This lab is divided into two practical modules:
- W2-PM3: OSINT Footprinting with Maltego CE
- W2-PM5: Network Scanning with Zenmap (Nmap)

---

### 🎯 Objectives
- To understand OSINT & Footprinting methodology
- To perform Domain, Email, and DNS footprinting
- To discover live hosts in a local network
- To document IP-MAC mapping

### 🔬 Lab Architecture
| Component | Details |
| :--- | :--- |
| Host OS | Windows 11 |
| Tool 1| Maltego CE v4.8.0 |
| Tool 2| Zenmap 7.95 |
| Target 1 | networkwalks.com (PM3 - Authorized) |
| Target 2 | 192.168.18.0/24 (PM5 - Own LAN) |

### ⚙️ Lab Procedure

#### W2-PM3: Maltego Footprinting
1. Added domain `networkwalks.com` as entity
2. Transform: `To Email Address [Using Search Engine]` -> Found emails
3. Transform: `To Person` -> Found related persons
4. Transform: `To DNS Name / To Website` -> Found subdomains
5. Transform: `To IP Address` -> Resolved IPs

#### W2-PM5: Zenmap Scanning
1. Ran `ipconfig` -> Found subnet `192.168.18.0/24`
2. Ran `nmap -sn 192.168.18.0/24` -> Found 8 Live Hosts
3. Documented IP-MAC mapping
4. Performed Intense Scan for OS & Ports

### ✅ Lab Verification
- ✔️ Maltego graph completed successfully
- ✔️ Zenmap discovered 8 hosts matching router list
- ✔️ Screenshots attached as proof

### 🧰 Tools Used
- Maltego CE, Zenmap, Nmap, GitHub

### 👩‍💻 Author Mubashra Sarfraz | B084 | Networkwalks
LiksdIN:https://www.linkedin.com/in/mubashra-khan-981805430?utm_source=share_via&utm_content=profile&utm_medium=member_android

### 📚 Project Info
- Week: 02 | Modules: W2-PM3 & W2-PM5 | Date: 14 November
