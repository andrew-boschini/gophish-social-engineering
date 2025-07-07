# BootCon Social Engineering Campaign – Project 4

**Author**: Andrew Boschini  
**Role**: Social Engineering Lead  
**Certifications in Progress**: Security+, Splunk Core Certified Power User  
**Tools Used**: Gophish, Kali Linux, cloned login pages (HTML), OSINT techniques

---

## Overview

This project involved planning and executing a social engineering campaign using Gophish as part of the BootCon cybersecurity simulation. The objective was to raise awareness of phishing risks by demonstrating how easily users could be tricked into entering credentials on spoofed web pages.

The campaign was designed to mimic a realistic corporate phishing attempt and to measure user interaction with the email, including link clicks and submitted credentials.

---

## Objectives

- Set up and configure a Gophish server
- Clone a legitimate login page to use as a phishing landing page
- Design and launch a phishing email template
- Track campaign metrics (opens, clicks, submissions)
- Report results and propose mitigations

---

## Campaign Details

- **Targeted Users**: Internal BootCon simulation participants
- **Phishing Method**: Email with embedded link to cloned login page
- **Landing Page**: Cloned version of Outlook login page
- **Hosted On**: Local Kali server using Python HTTP server
- **Tracking**: Email opened, link clicked, credentials entered

---

## Key Metrics

- Open Rate: 76%
- Click-Through Rate: 53%
- Credential Submission Rate: 42%
- Time to First Click: < 1 minute

---

## Skills Demonstrated

- Gophish installation and campaign setup
- Landing page development with HTML cloning
- Email template design and targeting
- Credential capture and analysis
- Ethical reporting and remediation suggestions

---

## Files Included

- `campaign-summary.md` – Detailed breakdown of campaign setup, results, and lessons learned
- `gophish-bootcon-presentation.pdf` – Slides presented at BootCon event
