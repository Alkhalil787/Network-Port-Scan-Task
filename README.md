# Network-Port-Scan-Task
# Task 1: Scan Your Local Network for Open Ports

# Objective
Perform a basic network reconnaissance using Nmap to identify open ports on devices in my local network. This helps understand which services are exposed and what potential security risks exist.



1. Installed Nmap on Windows 10.
2. Found my local IP range using `ipconfig`. My IP was `192.168.3.11` so I scanned `192.168.3.0/24`.
3. Ran the command: `nmap -sS 192.168.3.0/24`
4. Recorded open ports and IPs in `scan_results.txt`.
5. Researched common services like HTTP (80), SSH (22), and FTP (21)
