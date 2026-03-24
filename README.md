# 0wL OPS - 0wL Operational Security

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)  
![Bash](https://img.shields.io/badge/Bash-Scripting-1f425f.svg)
![Version](https://img.shields.io/badge/Version-1.27.030--VADER-red.svg)

## **We Hunt in the Shadows.**  

0wL OPS is a **powerful Bash-based offensive security toolkit** designed for:  
✅ **Red Team Operators** → Pre-exploitation recon, initial access, lateral movement.  
✅ **Penetration Testers** → Active & passive scanning, privilege escalation.  
✅ **Bug Bounty Hunters** → OSINT, web attack surface mapping, subdomain discovery.  
✅ **Forensic Analysts** → Threat hunting, adversary simulation.  

🦉 **0wL OPS automates reconnaissance, network analysis, exploitation, and persistence** in a highly modular and customizable way, structured around the **MITRE ATT&CK framework**.

---

## Features  

| **Tactic (MITRE ATT&CK)**                | **Modules**                                                                                                                |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Reconnaissance** TA0043                 | Google Hacking, DNS Recon, Reverse DNS, WHOIS & Passive DNS, Metadata Extraction, HTML Parsing                             |
| **Resource Development** TA0042           | DNS Zone Transfer, Subdomain Takeover                                                                                      |
| **Initial Access** TA0001                 | Wireless Access Operations                                                                                                 |
| **Privilege Escalation** TA0004           | Root Password Reset, JALESC Enumeration, Vim Shell Escape, Restricted Bash Escape                                          |
| **Credential Access** TA0006              | Man-in-the-Middle Simulation (T1557)                                                                                       |
| **Discovery** TA0007                      | Nmap, Netcat, Bash Socket Scan, ARP Scan, SMB Enumeration, HTTP(S) Banner Grabbing, System Info, File & Directory Analysis |
| **Lateral Movement** TA0008               | Internal Recon Agent Deployment (ARP-based)                                                                                |
| **Operator Utilities**                    | Network Commands Quick Ref, Windows Commands Quick Ref, WSL ↔ VirtualBox Routing                                           |

---

## Installation  

1. **Clone the repo**  

   ```bash
   git clone https://github.com/JPGress/owl-ops.git
   cd owl-ops
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
./0wlops.sh 101   # Metadata Analysis (Reconnaissance)
./0wlops.sh 801   # Adversary-in-the-Middle Simulation (Credential Access)
./0wlops.sh 901   # Netcat Port Scan (Discovery)
```

### Help Menu

```bash
./0wlops.sh -h
```

---

## Module Reference

> Option numbers follow a **centesimal scheme** — each hundred maps to one MITRE ATT&CK tactic.

### [+] RECONNAISSANCE [TA0043]

| Option | Module                                                 | MITRE Technique |
| ------ | ------------------------------------------------------ | --------------- |
| 101    | Gather Victim Identity Information - Document Metadata | T1589 / T1592   |
| 102    | Gather Victim Network Information - Whois & DNS        | T1590           |
| 103    | Gather Victim Network Information - Reverse DNS Lookup | T1590.001       |
| 104    | Gather Victim Network Information - DNS Recon          | T1590.001       |
| 105    | Search Engine OSINT - Target Profiling                 | T1593.001       |
| 106    | Gather Victim Web Presence - HTML Parsing *(DISABLED)* | —               |

### [+] RESOURCE DEVELOPMENT [TA0042]

| Option | Module                                                   | MITRE Technique |
| ------ | -------------------------------------------------------- | --------------- |
| 201    | Exploit Public-Facing Infrastructure - DNS Zone Transfer | T1584.002       |
| 202    | Subdomain Takeover Assessment                            | T1583.002       |

### [+] INITIAL ACCESS [TA0001]

| Option | Module                             | MITRE Technique |
| ------ | ---------------------------------- | --------------- |
| 301    | Wireless Access Operations Toolkit | T1566           |

### [+] PRIVILEGE ESCALATION [TA0004]

| Option | Module                                            |
| ------ | ------------------------------------------------- |
| 601    | Local Access Recovery - Root Password Reset Guide |
| 602    | Privilege Escalation Enumeration - JALESC         |
| 603    | Escape to Shell - Vim Techniques                  |
| 604    | Escape to Shell - Restricted Bash Techniques      |

### [+] CREDENTIAL ACCESS [TA0006]

| Option | Module                             | MITRE Technique |
| ------ | ---------------------------------- | --------------- |
| 801    | Adversary-in-the-Middle Simulation | T1557           |

### [+] DISCOVERY [TA0007]

| Option | Module                                               | MITRE Technique |
| ------ | ---------------------------------------------------- | --------------- |
| 901    | Network Service Discovery - Netcat Port Scan         | T1046           |
| 902    | Network Service Discovery - Bash Socket Scan         | T1046           |
| 903    | Service Discovery - HTTP(S) Banner Grabbing          | T1046           |
| 904    | SMB Service Enumeration *(UNSTABLE)*                 | —               |
| 905    | System Information Discovery - Linux                 | T1082           |
| 906    | File and Directory Discovery - Attack Surface Review | T1083           |
| 907    | File and Directory Discovery - Quick Reference       | T1083           |
| 908    | Network Service Discovery - Nmap Scan                | T1046           |
| 909    | Network Neighbor Discovery - ARP Scan                | T1046 / T1016   |

### [+] LATERAL MOVEMENT [TA0008]

| Option | Module                          |
| ------ | ------------------------------- |
| 1001   | Internal Recon Agent Deployment |

### [+] OPERATOR UTILITIES

| Option | Module                              |
| ------ | ----------------------------------- |
| 001    | Network Commands - Quick Reference  |
| 002    | Windows Commands - Quick Reference  |
| 003    | Enable WSL Routing to VirtualBox VM |
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

**GitHub Repo**: https://github.com/JPGress/owl-ops  
**Contact:** R3v4N aka 0wL (jpgress@gmail.com)