# Vulnerability Assessment Report - testasp.vulnweb.com

## Project Overview

This repository contains a professional Vulnerability Assessment Report conducted on the publicly accessible website:

**Target Website**: http://testasp.vulnweb.com

The assessment was performed under a strict read-only and passive scope, meaning no exploitation, brute-force, or harmful testing was conducted.

The purpose of this project is to demonstrate practical cybersecurity auditing skills such as:

- Website security analysis
- Identifying common vulnerabilities
- Risk classification
- Professional report writing
- Security remediation recommendations

---

## Objective

To analyze a live public website for visible security weaknesses and prepare a business-style vulnerability assessment report.

---

## Scope & Ethics

### Allowed Activities

- Public page inspection
- Header analysis
- Browser Developer Tools review
- Passive scanning
- Basic reconnaissance
- Manual security review

### Not Allowed

- SQL Injection attacks
- Brute force attacks
- Login bypass attempts
- Exploitation
- Denial of Service
- Any harmful activity

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Browser DevTools | Inspect headers, requests |
| OWASP ZAP | Passive vulnerability scan |
| Nmap | Basic reconnaissance |
| Manual Review | Security observations |
| Canva / MS Word | Report preparation |

---

## Key Findings

### 1. Website Accessible Over HTTP
- Traffic not encrypted
- Risk of Man-in-the-Middle attacks

### 2. Missing Security Headers
- CSP missing
- HSTS missing
- X-Frame-Options missing

### 3. Server Information Disclosure
- Microsoft IIS/8.5 exposed
- ASP.NET disclosed

### 4. Public Disclosure of Vulnerable Features
- Site openly mentions SQL Injection & Directory Traversal

### 5. Potential Insecure Inputs
- Search/login/forum inputs may be unsafe

---

## Risk Summary

| Severity | Count |
|---------|------|
| High | 3 |
| Medium | 2 |
| Low | 0 |

---

## Recommendations

- Force HTTPS
- Add security headers
- Hide server banners
- Validate all user inputs
- Conduct regular vulnerability scans
- Keep systems updated
- Follow secure coding practices

---

## Repository Contents

- `README.md`
- `VULNERABILITY ASSESSMENT REPORT.pdf`
- `Supporting evidence/` files containing screenshots of the vulnerabilities found during the assessment.
  - `Screenshot (670).png`
  - `Screenshot 2026-04-17 231355.png`
  - `Screenshot 2026-04-17 231929.png`
  - `Screenshot 2026-04-17 231934.png`
  - `Screenshot 2026-04-17 233412.png`
  - `Screenshot 2026-04-17 235040.png`
  - `Screenshot 2026-04-17 235553.png`

## Screenshots

<img src="./Supporting evidence/Screenshot (670).png" width="800">
<img src="./Supporting evidence/Screenshot 2026-04-17 231355.png" width="800">
<img src="./Supporting evidence/Screenshot 2026-04-17 231929.png" width="800">
<img src="./Supporting evidence/Screenshot 2026-04-17 231934.png" width="800">
<img src="./Supporting evidence/Screenshot 2026-04-17 233412.png" width="800">
<img src="./Supporting evidence/Screenshot 2026-04-17 235040.png" width="800">
<img src="./Supporting evidence/Screenshot 2026-04-17 235553.png" width="800">