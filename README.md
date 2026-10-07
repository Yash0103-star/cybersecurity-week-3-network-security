# Week 3 Network Security Assessment
**DG Intern Hub | Cybersecurity Internship**

## Overview
Comprehensive network security assessment of authorized lab using Nmap and Wireshark.

## Lab Environment
- **Network:** 192.168.174.0/24
- **Hosts:** 4 active systems (Kali Linux, Ubuntu, Gateway)
- **Tools:** Nmap 7.99, Wireshark, Ubuntu/Kali Linux

## Tasks Completed
✅ Task 7: Network Discovery
✅ Task 8: Advanced Nmap Assessment  
✅ Task 9: Wireshark Traffic Capture
✅ Task 10: Nmap + Wireshark Investigation
✅ Task 11: Advanced Traffic Investigation
✅ Task 12: Vulnerability Assessment
✅ Task 13: Security Hardening
✅ Task 14: Final Security Assessment

## Key Findings
**6 Security Vulnerabilities:**
- 4 Medium Risk: DNS exposure, NTP access, open high ports, ARP weakness
- 2 Low Risk: mDNS/LLMNR, missing DNSSEC

## Hardening Actions
1. ✅ DNS Restricted to lab network (firewall rule)
2. ✅ NTP Restricted to lab network (firewall rule)
3. ✅ mDNS/LLMNR Disabled (systemctl)

**Result:** Risk reduced MEDIUM → LOW

## Recommendations
1. Document high-numbered port services
2. Implement Dynamic ARP Inspection (DAI)
3. Enable DNSSEC validation
4. Network segmentation with VLANs
5. Continuous monitoring and logging

## Files
- `Week-3-DG-Intern-Hub-Assessment.pdf` - Complete report (20+ pages)
- `/evidence/` - Wireshark screenshots + Nmap results
- `README.md` - This file

## Submission
**Date:** 7 October 2026  
**Analyst:** Yash Panchal  
**Program:** DG Intern Hub - Cybersecurity  
**Status:** ✅ COMPLETE
