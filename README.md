# Cybersecurity Security Architecture & Vulnerability Assessment

## Overview

This repository contains the implementation and documentation of two cybersecurity tasks focused on **Security Architecture Design** and **Vulnerability Assessment**. The project demonstrates the application of cybersecurity principles to protect business-critical assets and identify security weaknesses in a vulnerable target machine.

## Task 01: Security Architecture

The first task presents a security architecture for a large organization and discusses industry best practices for protecting business-critical data. It covers:

* Security architecture design
* Network segmentation
* Identity and Access Management (IAM)
* Multi-Factor Authentication (MFA)
* Firewalls and Intrusion Detection/Prevention Systems (IDS/IPS)
* Data encryption (at rest and in transit)
* Backup and disaster recovery strategies
* Security monitoring and logging
* Vulnerability management
* Security awareness and compliance

The objective is to design a secure infrastructure that ensures the confidentiality, integrity, and availability (CIA) of organizational data.

---

## Task 02: Vulnerability Assessment

The second task demonstrates a vulnerability assessment using a controlled penetration testing environment.

### Lab Setup

* **Attacker Machine:** Kali Linux
* **Target Machine:** Metasploitable 2
* **Scanning Tool:** Nmap

### Activities Performed

* Created a virtual network containing Kali Linux and Metasploitable.
* Performed host discovery and comprehensive port scanning using Nmap.
* Identified open services and vulnerable ports.
* Analyzed the top five exposed ports and discussed the security risks associated with each service.
* Included screenshots of the scan results with appropriate captions.

### Ports Analyzed

Examples include:

* FTP (21)
* SSH (22)
* Telnet (23)
* HTTP (80)
* SMB (445)

For each port, the repository explains:

* Service running
* Common vulnerabilities
* Potential attack scenarios
* Security recommendations

---

## Tools Used

* Kali Linux
* Metasploitable 2
* Nmap
* VirtualBox / VMware
* GitHub

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Designing secure enterprise architectures
* Performing vulnerability assessments
* Network reconnaissance using Nmap
* Identifying exposed services and security risks
* Understanding common attack vectors
* Documenting cybersecurity findings professionally

---

## Disclaimer

This project was conducted in a controlled virtual lab environment for educational purposes only. The techniques demonstrated should only be used on systems for which explicit authorization has been granted.

---

## Repository Structure

```text
├── Task-01-Security-Architecture/
│   ├── Report.pdf
│   └── Architecture-Diagram.png
│
├── Task-02-Vulnerability-Assessment/
│   ├── Nmap-Scan-Results.pdf
│   ├── Screenshots/
│   └── Analysis.pdf
│
└── README.md
```

---

## Author

**Shiza Nawaz**

Cybersecurity Student | Ethical Hacking | Penetration Testing | Network Security
