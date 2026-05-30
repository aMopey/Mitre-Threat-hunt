# Threat Hunting in the Finance Sector with MITRE ATT&CK

**Author:** Rukayat Mopelola Lawal  
**Date:** March 2026

---

## Overview

A proactive threat hunting project focused on the finance industry, using the MITRE ATT&CK framework to identify, map, and analyse Advanced Persistent Threat (APT) groups targeting the sector.

---

## Objectives

- Understand the MITRE ATT&CK framework and its practical application in threat hunting
- Identify APT groups targeting the finance sector using SOCRadar Labs
- Map identified APT groups to their tactics, techniques, and procedures (TTPs) in the MITRE ATT&CK Navigator
- Conduct comparative analysis to uncover shared attack patterns across threat actors

---

## Tools & Resources

| Tool | Purpose |
|------|---------|
| [SOCRadar Labs](https://socradar.io) | Threat intelligence gathering; identifying finance-sector APTs |
| [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) | Mapping and visualising TTPs per APT group |
| [MITRE ATT&CK Framework](https://attack.mitre.org) | Structured taxonomy of adversary behaviours |

---

## APT Groups Identified

Four APT groups were identified via SOCRadar Labs as active threats to financial organisations:

### 1. APT 41
**Aliases:** Amoeba, BARIUM, BRONZE ATLAS, Blackfly, Brass Typhoon, Double Dragon, Earth Baku, G0044, G0096, Grayfly, HOODOO, LEAD, Leopard Typhoon, Red Kelpie, TA415, TG-2633, WICKED PANDA, WICKED SPIDER, Winnti

### 2. Lazarus Group
**Aliases:** APT 38, APT-C-26, Appleworm, BeagleBoyz, Black Artemis, Bluenoroff

### 3. Kimsuky
**Aliases:** MoneyLibra

### 4. Cobalt
**Aliases:** G0080, Cobalt Spider, Cobalt Gang

---

## Methodology

1. **Framework Study** — Reviewed MITRE ATT&CK structure: Tactics (objectives), Techniques (methods), and Procedures (real-world implementations).
2. **APT Research** — Used SOCRadar Labs to identify APT groups with a confirmed focus on the finance sector.
3. **TTP Mapping** — Generated individual ATT&CK Navigator layers for each APT group, scoped to the United Kingdom as the operational location.
4. **Comparative Analysis** — Overlaid layers to identify shared techniques and clusters of activity.

---

## Key Findings

- **Most prevalent techniques:** Spear phishing (Initial Access) and credential dumping (Credential Access) appear across multiple groups.
- **Common tactic categories:** Initial Access, Credential Access, Lateral Movement (notably via RDP exploitation), Persistence, and Privilege Escalation.
- **Group-specific patterns:**
  - *Cobalt* and *Lazarus Group* frequently target transactional systems and financial platforms.
  - *APT 41* demonstrates broad targeting of both infrastructure and individual user accounts.
- **Visualisation insight:** Techniques cluster heavily around persistence and privilege escalation, suggesting adversaries prioritise maintaining and expanding access after initial compromise.

---

## Recommendations

- Prioritise defences against **phishing and credential theft**
- Strengthen **lateral movement monitoring** across internal networks
- Enforce **robust multi-factor authentication** protocols
- Invest in **targeted employee training**, particularly phishing awareness
- Maintain **regular threat intelligence updates** to track evolving TTPs
- Encourage **sector-wide intelligence sharing** and adoption of structured frameworks like MITRE ATT&CK

---

## Conclusion

Mapping APT groups to TTPs via the MITRE ATT&CK framework provides actionable visibility into the finance sector threat landscape. The recurrence of specific techniques across multiple threat actors indicates that financial organisations can significantly reduce risk through layered security controls, continuous monitoring, and collaborative, intelligence-driven defence strategies.
