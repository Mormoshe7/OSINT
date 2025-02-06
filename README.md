# OSINT and Social Engineering Report on Apple

This report documents an investigation conducted using OSINT (Open Source Intelligence) tools on Apple Inc., focusing on gathering and analyzing publicly available information. The report includes the use of tools such as Google Search, WHOIS, LinkedIn, Hunter.io, Shodan, and more. Additionally, it demonstrates an example of a social engineering attack using ZPhisher.

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Tools Used](#tools-used)
4. [Methodology](#methodology)
5. [Findings](#findings)
6. [Social Engineering Example](#social-engineering-example)
7. [Conclusion](#conclusion)

---

## Introduction
This report outlines the steps taken during an OSINT investigation on Apple Inc. The goal was to gather publicly available information about the company, its key personnel, and its infrastructure. The investigation also includes an example of a social engineering attack using ZPhisher.

## Objectives
1. Gain access to internal servers.
2. Collect personal information of key personnel for targeted attacks.

## Tools Used
- **Google Search**: For gathering information about key personnel and their public profiles.
- **WHOIS**: For domain registration details.
- **LinkedIn**: For identifying employees and company structure.
- **Hunter.io**: For email address pattern identification.
- **Shodan**: For scanning exposed servers and services.
- **ZPhisher**: For demonstrating a social engineering attack.

## Methodology
1. **Google Search**: Searched for information about Apple's CEO, Tim Cook, including his social media profiles and residential address.
2. **WHOIS**: Analyzed domain registration details for `apple.com`.
3. **LinkedIn**: Identified active employees and inferred company structure.
4. **Hunter.io**: Identified email address patterns used by Apple.
5. **Shodan**: Scanned IP addresses associated with Apple to identify exposed servers and services.
6. **ZPhisher**: Set up a phishing page mimicking Gmail's login page to demonstrate a social engineering attack.

## Findings
- Identified key personnel and their public profiles.
- Discovered domain registration details and server locations.
- Identified email address patterns used by Apple employees.
- Found exposed servers and services using Shodan.
- Successfully demonstrated a social engineering attack using ZPhisher.

## Social Engineering Example
Using ZPhisher, a phishing page was created to mimic Gmail's login page. The page was hosted locally and shared using LocalXpose to make it accessible externally. The attack successfully captured login credentials entered by the target.

## Conclusion
This report demonstrates the effectiveness of OSINT tools in gathering publicly available information about a company. It also highlights the risks associated with social engineering attacks and the importance of cybersecurity awareness.

---

### How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
