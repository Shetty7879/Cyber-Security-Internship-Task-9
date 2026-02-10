# Cyber Security Internship – Task 9

## Task Title
Network Vulnerability Scanning Using Nmap

## Objective
To perform a basic network vulnerability scan on a local system using Nmap, identify open ports and services, and analyze potential security risks.

## Tool Used
- Nmap (Network Mapper)

## Target
- Localhost (127.0.0.1)

## Scan Performed
A basic TCP port scan was conducted on the local system using the following command:
nmap 127.0.0.1

## Key Findings
- The host was active and reachable
- Out of 1000 TCP ports scanned, 996 ports were closed
- Open ports identified:
  - 135/tcp – msrpc (Windows Remote Procedure Call)
  - 445/tcp – microsoft-ds (SMB file sharing)
  - 1755/tcp – wms (Windows Media Service)
  - 1761/tcp – landesk-rc (Remote management service)

## Risk Analysis
- Open ports increase the system attack surface
- SMB services are commonly targeted by attackers
- Remote management services may expose the system if not secured

## Recommendations
- Disable unnecessary services
- Close unused ports
- Use firewall rules
- Keep the operating system updated
- Monitor network activity regularly

## Deliverables
- Network Vulnerability Scanning Report (PDF)
## Author
Prajwal S Shetty
