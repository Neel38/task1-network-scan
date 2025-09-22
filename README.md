# Task 1 - Local Network Port Scanning

## 📌 Objective
The goal of this task was to perform **network reconnaissance** using `Nmap` to discover devices in the local network, identify open ports, and analyze potential security risks.

## 🛠 Tools Used
- **Nmap** (for port scanning)
- **Wireshark** (optional, for packet capture and traffic analysis)
- **GitHub** (for documentation and submission)

## 🔍 Steps Performed
1. Installed Nmap on my system.
2. Identified my local IP range (example: `192.168.1.0/24`).
3. Performed a TCP SYN scan:
   ```bash
   nmap -sS 172.31.0.0/16
   ```
4. Saved scan results into a file:
   ```bash
   nmap -sS 172.31.0.0/16 -oN scan_results.txt
   ```
5. Researched common services running on discovered open ports.

## 📂 Repository Contents

scan_results.txt → Raw Nmap scan output.

screenshots/ → Screenshots of terminal.

README.md → Documentation of the task.

## 🎯 Key Learnings

How to use Nmap for scanning local networks.

Understanding the role of open ports in network exposure.

How Wireshark complements port scanning by showing traffic details.

Importance of securing unnecessary open ports with firewalls and configuration.
