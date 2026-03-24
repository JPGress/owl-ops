# 0wL OPS - 0wL Operational Security

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)  
![Bash](https://img.shields.io/badge/Bash-Scripting-1f425f.svg)
![Version](https://img.shields.io/badge/Version-1.27.020--VADER-red.svg)

## **We Hunt in the Shadows.**  

0wL OPS is a **powerful Bash-based offensive security toolkit** designed for:  
✅ **Red Team Operators** → Pre-exploitation recon, initial access, lateral movement.  
✅ **Penetration Testers** → Active & passive scanning, privilege escalation.  
✅ **Bug Bounty Hunters** → OSINT, web attack surface mapping, subdomain discovery.  
✅ **Forensic Analysts** → Threat hunting, adversary simulation.  

🦉 **0wL OPS automates reconnaissance, network analysis, exploitation, and persistence** in a highly modular and customizable way, structured around the **MITRE ATT&CK framework**.

---

## Features  

| **Category (MITRE ATT&CK)**               | **Modules**                                                                                                                |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Reconnaissance**                        | Google Hacking, DNS Recon, Reverse DNS, WHOIS & Passive DNS, Metadata Extraction, HTML Parsing                             |
| **Resource Development / Initial Access** | DNS Zone Transfer, Subdomain Takeover, Wireless Access Operations                                                          |
| **Discovery**                             | Nmap, Netcat, Bash Socket Scan, ARP Scan, SMB Enumeration, HTTP(S) Banner Grabbing, System Info, File & Directory Analysis |
| **Credential Access / Collection**        | Man-in-the-Middle Simulation (T1557)                                                                                       |
| **Privilege Escalation**                  | Root Password Reset, JALESC Enumeration, Vim Shell Escape, Restricted Bash Escape                                          |
| **Lateral Movement / Internal Recon**     | Internal Recon Agent Deployment (ARP-based)                                                                                |
| **Operator Utilities**                    | Network Commands Quick Ref, Windows Commands Quick Ref, WSL ↔ VirtualBox Routing                                           |

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

Run a specific module directly by its option number:

```bash
./0wlops.sh <option>
```

Example:

```bash
./0wlops.sh 107   # DNS Reconnaissance
./0wlops.sh 200   # Adversary-in-the-Middle Simulation
./0wlops.sh 303   # JALESC - Privilege Escalation Enumeration
```

### Help Menu

```bash
./0wlops.sh -h
```

---

## Module Reference

### [+] RECONNAISSANCE

| Option | Module                                                 | MITRE Technique |
| ------ | ------------------------------------------------------ | --------------- |
| 102    | Gather Victim Host Information - Search Engines        | T1593.001       |
| 103    | Gather Victim Identity Information - Document Metadata | T1589 / T1592   |
| 106    | Gather Victim Network Information - Reverse DNS Lookup | T1590.001       |
| 107    | Gather Victim Network Information - DNS Recon          | T1590.001       |
| 109    | Gather Victim Network Information - Whois & DNS        | T1590           |
| 110    | Gather Victim Web Presence - HTML Parsing *(DISABLED)* | —               |

### [+] RESOURCE DEVELOPMENT / INITIAL ACCESS

| Option | Module                                                   | MITRE Technique |
| ------ | -------------------------------------------------------- | --------------- |
| 104    | Exploit Public-Facing Infrastructure - DNS Zone Transfer | T1190           |
| 105    | Subdomain Takeover Assessment                            | —               |
| 500    | Wireless Access Operations Toolkit                       | —               |

### [+] DISCOVERY

| Option | Module                                               | MITRE Technique |
| ------ | ---------------------------------------------------- | --------------- |
| 100    | Network Service Discovery - Netcat Port Scan         | T1046           |
| 101    | Network Service Discovery - Bash Socket Scan         | T1046           |
| 108    | Service Discovery - HTTP(S) Banner Grabbing          | T1046           |
| 201    | SMB Service Enumeration *(UNSTABLE)*                 | —               |
| 203    | System Information Discovery - Linux                 | T1082           |
| 300    | File and Directory Discovery - Attack Surface Review | T1083           |
| 301    | File and Directory Discovery - Quick Reference       | T1083           |
| 600    | Network Service Discovery - Nmap Scan                | T1046           |
| 601    | Network Neighbor Discovery - ARP Scan                | T1046 / T1016   |

### [+] CREDENTIAL ACCESS / COLLECTION

| Option | Module                             | MITRE Technique |
| ------ | ---------------------------------- | --------------- |
| 200    | Adversary-in-the-Middle Simulation | T1557           |

### [+] PRIVILEGE ESCALATION

| Option | Module                                            |
| ------ | ------------------------------------------------- |
| 302    | Local Access Recovery - Root Password Reset Guide |
| 303    | Privilege Escalation Enumeration - JALESC         |
| 400    | Escape to Shell - Vim Techniques                  |
| 401    | Escape to Shell - Restricted Bash Techniques      |

### [+] LATERAL MOVEMENT / INTERNAL RECON

| Option | Module                          |
| ------ | ------------------------------- |
| 602    | Internal Recon Agent Deployment |

### [+] OPERATOR UTILITIES

| Option | Module                              |
| ------ | ----------------------------------- |
| 202    | Network Commands - Quick Reference  |
| 501    | Windows Commands - Quick Reference  |
| 001    | Enable WSL Routing to VirtualBox VM |
| 000    | Exit                                |

---

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