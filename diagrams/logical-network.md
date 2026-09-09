# Logical Network Diagram

This is a portfolio-friendly reconstruction of the project's logical-design concept. It is intentionally high-level and does not invent addressing, VLAN IDs, routing protocols, or security rules that are not documented in the source material.

```mermaid
flowchart TD
    INTERNET[Business Internet]
    ROUTER[Business Router]
    FIREWALL[Cisco ASA 5516-X Firewall]
    CORE1[Cisco Catalyst 9200L PoE]
    CORE2[Cisco Catalyst 9200L PoE]
    USERS[Employee Workstations]
    WIFI[Wireless Infrastructure]
    PRINT[Office / Label Printers]
    CAM[Security Cameras]
    CLOUD[AWS-hosted Services]
    BACKUP[Datto Backup Services]

    INTERNET --> ROUTER --> FIREWALL
    FIREWALL --> CORE1
    FIREWALL --> CORE2
    CORE1 --> USERS
    CORE2 --> USERS
    CORE1 --> WIFI
    CORE2 --> WIFI
    CORE1 --> PRINT
    CORE2 --> PRINT
    CORE1 --> CAM
    CORE2 --> CAM
    FIREWALL -.-> CLOUD
    CLOUD -.-> BACKUP
```

## Interpretation

The source project selected and reused network infrastructure while proposing improvements primarily around Internet capacity, wireless performance, endpoint performance, rack cooling, and workplace ergonomics.

This diagram is a **documentation aid**, not the original academic diagram and not a production configuration.
