# Threat Hunting in Finance Sector
## Author: Rukayat Mopelola Lawal

### Date: March 2026
### Framework: MITRE ATT&CK® Enterprise

# Executive Summary
This project focuses on proactive threat hunting within the Finance industry, leveraging the MITRE ATT&CK framework to identify and analyse Advanced Persistent Threat (APT) groups targeting the sector.  

# Key Objectives:

Understand the MITRE ATT&CK framework and its practical application in threat hunting scenarios. 

Investigate advanced persistent threats (APTs) that are targeting the finance sector by utilising SOCRadar Labs. 

Link the identified APT groups to corresponding tactics, techniques, and procedures (TTPs) in the MITRE ATT&CK Navigator. 

| APT Group | Origin | Primary Goal | Signature Malware |
| :--- | :---: | :--- | :--- |
| **APT38** | North Korea | Financial Theft (SWIFT) | `DYEPACK`, `Hermes` |
| **APT43** | North Korea | Credential Theft | `BabyShark`, `AppleSeed` |
| **Cobalt** | Southeast Asia| ATM systems, card processing, payment systems | `Cl0p`, `Trojan.Win32` |
| **APT41** | China | Espionage & Crypto Theft | `PlugX`, `Winnti` |

# Map APTs to TTPs using MITRE Navigator 
Utilising the MITRE ATT&CK Navigator, individual layers were generated for each of the four identified APT groups with the United Kingdom specified as their operational location. This approach enabled a clear visual representation of the tactics, techniques, and procedures (TTPs) associated with each group. The creation of separate layers facilitated comparative analysis, making it possible to observe the specific methods used by these threat actors and to identify areas of overlap or similarity in their attack patterns targeting the finance sector. 



# Findings 

Analysis revealed several key patterns and trends: 

APT groups targeting finance frequently employ tactics such as Initial Access (spear phishing, watering hole attacks), Credential Access (credential dumping, brute force), and Lateral Movement (remote desktop protocol exploitation). 

There is significant overlap in TTPs among groups, with spear phishing and credential dumping emerging as the most prevalent techniques. 

Cobalt and Lazarus Group often exploit transactional systems and financial platforms, while APT 41 demonstrates broad targeting of both infrastructure and user accounts. 

Visualisation highlighted clusters of techniques concentrated around persistence and privilege escalation, suggesting adversaries prioritise maintaining access and expanding control once initial compromise is achieved. 

 
  
# Recommendations

To remain resilient in 2026, financial organizations must adopt a multi-layered security posture, Regular updates to threat intelligence and continuous review of attack patterns are essential to maintaining resilience against advanced threats. Policy makers are encouraged to facilitate sector-wide sharing of threat intelligence and promote adoption of frameworks like MITRE ATT&CK for structured, collaborative defence. 

# References

SOCRadar
MITRE ATT&CK
Mitre Attack Navigator.

# License
### This research was conducted as part of a Cybersecurity Threat Hunting Project (March 2026) by Rukayat Mopelola Lawal.
  
