# Phishing Analysis 1 — BTLO Challenge

## Challenge Info
- Platform: Blue Team Labs Online
- Date: 09/03/2026
- Difficulty: Easy
- Category: Phishing Analysis

## Tools Used
- MXToolbox
- VirusTotal
- AbuseIPDB
- DomainTools Whois

## Investigation

### Q1: Primary Recipient
- Investigated "To:" field in email header
- Answer: kinnar1975@yahoo.co.uk

### Q2: Subject
- Investigated "Subject:" field
- Answer: Website contact form submission

### Q3: Sending IP
- Found in X-PHP-Script header
- Answer: 91.90.123.43

### Q4: Reverse DNS
- Used DomainTools Whois
- IP: 103.9.171.10
- Answer: c5s2-1e-syd.hosting-services.net.au

### Q5: Malicious URL
- Found in email body
- Answer: https://35000usdperwwekpodf.blogspot.sg

### Q6: Hosting Service
- Identified from URL
- Answer: Blogspot

## What I Learned
- How to analyze phishing email headers
- How to investigate suspicious IPs
- How to perform Reverse DNS lookup
- How to extract malicious URLs
- How to use VirusTotal for IOC analysis

## Conclusion
This was a financial scam phishing email
targeting victims with fake earning claims
of $6500/week through a malicious blogspot page.
