# Wireshark Network Analysis Lab (SOC Project)

## Overview
This project demonstrates practical network traffic analysis using Wireshark in a Linux environment. The goal was to simulate real-world SOC (Security Operations Center) monitoring and identify key network activities such as DNS queries, HTTP requests, and TCP handshakes.

## Tools Used
- Wireshark
- Ubuntu (VirtualBox)
- Firefox (for traffic generation)

## Key Findings
- Captured DNS queries to external domains (e.g., detectportal.firefox.com)
- Observed TCP 3-way handshake (SYN, SYN-ACK, ACK)
- Analysed HTTP GET requests and server responses (200 OK)
- Identified encrypted TLS traffic over port 443

## Skills Demonstrated
- Packet capture and filtering
- Protocol analysis (DNS, TCP, HTTP, TLS)
- Traffic investigation and interpretation
- SOC-style reporting

## Report
You can view the full report here:
[SOC Report PDF](./SOC_Report_With_Screenshots.pdf)

## What I Did
- Set up a virtual lab using Ubuntu in VirtualBox
- Installed and configured Wireshark
- Captured live network traffic
- Generated traffic using Firefox
- Analysed DNS, TCP, HTTP, and TLS activity
  
 ## Sample Analysis
![Wireshark Capture](./screenshot1.png) 
