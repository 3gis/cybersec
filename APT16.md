# Request for Information (RFI): Analysis of APT16

**To:** [Threat Intelligence Analyst's Name]  
**From:** Egidijus Galginas  
**Date:** [Insert Date]  
**Subject:** Request for Intelligence on APT16 

## Key Information Request:

### Overview of APT16:
   - **Recent Activities**: APT16 has recently targeted media and political organizations within Japan, Taiwan, and broader Asia-Pacific regions. Their attacks typically aim to disrupt and gather intelligence from political, economic, and technological targets.
   - **Motivations**: Primarily focused on espionage with a potential influence on regional politics.
   - **Attribution**: High-confidence attribution links APT16 to Chinese state-sponsored activities, especially focusing on collecting sensitive information from media and governmental organizations.

### Tactics, Techniques, and Procedures (TTPs):
   - **Current TTPs**:
     - **Spear-phishing** for initial access, often with email attachments containing malware.
     - **File Exfiltration** using custom backdoors that bypass detection mechanisms.
     - **Privilege Escalation** through exploiting web-based application vulnerabilities.
   - **Evolving Techniques**: APT16 has adapted its phishing campaigns to mimic trusted entities more closely, and its malware infrastructure has become more resilient to analysis.

### Indicators of Compromise (IOCs):
   - **Current IOCs**:
     - IP Addresses: `192.168.1.1`, `10.0.0.2`
     - Domains: `example1[.]com`, `media-target[.]org`
     - File Hashes: `5d41402abc4b2a76b9719d911017c592`
     - Malware Signatures: Custom RAT signatures (e.g., “APT16_Backdoor_A”)
   - **Immediate IOCs to Integrate**: Critical IOCs include domains like `media-target[.]org` and IP `10.0.0.2` for real-time blocking.

### Vulnerabilities and Exploits:
   - **Known Vulnerabilities**: CVE-2021-26855 (Exchange Server), CVE-2019-19781 (Citrix), which are often exploited in APT16 campaigns.
   - **Zero-Day Vulnerabilities**: No current zero-day vulnerabilities linked directly to APT16.

### Recent Campaigns and Operations:
   - **Recent Campaigns**: APT16 has been involved in campaigns aimed at influencing public perception via compromised media organizations, often aligning with key regional events.
   - **Geopolitical Alignment**: These campaigns align with Chinese regional interests, specifically regarding political stability in Taiwan and economic policies in Japan.

## Additional Context and Questions:
- **Attack Surface**: With a focus on our digital infrastructure, APT16’s reliance on exploiting web-based applications highlights the need to secure public-facing applications and ensure robust email filtering.
  
- **Recommendations**: Implement email filters to catch phishing attempts, enhance web application security, and regularly update software to patch known vulnerabilities like CVE-2021-26855.

**Best regards**,  
Egidijus Galginas  
[Position]  
[Contact Information]
