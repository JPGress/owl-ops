# 0wL OPS - 0wL Operational Security

![GitHub Repo stars](https://img.shields.io/github/stars/R3v4N/owl-ops?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/R3v4N/owl-ops?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/R3v4N/owl-ops?style=for-the-badge)
![MIT License](https://img.shields.io/github/license/R3v4N/owl-ops?style=for-the-badge)

## **We Hunt in the Shadows.**  

0wL OPS is a **powerful Bash-based offensive security toolkit** designed for:  
✅ **Red Team Operators** → Pre-exploitation recon, initial access, lateral movement.  
✅ **Penetration Testers** → Active & passive scanning, privilege escalation.  
✅ **Bug Bounty Hunters** → OSINT, web attack surface mapping, subdomain discovery.  
✅ **Forensic Analysts** → Threat hunting, adversary simulation.  

🦉 **0wL OPS automates reconnaissance, network analysis, exploitation, and persistence** in a highly modular and customizable way.

---

## Features  

| **Category**             | **Features** |
|--------------------------|-------------|
| **Reconnaissance** | Google Hacking, DNS Recon, Metadata Extraction, WHOIS & Passive DNS |
| **Network Scanning** | Nmap, Netcat, ARP Scanning, Wireless Attacks |
| **Exploitation** | Bash & Vim Escape, Rbash Breakouts, Man-in-the-Middle Attacks |
| **Lateral Movement** | Network Discovery, Windows Privilege Escalation, SMB Enumeration |
| **Post-Exploitation** | OS Credential Dumping, Windows/Linux Command References |
| **Forensics & Defense** | Threat Hunting, File Integrity Checking, System Log Analysis |
| **Logging & Output** | Structured logs for later review & reporting |

---

## Installation  

1. **Clone the repo**  

   ```bash
   git clone https://github.com/R3v4N/0wL-OPS.git
   cd 0wL-OPS
   chmod +x 0wlops.sh
   ```

2. **Run the script**

    ```bash
    ./0wlops.sh
    ```

---

## Usage

### Interactive Mode

Launch the main menu to navigate through available tools:

```bash
./0wlops.sh
```

### Fast Mode (Direct Execution)

Run a specific function directly:

```bash
./0wlops.sh <option>
```

Example:

```bash
./0wlops.sh 12

```

### Help Menu

```bash
./0wlops.sh -h

```

---

## Module Descriptions

### Reconnaissance & OSINT

- **Google Hacking:** Finds sensitive data indexed in search engines.
- **WHOIS & Passive DNS:** Gathers domain info and historical DNS data.
- **Metadata Extraction:** Extracts hidden metadata from documents.

### Network Scanning

- **ARP Scanning:** Identifies live hosts on the local network.
- **Nmap Discovery:** Comprehensive network scanning & fingerprinting.
- **Netcat Port Scanning:** Quick manual TCP scanning for reconnaissance.

### Exploitation & Evasion

- **Vim Escape:** Breaks out of restricted shells using Vim.
- **Rbash Escape:** Techniques to escape restricted shells.
- **MITM Attacks:** Man-in-the-middle attack simulation.

### Post-Exploitation & Forensics

- **Windows/Linux Command Cheatsheets:** Essential command-line references.
- **Credential Extraction:** Collects stored system credentials.
- **Threat Hunting:** Log analysis & detection of adversary activity.

## Legal Disclaimer

**0wL OPS is intended for legal security testing and research purposes only.**
Unauthorized use on systems without explicit permission is strictly prohibited.

---

## License

This project is licensed under the MIT License.
Feel free to modify and use, **but use responsibly.**

---

## Contributing

Want to improve 0wL OPS? Fork the repo, submit a PR, or open an issue!

**GitHub Repo**: https://github.com/R3v4N/0wL-OPS
**Contact:** R3v4N aka 0wL (jpgress@gmail.com)