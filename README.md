 FUTURE_CS_02 — Phishing Email Analysis Report



## Overview
Technical phishing email analysis conducted on two real-world 
samples from a public phishing repository.

## Analyst
- **Name:** Wafa Chaibai
- **Track:** Cyber Security (CS)
- **Task:** 02 — Phishing Email Analysis

## Samples Analyzed
| Sample | Classification | Threat Type | Confidence |
|--------|---------------|-------------|------------|
| Sample-1101 | PHISHING — CRITICAL | Credential Harvesting (Microsoft Spoofing) | 100% |
| Sample-1102 | SPAM / SCAM | Product Scam + Tracking Pixel | 95% |

## Key Findings
- SPF / DKIM / DMARC: FAIL on both samples
- Display name spoofing confirmed
- Gmail Reply-To on corporate impersonation email
- Covert tracking pixel embedded (Sample-1102)

## Tools Used
- Google Admin Toolbox — Messageheader Analyzer
- Browser DevTools
- Manual header analysis

## Report
📄 [View Full PDF Report](./Phishing_Analysis_Report_2026.pdf)

> All samples sourced from public phishing repositories for educational purposes only.
