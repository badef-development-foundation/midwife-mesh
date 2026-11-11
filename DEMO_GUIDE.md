# Midwife Mesh — interactive concept demonstrator

**Status:** browser-based workflow simulation, built for BADEF's concept-stage project. **Not** a functional LoRa/Meshtastic implementation, medical device, clinically validated tool, or field-tested prototype.

## Run locally

Open `index.html` in any modern browser. No dependencies, account, server, internet connection or build process are required.

## Demonstrated workflow

1. Choose a fictional location, danger-sign category, and case code.
2. Click **Send simulated emergency alert**.
3. Observe the illustrative mesh routing steps and facility alert list.
4. Click **Acknowledge (simulation)** to update the facility status and counters.
5. Click **Reset demo** to clear the in-memory data.

**Important:** Routing is visual only. No radio hardware, Meshtastic integration, real message delivery, SMS fallback, encryption, persistent storage, patient record handling, clinical decision support or predictive analytics is implemented. Do not enter real patient data. The counters are not field results.

## Source concept

Banadir Development Foundation (BADEF), *Midwife Mesh Concept Note*, 2026. The proposal envisages LoRa/Meshtastic communication between rural midwives and referral facilities in Jubaland, Somalia, with Aspire Graphics Ltd as proposed technical partner.

## Next engineering steps

Hardware selection and regulatory review; Meshtastic device integration; authenticated gateways; secure message format; delivery acknowledgement/retry testing; Somali-language usability co-design; privacy and threat modelling; clinical and safeguarding reviews; ethics and ministry approvals; field evaluation. None of these steps has been completed by this demo.

## Licensing

This standalone demonstrator is provided under the MIT License in `LICENSE`. This does **not** determine the license of future Meshtastic-derived code, which must comply with applicable upstream licenses and be agreed by BADEF and its development partner.
