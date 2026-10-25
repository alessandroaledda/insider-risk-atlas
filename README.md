# Insider Threat Exposure Map (ITEM)

Insider risk scenarios classified by access population, act, and primary asset, with references to the [Insider Threat Matrix™](https://insiderthreatmatrix.org/).

The Insider Threat Matrix™ describes what an insider does, entry by entry, from motive to anti-forensics. A program in a European organization has to answer two questions before it can choose its use cases and write its agreements: who, in this organization, has the access, and which asset the act reaches. The map draws every scenario as one line from the access population that could carry it, through the act, to the primary asset it reaches; a population, an act, or an asset selects its scenarios. Each scenario carries its signals, the chain of controls that answers it (prevent, detect, contain, respond), its Insider Threat Matrix™ references, and the reporting assessment for the affected assets under European law, with references to Insider Threat Event Requirements (ITER). The scenarios are illustrative; their validation by the author is in progress.

- `index.html`: the map, an HTML page with the fonts beside it and no other dependency. Open it in a browser.
- `COVERAGE.md`: the relationship between each Infringement section of the Matrix and the six combinations of the map, direct, partial, or contextual, and the sections without a primary mapping. Pinned to Matrix version 2.13.0.

## The three dimensions

Acts on a primary asset, six combinations: exfiltration of personal data; exfiltration of business information; disruption of systems and operations; disruption of data integrity; fraud on money and physical assets; misconduct towards people, on personal data.

Access populations, eight: customer-facing; operations; technology; data and analytics; management; people functions; third parties; non-human identities.

Every scenario has a stable identifier (ITEM-001 to ITEM-039) and is reached at `index.html#ITEM-nnn`.

Scope: acts by people and identities with legitimate access, including a colleague using another colleague's identity, where the act is theirs and the identity is the channel. An external attacker using a stolen identity is the work of security operations.

## What an organization does with it

It keeps the scenarios that apply to it, adds its own, and marks on its copy whether the act is visible and the asset recognized, and which lever it chose. Coverage is measured on the copy. The configuration of each control on Microsoft Purview, Defender, and Entra, with the works council agreement clauses and the data protection impact assessment paragraphs it rests on, is a separate, licensed kit.

## Versions

Version 0.6, 26 October 2026, under review. Version 1.0 will follow the author's review of the scenarios and the exchange with Forscie. The mapping follows the Insider Threat Matrix™ version named in the map; a new version of the Matrix requires the coverage table to be reviewed.

## License and attribution

Insider Threat Exposure Map (ITEM) © Alessandro Aledda, [CC BY 4.0](LICENSE). Insider Threat Matrix™ is a trademark of [Forscie Limited](https://forscie.com/); the framework is published under the Apache License 2.0. This map is an independent work and is not sponsored, endorsed by, or affiliated with Forscie Limited. See `NOTICE`.

Alessandro Aledda, Insider Risk Consultant, [alessandroaledda.com](https://alessandroaledda.com).
