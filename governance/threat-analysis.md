
# Phishing Identification & Threat Analysis Report

## 1. Executive Summary
This assessment highlights the identification methodologies and reporting procedures developed during the Mastercard Cybersecurity Job Simulation. Serving as an analyst on the Security Awareness Team, the primary objective was to analyze inbound communication threats, specifically phishing, and establish rapid reporting frameworks to mitigate corporate risk.

## 2. Threat Identification Framework
To protect corporate infrastructure from social engineering attacks, the following indicators were established to identify malicious emails:
* **Sender Verification:** Analyzing email headers for spoofed domains, mismatched display names, and unverified external senders.
* **Urgency & Coercion Check:** Highlighting behavioral triggers such as artificial deadlines, threats of account suspension, or unusual requests from leadership.
* **Technical Indicators:** Spotting disguised hyperlinks, suspicious attachments (e.g., hidden macro documents), and credential-harvesting landing pages.

## 3. Incident Reporting Procedure
When a suspicious communication is identified, the following enterprise response process is triggered:
1. **Triage:** The analyst reviews the user-reported email to confirm if it is a false positive, spam, or a verified phishing attempt.
2. **Containment:** If verified, indicators of compromise (IOCs) such as malicious URLs and sender IPs are forwarded to the Security Operations Center (SOC) for blocklisting.
3. **Metrics Tracking:** The attempt is logged into the Security Awareness database to track targeting trends across different departments.
