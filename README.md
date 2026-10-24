# Insider Risk Map

An organizational layer for the Insider Threat Matrix™: what is done to which asset, by who has the access.

The Insider Threat Matrix™ describes what an insider does, entry by entry, from motive to anti-forensics. A program in a European organization has to answer two questions before it can choose its use cases and write its agreements: who, in this organization, has the access, and which asset the act reaches. The map combines the act with the asset on its rows and places eight access populations on its columns. Each cell holds scenarios; each scenario carries its signals, the chain of controls that answers it (prevent, detect, contain, respond), its Insider Threat Matrix™ entries, and the reporting obligations to be assessed for the asset under European law, from Insider Threat Event Requirements (ITER™).

- `index.html`: the map, an HTML page with the fonts beside it and no other dependency. Open it in a browser.
- `COVERAGE.md`: where each Infringement section of the Matrix sits on the map, and which ones the map excludes and why. Pinned to Matrix version 2.13.0.

## Rows and columns

Rows, the act and the asset: exfiltration of personal data; exfiltration of business information; sabotage of systems and operations; sabotage of data integrity; fraud on money and physical assets; misconduct towards people.

Columns, the access population: customer-facing; operations; technology; data and analytics; management; people functions; third parties; non-human identities.

Scope: acts by people and identities with legitimate access, including a colleague using another colleague's identity, where the act is theirs and the identity is the channel. An external attacker using a stolen identity is the work of security operations.

## What an organization does with it

It keeps the cells that apply to it, adds its own scenarios, and marks on its copy whether the act is visible and the asset recognized, and which lever it chose. Coverage is measured on the copy. The configuration of each control on Microsoft Purview, Defender, and Entra, with the works council agreement clauses and the data protection impact assessment paragraphs it rests on, is a separate, licensed kit.

## Versions

Version 0.5, October 2026. The mapping follows the Insider Threat Matrix™ version named in the map; a new version of the Matrix requires the coverage table to be reviewed.

## Licence and attribution

Insider Risk Map © Alessandro Aledda, [CC BY 4.0](LICENSE). Insider Threat Matrix™ is a trademark of Forscie Limited; the framework is published under the Apache License 2.0. This map is an independent work and is not sponsored, endorsed by, or affiliated with Forscie Limited. See `NOTICE`.

Alessandro Aledda, Insider Risk Consultant, [alessandroaledda.com](https://alessandroaledda.com).
