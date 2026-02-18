# 🔐 Networking & Linux Security Lab

## 📌 Overview
This repository documents my hands-on practice in Networking and Linux fundamentals as part of my cybersecurity learning journey.

The focus of Week 2 is Linux system administration, Bash scripting, process management, networking commands, and SSH hardening in a virtual lab environment.

All practices are performed in a controlled lab using:
- Kali Linux (Attacker Machine)
- Ubuntu Server (Target Machine)
- Internal Network (VirtualBox)

---

# 📅 Week 2 – Linux & Bash Lab

## 🎯 Topics Covered

### 1️⃣ Linux File System
- Linux directory hierarchy
- /etc, /var, /home structure
- Exploring `/etc/passwd`
- File navigation & search (cd, ls, find)

### 2️⃣ Linux Permissions
- r, w, x fundamentals
- chmod (symbolic & numeric)
- chown
- setuid, setgid, sticky bit
- Security risks of 777 permissions

### 3️⃣ Process Management
- ps aux
- top
- kill & kill -9
- Background processes (&, jobs, bg)

### 4️⃣ Networking Commands
- netstat -tulnp
- ss -lnt
- lsof -i
- curl (HTTP request testing)
- telnet (port testing)

### 5️⃣ Bash Scripting
- Variables
- Loop (for)
- Conditional (if)
- Automated ping sweep script

### 6️⃣ SSH Lab & Hardening
- SSH server setup
- Key-based authentication
- Disable password login
- Security testing
- Passphrase management

---

# 🧪 Lab Environment

| Machine | Role | IP Address |
|----------|------|------------|
| Kali Linux | Attacker | 192.168.100.20 |
| Ubuntu Server | Target | 192.168.100.10 |
| Network Mode | Internal Network | /24 |

---

# 🛡 Security Concepts Applied

- Principle of Least Privilege
- Attack Surface Awareness
- Key-Based Authentication
- Service & Port Enumeration
- Process Control & Signal Handling

---

# 📂 Repository Structure
