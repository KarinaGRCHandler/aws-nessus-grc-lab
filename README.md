# aws-nessus-grc-lab
GRC lab using AWS, Nessus, and Excel to simulate vulnerability scanning and compliance reporting.
# 🛡️ GRC Lab – Vulnerability Reporting with Nessus & Excel

This project simulates a real-world GRC (Governance, Risk & Compliance) scenario using AWS, Nessus Essentials, and Excel. The goal is to demonstrate vulnerability identification, compliance mapping, and basic reporting for audit readiness.

## 🔧 Tools Used
- AWS EC2 (Ubuntu Server - Free Tier)
- Nessus Essentials (vulnerability scanner)
- Microsoft Excel (reporting & dashboard)

## 🎯 Objectives
- Deploy a cloud-hosted Ubuntu machine
- Run vulnerability scans using Nessus Essentials
- Export and analyze scan data in Excel
- Map findings to NIST 800-53 control families
- Create a simplified audit report

## 🧪 Method
1. Launch Ubuntu EC2 instance in AWS with open ports (22, 80, 443)
2. Scan the instance using Nessus Essentials
3. Export results as CSV
4. Import into Excel and build:
   - Vulnerability Summary tab
   - Compliance Dashboard tab
5. Write audit-style recommendations

## 📊 Example Findings (To Be Added)
| IP Address | Severity | Plugin ID | Plugin Name | Port |
|------------|----------|-----------|-------------|------|
| 3.123.456.78 | Critical | 19506 | SSL Medium Strength Cipher Suites Supported | 443 |

## 📋 Mapped Controls (NIST 800-53)
| Control | Area | Risk | Fix |
|--------|------|------|-----|
| AC-17 | Remote Access | Open SSH from any IP | Restrict access to internal IPs |
| SI-2 | Vulnerability Management | Outdated Ubuntu packages | Apply system updates |

## ✅ Outcome
This project demonstrates practical skills in vulnerability analysis, basic GRC mapping, and compliance reporting without needing complex enterprise tools.

## 📸 Lab Screenshots

### Excel Structure – Vulnerability Summary
![Excel Summary](screenshots/excel-structure-summary.png)

### Excel Structure – Compliance Dashboard
![Excel Dashboard](screenshots/excel-structure-dashboard.png)

### AWS EC2 Running Instance
![EC2 Instance](screenshots/Running%20Instance.png)

---

## 📝 Final Audit Summary

A Nessus Essentials scan was conducted on an Ubuntu EC2 instance hosted on AWS. The scan identified multiple vulnerabilities ranging from informational to high severity.

Key findings include:
- Open SSH services with weak configurations
- Exposed traceroute and timestamp data
- Backported or outdated software packages

Vulnerabilities were exported to Excel, analyzed, and mapped to relevant NIST 800-53 controls including:
- `AC-17` – Remote Access
- `SI-2` – Flaw Remediation
- `SC-7` – Boundary Protection

A Compliance Dashboard was created to track risk categories, remediation strategies, and compliance posture. All findings were marked

## 📝 Final Audit Report
[📄 View the full audit summary](FINAL-AUDIT-SUMMARY.txt)

