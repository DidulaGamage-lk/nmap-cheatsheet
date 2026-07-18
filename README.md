<div align="center">

# 🛰️ Nmap Cheatsheet

### The Ultimate Network Scanning & Enumeration Guide

A modern and comprehensive collection of **Nmap commands**, practical examples, and scanning techniques for **Ethical Hackers**, **Penetration Testers**, **Network Engineers**, **Cybersecurity Students**, and **System Administrators**.

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=00FF7F&center=true&vCenter=true&width=700&lines=Nmap+Cheatsheet;Network+Scanning+Made+Easy;Enumeration+%7C+Reconnaissance;Ethical+Hacking+Toolkit" />

![GitHub Repo stars](https://img.shields.io/github/stars/YOUR_USERNAME/nmap-cheatsheet?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/nmap-cheatsheet?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/nmap-cheatsheet?style=for-the-badge)
![License](https://img.shields.io/github/license/YOUR_USERNAME/nmap-cheatsheet?style=for-the-badge)

</div>

---

# 📖 About

This repository provides a well-organized collection of **Nmap commands**, categorized by scanning technique, host discovery, port scanning, service detection, OS detection, NSE scripting, firewall evasion, and performance tuning.

Perfect for:

- 🔐 Ethical Hackers
- 🛡️ Penetration Testers
- 🌐 Network Engineers
- 💻 IT Professionals
- 🎓 Cybersecurity Students

---

# 📂 Categories

| Category | Description |
|-----------|-------------|
| 🚀 Basic Scans | Basic Nmap Usage |
| 🌐 Host Discovery | Discover Live Hosts |
| 🔍 Port Scanning | TCP/UDP Scans |
| ⚙️ Service Detection | Version Detection |
| 💻 OS Detection | Operating System Fingerprinting |
| 📜 NSE Scripts | Nmap Scripting Engine |
| 🔥 Firewall Evasion | IDS/IPS Bypass |
| ⚡ Performance | Scan Optimization |
| 💾 Output Formats | Save Scan Results |

---

# 🚀 Basic Commands

### Scan One Host

```bash
nmap 192.168.1.1
```

---

### Scan Multiple Hosts

```bash
nmap 192.168.1.1 192.168.1.2
```

---

### Scan an Entire Subnet

```bash
nmap 192.168.1.0/24
```

---

### Scan a Domain

```bash
nmap scanme.nmap.org
```

---

# 🔍 Port Scanning

### SYN Scan

```bash
nmap -sS 192.168.1.1
```

### TCP Connect Scan

```bash
nmap -sT target
```

### UDP Scan

```bash
nmap -sU target
```

### Scan Specific Ports

```bash
nmap -p 22,80,443 target
```

### Scan All Ports

```bash
nmap -p- target
```

---

# ⚙️ Service Detection

```bash
nmap -sV target
```

Detect running services and versions.

---

# 💻 OS Detection

```bash
sudo nmap -O target
```

Detect operating system.

---

# 🔥 Aggressive Scan

```bash
sudo nmap -A target
```

Includes:

- OS Detection
- Version Detection
- Default NSE Scripts
- Traceroute

---

# 🌐 Host Discovery

```bash
nmap -sn 192.168.1.0/24
```

Ping sweep.

---

# 📜 NSE Scripts

Default Scripts

```bash
nmap -sC target
```

Run Specific Script

```bash
nmap --script=http-title target
```

Vulnerability Scan

```bash
nmap --script vuln target
```

SMB Enumeration

```bash
nmap --script smb-enum-shares target
```

---

# 🔥 Firewall Evasion

Fragment Packets

```bash
nmap -f target
```

Randomize Scan Order

```bash
nmap --randomize-hosts target
```

Decoy Scan

```bash
nmap -D RND:10 target
```

Spoof MAC Address

```bash
nmap --spoof-mac Cisco target
```

---

# ⚡ Performance

Fast Scan

```bash
nmap -F target
```

Timing Template

```bash
nmap -T4 target
```

Maximum Speed

```bash
nmap -T5 target
```

---

# 💾 Save Results

Normal Output

```bash
nmap -oN scan.txt target
```

XML

```bash
nmap -oX scan.xml target
```

All Formats

```bash
nmap -oA fullscan target
```

---

# ⭐ Popular Commands

| Command | Description |
|----------|-------------|
| nmap target | Default Scan |
| nmap -Pn target | Skip Host Discovery |
| nmap -sS target | SYN Scan |
| nmap -sV target | Service Detection |
| sudo nmap -O target | OS Detection |
| sudo nmap -A target | Aggressive Scan |
| nmap -sC target | Default Scripts |
| nmap --script vuln target | Vulnerability Scan |
| nmap -p- target | Scan All Ports |
| nmap -T4 target | Faster Scan |
| nmap -oA scan target | Save Output |

---

# 📚 Repository Features

- ✅ 100+ Nmap Commands
- ✅ Beginner Friendly
- ✅ Advanced Scanning Techniques
- ✅ NSE Script Examples
- ✅ Firewall Evasion
- ✅ Enumeration Guide
- ✅ Practical Examples
- ✅ Frequently Updated

---

# 🤝 Contributing

Pull requests are welcome.

Feel free to:

- Add new commands
- Improve explanations
- Add useful NSE scripts
- Submit Pull Requests

---

# 📜 License

MIT License

---

<div align="center">

⭐ If you found this project useful, consider giving it a Star!

Made with ❤️ by **Didula Gamage**

</div>
