# APT Threat Hunting in Finance Sector
## Author: Rukayat Mopelola Lawal

### Date: March 2026
### Framework: MITRE ATT&CK® Enterprise

# Executive Summary
 Advanced Persistent Threat (APT) groups represent a substantial and evolving risk to the global finance sector. This project provides a structured approach to proactive threat hunting by leveraging the MITRE ATT&CK Enterprise framework to identify, map, and analyze adversarial behaviors specifically targeting financial institutions.

# Key Objectives:

 Comprehend fundamental principles of proactive threat hunting.
 Analyze high-stakes APT groups with verified targeting of the finance sector.
 Extract and document detailed Tactics, Techniques, and Procedures (TTPs).
 Visually map and compare these behaviors using MITRE ATT&CK Navigator


| APT Group | Origin | Primary Goal | Signature Malware |
| :--- | :---: | :--- | :--- |
| **APT38** | North Korea | Financial Theft (SWIFT) | `DYEPACK`, `Hermes` |
| **FIN7** | Russia | POS / Credit Card Theft | `Carbanak`, `Lizar` |
| **TA505** | Russia | Big Game Ransomware | `Cl0p`, `Dridex` |
| **APT41** | China | Espionage & Crypto Theft | `PlugX`, `Winnti` |

# Methodology: 

### The Hunting Lifecycle

#### This project utilizes the PEAK Threat Hunting Framework to move from theory to actionable intelligence

   Hypothesis: Creating "what if" scenarios based on current threat intelligence (e.g., Lazarus Group operating within the network).
   Collect & Analyze: Gathering telemetry from EDR, network logs (NDR), and cloud activity.
   Investigate: "Pivoting" on anomalies to find the root cause, such as active lateral movement.
   Respond & Improve: Handing off confirmed threats to Incident Response and creating new automated detection rules.

# Comparative TTP Analysis

## A core component of this project is the unified comparative view created in the MITRE ATT&CK Navigator.

### Shared vs. Unique Tactics:
  #### Initial Access: APT38 and FIN7 are "Kings of Social Engineering" (tailored spear-phishing), while TA505 prefers volume (millions of emails), and APT41 relies on technical Zero-day     exploits.
  #### Persistence: APT38 is "Low and Slow," remaining hidden for over 150 days to learn workflows. In contrast, TA505 is "Fast and Loud," moving at lightning speed to deploy ransomware.
  #### Defense Evasion: Modern adversaries heavily favor Living off the Land (LotL) techniques, utilizing legitimate tools like PowerShell, WMI, and Cobalt Strike to bypass traditional     Antivirus.
  
# Recommendations
### To remain resilient in 2026, financial organizations must adopt a multi-layered security posture: against
 TA505: Focus on Backup Integrity and rapid Endpoint Detection and Response (EDR).
 APT38: Prioritize Segregation of Duties and deep monitoring of inter-bank messaging (SWIFT).
 FIN7: Focus on Supply Chain Security and rigorous hardening of Point-of-Sale (POS) systems.
 APT41: Emphasize Patch Management (especially for public-facing apps) and monitor for unusual data exfiltration.

# References

Research was compiled from a variety of 2024–2026 high-fidelity sources:FBI/CISA advisories.ENISA Finance Threat Landscape.Mandiant/Google Cloud Threat Intelligence.Kaspersky ICS CERT.SOCRadar.

# License
### This research was conducted as part of a Cybersecurity Threat Hunting Project (March 2026) by Rukayat Mopelola Lawal.
  
