

# Project 1: Kali Linux & Metasploitable 2 Vulnerability Scanning

# What this project is

A basic vulnerability assessment against Metasploitable 2, an intentionally vulnerable VM, using Kali Linux as the attacking machine. The goal was just to get real practice finding vulnerabilities and understanding the risk behind them.

# What you'll see in the walkthrough

- Confirming the target VM is up and reachable with a ping
- Running an Nmap stealth scan to find open ports and flag the risky ones (FTP, Telnet, SMB)
- Running a deeper vulnerability scan with Nmap's vuln script
- Hitting an error mid-scan, checking the firewall to rule it out as the cause
- Tracking the real issue down to scope, and fixing it
- A quick wrap-up on what I took away from the project

#Tools

- Attacker VM: Kali Linux
- Target VM: Metasploitable 2
- Hypervisor: Oracle VirtualBox
