# 🔍 Full Reconnaissance & Information Gathering

### OSINT | Passive Reconnaissance | DNS Analysis | Google Dorking

A cybersecurity reconnaissance project focused on identifying publicly available information about a target organization using Open Source Intelligence (OSINT), Google Dorking, and DNS enumeration techniques.

The objective of this project is to understand how attackers gather publicly accessible information before conducting further security assessments and how organizations can reduce their external attack surface.

---

## 📌 Project Overview

Reconnaissance is one of the initial phases of ethical hacking and penetration testing.

In this project, passive reconnaissance techniques were used to collect publicly available information about the target domain:

**Target Domain:** `wscubetech.com`

The assessment focused on discovering publicly visible information, including:

- Domain and DNS information.
- Publicly indexed documents.
- Email addresses.
- Login and administration page URLs.
- Subdomains.
- Website technology information.
- Publicly available organizational information.

The findings were documented and evaluated to understand potential security risks.

---

## 🎯 Project Objectives

- Understand the reconnaissance phase of ethical hacking.
- Perform passive information gathering.
- Explore OSINT investigation techniques.
- Identify publicly indexed information using Google Dorking.
- Understand DNS records and domain information.
- Discover publicly visible subdomains.
- Identify potential information disclosure risks.
- Prepare a reconnaissance assessment report.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Google Search | Public information discovery |
| Google Dorking | Advanced search-based information gathering |
| OSINT Framework | OSINT resource discovery |
| nslookup | DNS queries |
| WHOIS | Domain registration information |
| dig | DNS record investigation |
| Have I Been Pwned | Public breach exposure checks |
| SynapsInt | Domain and host information |
| Domain Dossier | Domain and IP information |

---

## 🔬 Methodology

The project followed a structured reconnaissance methodology.

### 1. Passive Reconnaissance

Collected publicly available information without directly interacting with the target infrastructure.

### 2. DNS Information Gathering

Investigated DNS records to understand domain infrastructure.

Records examined:

- A Record
- MX Record
- TXT Record

### 3. Google Dorking

Used advanced Google search operators to discover publicly indexed resources.

Queries used:

```text
site:wscubetech.com
```

```text
site:wscubetech.com filetype:pdf
```

```text
site:wscubetech.com filetype:doc
```

```text
site:wscubetech.com inurl:login
```

```text
site:wscubetech.com inurl:admin
```

### 4. OSINT Investigation

Used publicly available OSINT resources to investigate:

- Domain information.
- Host information.
- Publicly exposed email information.
- Available infrastructure details.

### 5. Risk Assessment

Evaluated the collected information to identify potential security concerns and recommend appropriate defensive measures.

---

## 📊 Key Findings

The following findings were documented during the assessment.

| Category | Observation |
|---|---|
| DNS Information | A, MX and TXT records investigated |
| Public Documents | Publicly indexed PDF and DOC searches performed |
| Login Pages | Login-related URLs investigated |
| Admin Pages | Admin-related URLs investigated |
| Email Exposure | Public email information identified |
| Subdomains | blog.wscubetech.com and courses.wscubetech.com identified in the report |
| Technology Information | Web server and technology information investigated |

**Note:** These are observations from the submitted assessment report, not independently verified current findings.

---

## 🚨 Potential Security Risks

### 1. Publicly Exposed Documents

Publicly accessible documents may unintentionally disclose organizational information.

**Potential Impact:** Information disclosure.

### 2. Discoverable Login Pages

Publicly indexed login pages may attract automated login attempts.

**Potential Impact:** Increased exposure to credential attacks.

### 3. Public Email Exposure

Publicly available email addresses may be collected by spammers and malicious actors.

**Potential Impact:** Phishing and spam campaigns.

### 4. Subdomain Exposure

Publicly discoverable subdomains increase the number of assets that an organization should monitor.

**Potential Impact:** An improperly secured subdomain could introduce security risks.

### 5. Technology Disclosure

Publicly identifiable technologies can help attackers understand an organization's technology environment.

**Potential Impact:** Increased exposure to technology-specific attacks.

---

## 🛡️ Security Recommendations

Based on the identified risk categories, the following defensive recommendations are proposed:

- Review publicly accessible documents for confidential information.
- Implement multi-factor authentication on administrative accounts.
- Apply rate limiting and account lockout protections where appropriate.
- Monitor publicly exposed email addresses.
- Maintain an updated inventory of subdomains.
- Regularly review DNS configurations.
- Keep web servers and frameworks updated.
- Perform periodic external attack surface assessments.
- Review publicly exposed services and administrative interfaces.

---

## 📁 Project Documentation

The repository includes the reconnaissance assessment report.

```text
Reconnaissance-Project/
│
├── README.md
│
├── Documentation/
│   └── Reconnaissance_Report.pdf
│
├── Screenshots/
│   ├── DNS_Analysis/
│   ├── Google_Dorking/
│   ├── OSINT/
│   └── Information_Gathering/
│
└── LICENSE
```

*The folder structure above is a suggested repository organization.*

---

## 📚 Skills Demonstrated

- Open Source Intelligence (OSINT)
- Passive Reconnaissance
- Google Dorking
- DNS Enumeration
- Domain Information Analysis
- Information Gathering
- Attack Surface Awareness
- Security Risk Identification
- Technical Documentation

---

## ⚠️ Disclaimer

This project was conducted for educational purposes as part of cybersecurity learning.

The assessment focuses on passive reconnaissance and publicly available information.

No unauthorized access, exploitation, or disruption of target systems is intended or claimed.

The findings represent observations recorded during the assessment on 27 October 2026 and should not be interpreted as independently verified current vulnerabilities.

---

## 👨‍💻 Author

**Aditya Kashinath Bagade**

Cybersecurity Student | Junior Security Analyst

**Project:** Full Reconnaissance & Information Gathering

**Date:** 27 October 2026

---

⭐ If you find this project useful for learning cybersecurity and OSINT, consider giving the repository a star.
