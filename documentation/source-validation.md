# Source Validation Notes

This page records material observations made while comparing the original project documents with the portfolio reconstruction.

## Cisco switch-model discrepancy

The source material contains two references that do not agree:

- Some design material references a **Cisco Catalyst 9300 48-port PoE** switch.
- The physical asset list identifies **two Cisco Catalyst 9200L 48-port PoE switches** for reuse.

### Portfolio treatment

The repository uses **two Cisco Catalyst 9200L 48-port PoE switches** when documenting the physical asset inventory because that is the explicit equipment entry in the physical asset list. The 9300 reference is not silently rewritten or presented as a confirmed physical asset.

This is a documentation decision, not a claim that the original source was error-free.

## Other important interpretation boundaries

- The documented traffic figures are treated as measurements/estimates from the project period, not as current client-network telemetry.
- The 16.944 Mbps figure is the combined estimate for the modeled email, FTP-server, and security-camera traffic in the project; it is not presented as the organization's complete bandwidth requirement.
- The implementation timeline and CAD cost figures are treated as proposed/estimated planning values, not evidence of an actual procurement or deployment.
- The project team did not perform the production installation, configuration, deployment, testing, or maintenance documented as Phase 5 activities.
- Subsequent changes made independently by the client are outside the project's documented scope.

## Editing principle

The original PDF and PPTX remain the primary historical record. Portfolio files may clarify terminology, structure, and scope, but should not manufacture missing technical details such as IP addressing, VLAN IDs, routing protocols, firewall policies, access-point models, or production configuration values.
