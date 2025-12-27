 Information Gathering & Reconnaissance (Cybersecurity Project)

📌 Project Overview
This project demonstrates the Information Gathering & Reconnaissance phase of penetration testing, performed in a controlled and ethical lab environment. The objective was to identify publicly available information, exposed services, and the overall attack surface of a target system using industry-standard reconnaissance and OSINT techniques.
The assessment was conducted using Kali Linux as the attacker machine and OWASP Broken Web Applications (OWASPBWA) as the intentionally vulnerable target, both running as virtual machines in a bridged network setup.

Lab Environment
Host OS: Windows 10 / 11
Virtualization: Oracle VirtualBox
Attacker VM: Kali Linux
Target VM: OWASPBWA
Network Mode: Bridged Adapter
This setup ensures safe, isolated, and reproducible testing without targeting real-world systems.

Project Objectives
Perform ethical and legal reconnaissance on an authorized target
Identify exposed network services and web applications
Practice OSINT and passive reconnaissance techniques
Understand how attackers map an attack surface before exploitation
Document findings in a professional security assessment format

Tools & Techniques Used
Network & Port Scanning: Nmap
Directory Enumeration: Gobuster
Technology Fingerprinting: WhatWeb, Wappalyzer
Subdomain Enumeration: Sublist3r, Amass, Assetfinder
DNS Enumeration: dig, nslookup
Email Harvesting & OSINT: theHarvester
Search Engine Recon: Google Dorking

Reconnaissance Activities
The project included:
Connectivity verification and IP identification
WHOIS and reverse DNS analysis (private IP limitations explained)
Subdomain enumeration on safe public domains (example.com)
DNS record analysis (A, MX, NS, TXT, AXFR testing)
Web technology fingerprinting
Directory and file discovery revealing vulnerable applications such as DVWA, WebGoat, Mutillidae, Bodgeit, and phpMyAdmin
Port and service enumeration identifying HTTP, FTP, SSH, and MySQL services
Email harvesting and OSINT demonstrations on documentation domains
Social media and public footprint analysis

Deliverables
A detailed reconnaissance report documenting:
Methodology
Commands used 
Screenshots
Findings and interpretations
Challenges faced
Conclusion and security insights

Ethical Disclaimer
This project was conducted strictly for educational purposes in a controlled lab environment using intentionally vulnerable systems and safe documentation domains (OWASPBWA, example.com, iana.org).
No real organizations, systems, or data were targeted.

