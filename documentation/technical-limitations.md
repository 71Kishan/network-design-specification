# Technical Limitations and Assumptions

This project is a design-and-planning study, not a production deployment record. The following boundaries should be considered when reviewing the technical conclusions.

## Measurement limitations

- Packet-capture results represent the traffic observed during the documented capture period; they are not a current baseline for the client's network.
- The application bandwidth model covers the selected traffic documented in the project and should not be interpreted as a complete enterprise capacity model.
- Wi-Fi mapping reflects the conditions observed during the project assessment and does not establish permanent coverage or performance guarantees.

## Design limitations

- The source material does not establish a complete production configuration with IP addressing, VLAN IDs, routing protocols, firewall policies, access-point models, or switch-port configuration. The portfolio reconstruction therefore does not invent those details.
- Hardware alternatives documented in the project are proposed selections rather than evidence that procurement occurred.
- The implementation timeline and cost analysis are planning estimates from the project documentation.

## Outcome limitations

- The student team completed the design and planning work but did not perform the production installation, configuration, testing, or maintenance.
- The client reviewed and considered the project, but the exact proposed solution was not implemented. Later client-side infrastructure changes are outside this project's evidence base.

## Source inconsistency

The source documents contain conflicting switch-model references: a Cisco Catalyst 9300 48-port PoE reference appears in design material, while the physical asset list identifies two Cisco Catalyst 9200L 48-port PoE switches for reuse. This repository records the discrepancy rather than presenting an unsupported resolution as fact. See [Source Validation Notes](source-validation.md).

## Why these limitations matter

These constraints do not invalidate the project. They define what the project can credibly demonstrate: requirements analysis, network assessment, traffic analysis, design reasoning, infrastructure planning, and technical documentation—rather than production network ownership or deployment experience.
