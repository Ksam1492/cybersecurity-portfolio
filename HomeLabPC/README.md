# 🏠 HomeLabPC - Cybersecurity Home Lab

This folder documents the setup and usage of my personal cybersecurity home lab, built on an older PC using Oracle VirtualBox. The lab is designed to provide hands-on experience in Linux administration, ethical hacking, vulnerability testing, and network security — all in support of building a strong cybersecurity portfolio.

---

## 🖥️ Host System Specs

- **Machine Name:** HomeLabPC
- **CPU:** Intel Core i5-7400
- **GPU:** NVIDIA GTX 1060 3GB
- **RAM:** 16GB
- **Storage:** 128GB SSD + 1TB HDD
- **Operating System:** Windows 10 (headless setup)
- **Remote Access Tool:** AnyDesk
- **Virtualization:** Oracle VirtualBox

---

## 🧱 Virtual Machines

| VM Name        | OS            | Role                                  |
|----------------|---------------|---------------------------------------|
| Kali           | Kali Linux    | Attacker / Pentesting toolkit         |
| Ubuntu         | Ubuntu Server | Hardening, services, and SSH testing  |
| Ubuntu-DVWA    | Ubuntu Clone  | Vulnerable Web App (DVWA) for testing |

- All VMs are connected via a **Host-Only VirtualBox Network** for internal traffic and isolation.

---

## 🛠️ Tools & Projects (Planned or In Progress)

- [x] Install and configure DVWA on Ubuntu
- [x] Set up isolated VirtualBox network for multi-VM communication
- [ ] Web vulnerability testing with **BurpSuite**, **sqlmap**, and **nikto**
- [ ] Server hardening with **UFW**, **fail2ban**, and SSH configs
- [ ] Vulnerability scans with **Nmap**, **OpenVAS**, or **Nessus**
- [ ] Bash/Python automation scripts for recon/log parsing
- [ ] Internal network mapping and lateral movement simulation
- [ ] CTF-style challenge builds and walkthroughs

---

## 🎯 Goals

- Gain hands-on experience with real-world tools and attack techniques
- Learn how to secure Linux systems and web applications
- Document all findings, processes, and configs as portfolio evidence
- Prepare for careers in cybersecurity, compliance, or IT security

---

## 📁 Folder Contents

This directory includes:
- VM setup & configuration notes
- Security tool usage logs and screenshots
- Hardening test results
- Web exploitation walkthroughs
- Network scanning & enumeration exercises

---

*Created and maintained by Ksam1492*
