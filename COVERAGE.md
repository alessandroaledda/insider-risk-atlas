# Infringement coverage

Insider Threat Matrix™ version 2.13.0. Of the Matrix's 45 Infringement sections (AR4), 31 are assigned to an act and primary asset. The remaining 14 are excluded from the classification, with a recorded reason. Of the 31 assigned sections, 16 are cited by at least one scenario in this map version. An entry excluded from the classification may still appear in scenario references. IF019 and IF039 are cited as means. A new Matrix version requires a review of this table.

## Assigned sections

| section | rows of the map | note |
|---|---|---|
| IF001 Exfiltration via Web Service | Exfiltration: personal data; Exfiltration: business information | Channel: web services (cloud, repositories, collaboration, generative AI) |
| IF002 Exfiltration via Physical Medium | Exfiltration: personal data; Exfiltration: business information | Channel: physical media |
| IF003 Exfiltration via Media Capture | Exfiltration: personal data; Exfiltration: business information | Channel: photography, audio, and video capture |
| IF004 Exfiltration via Other Network Medium | Exfiltration: personal data; Exfiltration: business information | Channel: other network media, including API and screen sharing |
| IF005 Exfiltration via Messaging Applications | Exfiltration: personal data; Exfiltration: business information | Channel: messaging applications |
| IF006 Unauthorized Printing of Documents | Exfiltration: personal data; Exfiltration: business information | Channel: printing |
| IF010 Exfiltration via Email | Exfiltration: personal data; Exfiltration: business information | Channel: email, corporate or personal |
| IF011 Providing Access to a Unauthorized Third Party | Sabotage: systems and operations; Exfiltration: business information | Weakening a control for a third party sits with sabotage; granting a third party access to a platform exposes what the platform holds, and sits with business information |
| IF013 Disruption of Business Operations | Sabotage: systems and operations | The act of disruption itself |
| IF014 Unauthorized Changes to IT Systems | Sabotage: systems and operations | Changes to systems, access controls, and cloud resources, deliberate or negligent |
| IF015 Theft | Fraud: money and physical assets | Physical assets diverted; the data on a stolen device is an exfiltration scenario of its own |
| IF016 Misappropriation of Funds | Fraud: money and physical assets; Exfiltration: business information | Funds misappropriated; IF016.004 Insider Trading sits with inside information |
| IF018 Sharing on AI Chatbot Platforms | Exfiltration: personal data; Exfiltration: business information | Channel: AI chatbot platforms, often negligent |
| IF021 Harassment and Discrimination | Misconduct towards people | Harm to a person through communications and conduct, where the organization's channels carry it |
| IF022 Data Loss | Exfiltration: personal data; Exfiltration: business information; Sabotage: systems and operations | The loss itself, by kind of data: PII, PHI, and payment card data are personal; IP and media leaks are business information; a credential leak opens systems |
| IF024 Exfiltration via Screen Sharing | Exfiltration: personal data; Exfiltration: business information | Channel: screen sharing |
| IF026 Denial of Service | Sabotage: systems and operations | Disruption of availability |
| IF027 Installing Malicious Software | Sabotage: systems and operations; Exfiltration: personal data | Destructive malware is sabotage; an infostealer is exfiltration |
| IF028 Delegated Execution via Artificial Intelligence Agents | Exfiltration: personal data; Exfiltration: business information; Sabotage: systems and operations; Misconduct towards people | Cross-cutting: the non-human identities column, in every row it reaches |
| IF029 Codebase Integrity Compromise | Sabotage: systems and operations | Integrity of code and pipelines |
| IF030 Exfiltration via SMS/MMS | Exfiltration: personal data; Exfiltration: business information | Channel: SMS and MMS |
| IF032 External Credential Sharing | Exfiltration: business information; Sabotage: systems and operations | Credentials given outside: what they open is the asset |
| IF033 Digital Defacement | Sabotage: systems and operations | Integrity of public and internal surfaces |
| IF034 Exfiltration via Automated Transcription | Exfiltration: personal data; Exfiltration: business information | Channel: automated transcription of meetings |
| IF036 Misuse of Corporate Communication Channels | Misconduct towards people | Hostile or inappropriate communications towards people |
| IF037 Physical Sabotage | Sabotage: systems and operations | Physical sabotage of equipment and infrastructure |
| IF040 Data Integrity Manipulation | Sabotage: data integrity | The alteration of records, data in transit, or what a system presents |
| IF042 Deliberate Safety Control Defeat | Sabotage: systems and operations | Safety controls defeated: operations and people at risk |
| IF043 Organizational Resource Diversion | Fraud: money and physical assets | Resources, equipment, inventory, personnel, and working time diverted |
| IF044 Abuse of Decision-Making Authority | Fraud: money and physical assets | Authority abused for approval, preference, or waiver |
| IF045 Unauthorized Data Access | Misconduct towards people; Exfiltration: business information | Access without a business reason: to customer and workforce data it is misconduct; to organizational and third-party data it sits with business information, and a transfer that follows is assessed as its own event |

## Excluded sections

| section | why |
|---|---|
| IF007 Unlawfully Accessing Copyrighted Material | Conduct towards third parties' rights, not an act on the organization's assets; acceptable-use matter |
| IF008 Inappropriate Web Browsing | Conduct; the monitoring of browsing content is restricted under European employment law and is not a program measure |
| IF009 Installing Unapproved Software | Endpoint hygiene, handled by security operations; appears in scenarios as a means, not as the act |
| IF012 Public Statements Resulting in Brand Damage | Communications and reputation; not an act on an information asset; the communications and Human Resources functions |
| IF017 Excessive Personal Use | Conduct; a program measure here would have to pass the necessity and proportionality test that European employment and data protection law set for monitoring, and is unlikely to |
| IF019 Non-Corporate Device | A means (the device), not an act; appears in scenarios as the channel |
| IF020 Unauthorized VPN Client | A means; network hygiene, handled by security operations |
| IF023 Regulatory Non-Compliance | Export, sanctions, and competition law: the trade compliance function's domain; an interface, not a program measure |
| IF025 Internal Credential Sharing | A means: the colleague's identity as the channel; the act performed with it is classified under its own act and primary asset |
| IF031 Unauthorized Presence in Restricted Physical Areas | Physical security's domain; a preparation for sabotage or theft, handled at the interface with corporate security |
| IF035 Unauthorized Work Location | Conduct and compliance (tax, immigration, and data residency); location monitoring is restricted and is not a program measure |
| IF038 Undisclosed Concurrent Employment | Conflict of interest and conduct; the HR and compliance functions |
| IF039 Unauthorized Account Access | A means: access to another account, or to one's own after it should have been closed; the act performed with it is classified under its own act and primary asset |
| IF041 Unauthorized Organizational Representation | Conduct and legal exposure; where a contract or payment follows, the scenario is classified under fraud |

Means (AR2), motives (AR1), preparation (AR3), and anti-forensics (AR5) are recorded at scenario level and appear in scenario references; they are not part of the classification.

Insider Threat Matrix™ is a trademark of [Forscie Limited](https://forscie.com/); the framework is published under the Apache License 2.0. This table is part of Insider Threat Exposure Map (ITEM™), CC BY 4.0, Alessandro Aledda.
