# Midwife Mesh

**Status: Concept stage — no functional prototype or field testing completed.**

**Proposed by:** Banadir Development Foundation (BADEF), Somalia  
**Proposed technology development partner:** Aspire Graphics Ltd, Kenya  
**Proposed pilot:** Afmadow District, Lower Juba, Jubaland, Somalia  
**Project website:** https://www.badef.org

> This repository documents a proposed maternal emergency communication solution. It does not contain a deployed clinical system. It must not be used for patient care or emergency response.

## The problem

Rural midwives around Afmadow and Dhobley face unreliable cellular coverage, limited transport, and long referral routes. BADEF's 2022–2023 Afmadow project recorded 548 skilled births and 206 emergency obstetric referrals. These are historical programme figures, **not** Midwife Mesh pilot results.

## Proposed solution

Midwife Mesh proposes to connect rural midwives to referral care using solar-powered LoRa radio nodes and an adapted open-source Meshtastic network. A Somali-language, pictorial interface would allow a midwife to select a danger sign and request help. Relay nodes would store and forward alerts; facilities would acknowledge receipt, coordinate referral, and optionally use SMS fallback where cellular coverage exists. A privacy-preserving dashboard is planned.

**Planned route:** Rural midwife → LoRa relay nodes → health centre gateway → referral hospital, with a return acknowledgement and referral coordination.

## Proposed pilot scope

- 40 midwives
- Waamo MCH and Bulakutuur Health Centre
- Four health posts and Kismayo Hospital
- 12 months, subject to funding, clinical review, approvals and technical feasibility

## Intended results (targets, not achieved outcomes)

| Indicator | Month-12 target |
| --- | --- |
| Alerts delivered to a facility | ≥95% |
| Median time to acknowledgement | Under 30 minutes |
| Midwives sending ≥1 message per month | 32 of 40 |
| Midwives remaining in rural practice | 36 of 40 |
| Public aggregate dashboard | Planned by month 6 |

## Current maturity and outstanding validation

The project is at **concept stage**. There is no Midwife Mesh application, radio integration, validated end-to-end alert transmission, field-test result, or production dashboard available in this repository. The team must validate LoRa range, message reliability, encryption, consent, radio regulatory requirements, SMS gateway feasibility, and emergency response procedures. The proposed network cannot replace established clinical referral pathways.

## Documentation

- [Problem and evidence](docs/problem-statement.md)
- [Proposed architecture](docs/system-architecture.md)
- [Technical specifications and open questions](docs/technical-specifications.md)
- [Pilot roadmap](ROADMAP.md)
- [Data protection and safety](docs/data-protection.md)
- [Partnership and governance](docs/governance.md)
- [UNICEF eligibility and evidence gaps](docs/funding-readiness.md)

## Open-source approach

The concept note proposes GPL-3.0 licensing for new software and CC BY for training content. **No original Midwife Mesh software has yet been published or licensed.** Before publishing source code, BADEF and Aspire Graphics must agree on ownership, contributor permissions, third-party licence compatibility and the exact licence notices. Meshtastic is a third-party open-source project; this repository is not affiliated with or endorsed by Meshtastic.

## Contact

Banadir Development Foundation — info@badef.org — https://www.badef.org

## Disclaimer

This is a proposed project, not a tested medical device or emergency communication service. Clinical decision aids require qualified clinical review and relevant approvals before any deployment.
