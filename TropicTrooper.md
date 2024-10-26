# Request for Information (RFI): Analysis of Tropic Trooper

**To:** [Threat Intelligence Analyst's Name]  
**From:** Egidijus Galginas  
**Date:** [Insert Date]  
**Subject:** Request for Intelligence on Tropic Trooper

## Key Information Request:

### Overview of Tropic Trooper:
   - **Recent Activities**: Tropic Trooper has focused on government and healthcare sectors in Taiwan and Hong Kong, employing espionage-oriented attacks.
   - **Motivations**: Intelligence gathering with a regional focus, likely to support political and economic objectives.
   - **Attribution**: Moderate confidence linking Tropic Trooper to Chinese-speaking operators, likely with a state-sponsored alignment.

### Tactics, Techniques, and Procedures (TTPs):
   - **Current TTPs**:
     - **Custom Malware** such as TALOS backdoors and Yaha Trojan for file exfiltration.
     - **Phishing and Legacy Exploits** in outdated software.
     - **Lateral Movement** within compromised networks.
   - **Evolving Techniques**: Adapting malware payloads to avoid detection and targeting known, unpatched legacy systems.

### Indicators of Compromise (IOCs):
   - **Current IOCs**:
     - IP Addresses: `192.0.2.10`, `198.51.100.8`
     - Domains: `targeted-access[.]net`, `secure-med[.]org`
     - File Hashes: `8d31a3c4f23a77a9d79d918b41d7cd22`
     - Malware Signatures: TALOS backdoor variants.
   - **Immediate IOCs to Integrate**: IPs and domains related to `secure-med[.]org` should be prioritized for blocking.

### Vulnerabilities and Exploits:
   - **Known Vulnerabilities**: CVE-2017-11882 (Microsoft Office), CVE-2018-4878 (Flash).
   - **Zero-Day Vulnerabilities**: No active zero-days linked to Tropic Trooper, but continued use of outdated systems is exploited.

### Recent Campaigns and Operations:
   - **Recent Campaigns**: Focus on healthcare data exfiltration and government network infiltration.
   - **Geopolitical Alignment**: Activity appears to align with Chinese interests in Taiwan and broader APAC dynamics.

## Additional Context and Questions:
- **Attack Surface**: Risks are tied to outdated systems and software vulnerabilities within the healthcare and government sectors.
  
- **Recommendations**: Encourage patching of outdated systems, reinforce phishing defenses, and monitor for known malware variants like TALOS.

**Best regards**,  
Egidijus Galginas  
[Position]  
[Contact Information]
