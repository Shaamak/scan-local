# Network Scan Task

## Overview
Scanned the local network using Nmap to identify active hosts, open ports, and running services.

## Files
- `scan_results.txt`: Nmap scan output
- `open_ports.csv`: List of detected open ports and services
- `open_ports_analysis.md`: Research and security analysis of open ports

## How to Reproduce
1. Install Nmap.
2. Find your local IP range.
3. Run:  
   `nmap -sS 192.168.1.0/24 -oN scan_results.txt`
4. Analyze results in the provided files.

## Key Points
- Common open ports: 22 (SSH), 80 (HTTP), 443 (HTTPS)
- Security risks and mitigations are summarized in `open_ports_analysis.md`
