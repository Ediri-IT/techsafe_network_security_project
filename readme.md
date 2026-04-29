TechSafe Ltd: Network Security Hardening & Traffic Analysis

Domain: Network Security / Infrastructure Operations

Project Overview

As a Security Consultant for TechSafe Ltd, I was tasked with modernizing a 
"flat" network into a secure, subnetted architecture and implementing 
endpoint security policies. This project demonstrates the ability to 
design network topologies, analyze live traffic for compliance, and harden 
systems against insecure protocols.

Technical Implementation
1. Network Segmentation & Design
Task: Transitioned the organization from a single broadcast domain to a 
structured 3-subnet architecture (Admin, Sales, and IT).
Skills: Calculated IP address ranges and subnet masks using CIDR notation 
to ensure efficient address allocation and department isolation.

3. Traffic Analysis (Wireshark)
Task: Performed deep packet inspection to verify that sensitive web 
traffic was being handled securely over HTTPS.
Analysis: Utilized advanced display filters to isolate TLS Handshakes and 
SNI (Server Name Indication) data, proving that encrypted connections to 
Wikipedia and Google were established correctly.

5. Firewall Policy Enforcement
Task: Hardened a Windows endpoint by blocking insecure, clear-text 
protocols.
Implementation: Created Outbound Firewall Rules in Windows Defender with 
Advanced Security to block:
             Port 21 (FTP): To prevent unencrypted file transfers.
             Port 80 (HTTP): To enforce a "Secure-by-Default" web 
standard.
Verification: Validated the security posture through "Before and After" 
connectivity testing.
 Skills & Tools
Protocols: TCP/IP, UDP, TLS/SSL, HTTP/HTTPS, FTP.
Tools: Wireshark, Windows Defender Firewall, Git/GitHub.
Concepts: Subnetting, Protocol Analysis (OSI Layers 3, 4, and 7), Least 
Privilege, Fault Isolation.
