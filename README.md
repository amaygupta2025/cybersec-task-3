# cybersec-task-3
## Task 3: Perform a Basic Vulnerability Scan on Your PC.

# Nessus Vulnerability Scan

## Tool Used:
**Nessus Essentials** (Free vulnerability scanner by Tenable)

## Scan Target:
Local PC with IP: `192.168.137.1`

## Objective:
Perform a vulnerability scan to identify known risks and weaknesses on the local system.

## Summary of Findings:
- **Total Vulnerabilities Detected:** 82
- **Top Issues:**
  1. SSL Certificate Cannot Be Trusted (Medium, Port 8834)
  2. SMB Signing Not Required (Medium, Port 445)
  3. OS Security Patch Assessment Not Available (Informational)
  4. CPE Enumeration (Informational)
  5. Scan Metadata (Informational)

## Description:
This scan identified a number of medium and informational vulnerabilities on the system. The most significant issues involve SSL misconfiguration and weak SMB signing settings that may expose the system to man-in-the-middle attacks.

## Recommendations:
- Use a valid and trusted SSL certificate.
- Enforce SMB signing to prevent tampering.
- Ensure Nessus has the necessary credentials to check OS patch levels.
- Review informational findings to understand software footprint.

##  Full Report:
See nessus_scan_report.txt for complete details of all 82 findings.



