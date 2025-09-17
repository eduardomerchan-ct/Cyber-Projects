# Cyber-Projects
Aspiring Cyber Security Professional. This will contain Folders that expand through different skills and will be reporting on all of projects in detail

Project 1#  Kali Linux & Metasploitable 2 Vulnerabilty Scanning 

Step 1:
Discover Metasploitable 2 VM and Performed Pinging to confirm its activeness.:
<img width="549" height="181" alt="image" src="https://github.com/user-attachments/assets/b341826f-9281-47f1-a768-d255e1f5cb04" />

This image shows that 3 packets were sent and were received, Confirming that the Metasploitable Vm is active on same network. 

Step 2: Perform Vulnerability Scans on network Using Nmap.
-Used nmap to scan the Ip addr:192.16.56.102 in stealth mode
-Used the command -sS
-Allowed me to identify open ports on the Vm that could be potentially be exploitated.

Starting Nmap 7.95 at 2025-09-16 23:17 EDT 

Nmap Scan report for IP addr: 192.168.56.102

Showed the Following Report:

<img width="524" height="365" alt="image" src="https://github.com/user-attachments/assets/060ff6f4-0df4-43c6-a63b-5d2fa89bc06b" />

The following important ports are reported as open:

-21/tcp open (FTP

-23/tcp open (Telnet):

-445/tcp (SMB)

This showed multiple ports that could be exploitaped by an attacker to gain aunthorized access and can lead to data breaches and system compromise.

The next scan that was used to further investigate was:

nmap --script vuln 192.162.56.102
 This scan searches for known vulnerabilities.

 Starting Nmap 7.95 at 2025-09-16 23:42 EDT showed the following Results:
 




