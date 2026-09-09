# Logical Network Diagram

This is a portfolio-friendly reconstruction of the project's logical-design concept. It is intentionally high-level and does not invent addressing, VLAN IDs, routing protocols, firewall policies, access-point models, or production configuration values that are not documented in the source material.

```mermaid
flowchart TD
    INTERNET[Business Internet]
    ROUTER[Business Router]
    FIREWALL[Cisco ASA 5516-X Firewall]
    SW1[Cisco Catalyst 9200L PoE\nSwitch 1]
    SW2[Cisco Catalyst 9200L PoE\nSwitch 2]
    USERS[Employee Workstations]
    WIFI[Wireless Infrastructure]
    PRINT[Office / Label Printers]
    CAM[Security Cameras]
    AWS[AWS-hosted Services\nReferenced in environment]
    M365[Microsoft 365 / AD\nBackup targets referenced]
    DATTO[Datto Backup Services]

    INTERNET --> ROUTER --> FIREWALL
    FIREWALL --> SW1
    FIREWALL --> SW2
    SW1 --> USERS
    SW2 --> USERS
    SW1 --> WIFI
    SW2 --> WIFI
    SW1 --> PRINT
    SW2 --> PRINT
    SW1 --> CAM
    SW2 --> CAM
    FIREWALL -.-> AWS
    M365 -.-> DATTO
```

## Interpretation

The source project retained selected existing switching and firewall infrastructure while proposing improvements around Internet capacity, wireless performance, endpoint performance, rack capacity/cooling, and workplace ergonomics.

AWS-hosted services were referenced as part of the existing environment. The source also documented Datto backups for Microsoft 365 and Active Directory; the diagram therefore keeps those backup targets separate rather than implying that Datto is an AWS backup service.

The two 9200L switches shown here follow the explicit physical asset-list entry. The original source also contains a 9300 reference; that inconsistency is documented in [Source Validation Notes](../documentation/source-validation.md).

This diagram is a **documentation aid**, not the original academic diagram and not a production configuration.
