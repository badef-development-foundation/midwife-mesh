# Midwife Mesh

**Status: Interactive browser-based software proof of concept available; physical LoRa integration and field testing not completed.**

**Live interactive demonstration:** https://badef-development-foundation.github.io/midwife-mesh/  
**Source code:** [index.html](index.html)  
**Manual demonstration observations:** [TEST_NOTES.md](TEST_NOTES.md)

**Proposed by:** Banadir Development Foundation (BADEF), Somalia  
**Proposed technology development partner:** Hornlink (Horn Digital Limited), Somalia  
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

A publicly accessible browser-based demonstration allows users to create fictional maternal emergency alerts, view illustrative mesh-routing steps, and acknowledge alerts in a simulated facility dashboard. On 11 November 2026, two fictional alerts were manually generated and acknowledged in the browser (two generated, two acknowledged, zero pending). This is **manual software simulation testing only**, not radio, SMS, clinical or field validation.

The demonstration does not implement LoRa/Meshtastic hardware communication, verified message delivery, SMS fallback, clinical decision support or a production dashboard. Radio range, reliability, security, consent, regulatory approvals and emergency response protocols remain to be validated. It must not be used for actual patient care or emergencies.

## Documentation

- [Problem and evidence](docs/problem-statement.md)
- [Proposed architecture](docs/system-architecture.md)
- [Technical specifications and open questions](docs/technical-specifications.md)
- [Pilot roadmap](ROADMAP.md)
- [Data protection and safety](docs/data-protection.md)
- [Partnership and governance](docs/governance.md)
- [UNICEF eligibility and evidence gaps](docs/funding-readiness.md)

## Open-source approach

The standalone browser demonstrator is published with an [MIT License](LICENSE). This does not determine the licence of future LoRa/Meshtastic-derived software, which must comply with applicable upstream requirements. The concept note proposes GPL-3.0 for future software and CC BY for training materials, subject to confirmation by BADEF and Hornlink. The project is not affiliated with or endorsed by Meshtastic.

## Contact

Banadir Development Foundation — info@badef.org — https://www.badef.org

## Disclaimer

This is a proposed project, not a tested medical device or emergency communication service. Clinical decision aids require qualified clinical review and relevant approvals before any deployment.
