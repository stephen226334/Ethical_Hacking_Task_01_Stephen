# Ethical Hacking Task 01 – Information Gathering & Reconnaissance

## Internship

**White Band Associates – Cyber Security Internship**

---

# Student Information

**Name:** Stephen J

**Task:** Ethical Hacking Task 01

**Topic:** Information Gathering & Reconnaissance

**Target Website:** Amazon.com

**Website URL:** https://www.amazon.com

---

# Objective

The objective of this task is to understand the reconnaissance (information gathering) phase of ethical hacking by collecting publicly available information about a target website without interacting with or exploiting its systems.

---

# Tools Used

* WHOIS Lookup
* DNSChecker
* Wappalyzer
* SecurityHeaders.com
* Web Browser (Google Chrome)

---

# Task Performed

### Part A – Target Selection

* Selected Amazon.com as the target website.
* Recorded the website name, URL, and reason for selection.

### Part B – WHOIS Lookup

Collected:

* Domain Name
* Registrar
* Registration Date
* Expiry Date
* Name Servers
* Domain Status

### Part C – DNS Enumeration

Collected:

* A Record
* MX Record
* NS Record
* TXT Record

### Part D – Website Technology Identification

Identified:

* HTTP/3
* Amazon Web Services (AWS)
* Amazon CloudFront CDN
* Open Graph
* Tailwind CSS
* Other publicly detectable technologies

### Part E – HTTP Security Headers

Checked:

* Content-Security-Policy (CSP)
* X-Frame-Options
* X-Content-Type-Options
* Strict-Transport-Security (HSTS)
* Referrer-Policy

### Part F – Robots.txt & Sitemap Analysis

* Reviewed robots.txt
* Attempted to access sitemap.xml
* Recorded observations

---

# Folder Structure

```text
Ethical_Hacking_Task_01_StephenJ
│
├── Reconnaissance_Report.pdf
├── Research_Notes.txt
├── README.md
│
└── Screenshots
    ├── 01_Target_Website.png
    ├── 02_WHOIS_1.png
    ├── 03_WHOIS_2.png
    ├── 04_DNS_Records_1.png
    ├── 05_DNS_Records_2.png
    ├── 06_Website_Technology.png
    ├── 07_HTTP_Security_Headers_1.png
    ├── 08_HTTP_Security_Headers_2.png
    ├── 09_Robots_txt.png
    └── 10_Sitemap_xml.png
```

---

# Learning Outcomes

Through this task, I learned:

* The importance of reconnaissance in ethical hacking.
* How to collect publicly available information using passive techniques.
* How WHOIS provides domain registration details.
* How DNS records help understand domain configuration.
* How technology detection tools identify publicly visible web technologies.
* The role of HTTP security headers in protecting web applications.
* The purpose of robots.txt and sitemap.xml files.
* The importance of performing reconnaissance ethically without attempting unauthorized access.

---

# Conclusion

This task provided practical experience in passive reconnaissance by collecting publicly available information about Amazon.com. Various tools were used to gather domain details, DNS records, website technologies, security headers, and crawler-related files. The exercise demonstrated how reconnaissance helps security professionals understand a target's publicly exposed infrastructure before any security assessment while remaining within ethical and legal boundaries.

---

# Repository

This repository contains all required documentation, screenshots, research notes, and the reconnaissance report for Ethical Hacking Task 01.
