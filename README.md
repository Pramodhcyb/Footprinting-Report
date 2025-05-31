# Footprinting-Report
This repository contains a comprehensive report on Footprinting and Reconnaissance in the context of ethical hacking. It includes step-by-step documentation of the process, sample findings, and illustrative images. The report is structured for clarity and practical use in cybersecurity assessments.

footprinting-reconnaissance-report/
├── README.md
├── images/
│   ├── google-hacking-example.png
│   ├── netcraft-site-report.png
│   ├── dnsdumpster-results.png
│   └── social-network-footprinting.png
└── report/
    └── footprinting-reconnaissance.md
# Footprinting and Reconnaissance: Ethical Hacking Report

This repository documents the process and findings of a simulated ethical hacking engagement, focusing on the *Footprinting and Reconnaissance* phase. The report follows standard penetration testing methodology and includes screenshots for reference.

## Overview

Footprinting and reconnaissance are the initial steps in ethical hacking, aimed at gathering as much information as possible about a target organization without actively engaging its systems. This information helps assess the organization's security posture and identify potential attack vectors.

## Objectives

- Collect organization, network, and system information
- Demonstrate passive and active footprinting techniques
- Use publicly available tools and resources
- Document findings with screenshots

## Methodology

### 1. **Defining Scope and Rules of Engagement**
- Confirmed with management the systems and data in-scope
- Established rules of engagement to ensure legal and ethical compliance

### 2. **Information Gathering Techniques**

#### a. Passive Footprinting
- **Search Engines & Google Hacking:** Used advanced operators to find sensitive files and login portals  
  ![Google Hacking Example](images/google-hacking-example.png)
- **Internet Research Services:** Leveraged Netcraft and DNSdumpster to map domains, subdomains, and DNS infrastructure  
  ![Netcraft Site Report](images/netcraft-site-report.png)  
  ![DNSdumpster Results](images/dnsdumpster-results.png)
- **Social Networking Sites:** Gathered employee details, roles, and contact information  
  ![Social Network Footprinting](images/social-network-footprinting.png)

#### b. Active Footprinting
- **Whois Lookups:** Identified domain ownership and registration details
- **DNS Queries:** Used `nslookup` and online tools to enumerate DNS records
- **Traceroute:** Mapped network paths to target systems

### 3. **Documentation**
- All findings, screenshots, and data are included in the `report/footprinting-reconnaissance.md` file.

## Key Findings

- **Organization Info:** Employee names, roles, email formats, office locations
- **Network Info:** Domain names, subdomains, IP addresses, DNS server details
- **System Info:** Web server OS, hosting provider, SSL certificate details

## Tools Used

- Google (advanced operators)
- Netcraft
- DNSdumpster
- Whois lookup tools
- Social media platforms (LinkedIn, Twitter)
- nslookup, traceroute

## Images

All screenshots referenced in the report are in the `/images` directory.

## Usage

This repository serves as a reference for security professionals learning about the reconnaissance phase of ethical hacking or preparing for penetration testing certifications.

---

*For educational and authorized testing purposes only.*
