# Week 2 – Penetration Testing
## Footprinting & Network Scanning

### Overview
This repository contains the practical work completed during Week 2 of my Cybersecurity and Ethical Hacking internship at Networkwalks.

The main objective was to understand the initial stages of penetration testing, including information gathering, website reconnaissance, DNS enumeration, and network scanning.

### Objectives
- Understand the fundamentals of footprinting and reconnaissance.
- Identify publicly available domain information.
- Analyze website technologies and HTTP response headers.
- Perform DNS enumeration.
- Detect Web Application Firewall (WAF) technologies.
- Discover active devices on a local network.
- Visualize network topology using Zenmap.

### Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Reconnaissance environment |
| WHOIS | Domain registration information |
| WhatWeb | Website technology fingerprinting |
| Nslookup | DNS resolution |
| cURL | HTTP response header analysis |
| Wafw00f | WAF detection |
| DNSRecon | DNS record enumeration |
| Zenmap | Network scanning and host discovery |
| Windows CMD | Local IP and network configuration |

### Practical Tasks

#### 1. Footprinting & Reconnaissance
Performed reconnaissance on the authorized target domain using Kali Linux.

Activities included:
- Collecting domain registration information using WHOIS.
- Identifying website technologies using WhatWeb.
- Resolving domain names using Nslookup.
- Inspecting HTTP response headers using cURL.
- Checking WAF protection using Wafw00f.
- Enumerating DNS records using DNSRecon.

#### 2. Network Scanning with Zenmap
Performed network discovery on my own local network.

Activities included:
- Identifying the local IP address and subnet using Windows CMD.
- Performing Ping Scans using Zenmap.
- Discovering active network devices.
- Identifying IP and MAC addresses.
- Generating a visual network topology.
- Exporting the topology report in PDF format.

### Key Learnings
- Understood how reconnaissance helps gather information before security testing.
- Gained practical experience with commonly used Kali Linux utilities.
- Learned how DNS records and website technologies can reveal infrastructure details.
- Understood the process of identifying active hosts on a network.
- Gained experience in network topology visualization.
- Learned to document findings and identify potential security risks.

### Repository Structure

```text
Week-2-Penetration-Testing/
│
├── README.md
│
├── Report/
│   └── Week-2-Penetration-Testing-Report.pdf
│
└── Evidence/
    ├── Footprinting/
    │   ├── WHOIS.png
    │   ├── WhatWeb.png
    │   ├── Nslookup.png
    │   ├── Curl.png
    │   ├── Wafw00f.png
    │   └── DNSRecon.png
    │
    └── Network-Scanning/
        ├── Zenmap-Scan.png
        └── Network-Topology.pdf
```

### Conclusion
Week 2 provided practical exposure to footprinting, reconnaissance, DNS enumeration, and network scanning. These exercises helped strengthen my understanding of how cybersecurity professionals gather information, identify network devices, and document security-related observations.

### Disclaimer
All activities were performed for educational purposes within authorized testing environments. Reconnaissance and scanning were restricted to systems and networks for which permission was available. Unauthorized testing is not encouraged.

---

**Program:** Cybersecurity & Ethical Hacking Internship  
**Organization:** Networkwalks  
**Week:** 02
