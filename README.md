# Cybersecurity Week 3 – Network Security Assessment

## Overview
This repository contains the work completed for Week 3 of the Cybersecurity Internship. The practical focused on network security assessment, network discovery, service enumeration, traffic analysis, vulnerability assessment, and security hardening in a controlled virtual lab environment.

## Objectives
- Discover active hosts using Nmap
- Identify open ports and running services
- Perform advanced Nmap scanning
- Capture and analyse network traffic using Wireshark
- Identify potential security vulnerabilities
- Classify identified risks
- Apply security-hardening measures
- Compare the security configuration before and after hardening

## Tools Used
- Nmap
- Wireshark
- Kali Linux
- VMware Workstation
- Windows/Linux Virtual Machines
- draw.io / diagrams.net

## Repository Structure
- `01-Nmap/` – Nmap scan outputs and screenshots
- `02-Wireshark/` – PCAP capture and Wireshark screenshots
- `03-Vulnerability-Assessment/` – Vulnerability assessment evidence
- `04-Hardening/` – Before and after hardening evidence
- `Network-Diagram/` – Network topology diagram
- `Week-3-Report.pdf` – Detailed practical report
- `Week-3-Presentation.pptx` – Week 3 presentation

## Key Finding
The Nmap vulnerability assessment identified a potential Slowloris vulnerability (CVE-2007-6750) associated with the HTTP service. The finding was reported as "LIKELY VULNERABLE" and classified as Medium Risk based on the available evidence.

## Network Traffic Analysis
Wireshark was used to analyse HTTP, DNS, ARP and other network traffic captured within the controlled lab environment. The packet capture is included in the `02-Wireshark/PCAP/` folder.

## Scope
All security testing was performed only within the authorized virtual laboratory environment for educational purposes.

## Conclusion
The practical provided hands-on experience in network reconnaissance, service enumeration, packet analysis, vulnerability assessment, risk classification, and security hardening.