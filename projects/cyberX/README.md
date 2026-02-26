# Overview
  CyberX is a vulnerable virtual machine used during my cybersecurity training to simulate a real penetration testing engagement. The goal was to perform a full attack chain, including scanning,       
  enumeration, exploitation, privilege escalation, and post‑exploitation.
  
  The assessment revealed critical vulnerabilities in FTP, SSH, and WordPress that allowed full system compromise.

# Methodology
  Reconnaissance
  Nmap scanning
  Service enumeration (FTP, SSH, HTTP)
  Vulnerability analysis
  Exploitation
  Privilege escalation
  Post‑exploitation
  Reporting

# Attack Surface (Nmap)
  Port	Service	Version
  21	FTP	ProFTPD 1.3.3c
  22	SSH	OpenSSH 7.2p2
  80	HTTP	Apache 2.4.18

# Main Findings
**  ProFTPD Backdoor RCE → Remote code execution as root
**  Weak SSH Credentials → Direct login and privilege escalation
**  Weak WordPress Admin Authentication → Full dashboard control
**  Each vulnerability allowed unauthorized access and full system compromise.

# Tools Used
  Nmap
  Metasploit
  Hydra
  Gobuster
  WPScan
  curl
  Linux command‑line tools

# Result
  The CyberX machine was fully compromised through three independent attack vectors. The environment requires strong authentication policies, service updates, and improved configuration.
  
# Conclusion
  This project demonstrates practical experience in identifying and exploiting real vulnerabilities, performing privilege escalation, and documenting findings in a structured penetration testing report.
