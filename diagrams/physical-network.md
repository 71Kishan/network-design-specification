# Physical Network Design Diagram

This diagram summarizes the physical-design placement documented by the project. It is a simplified portfolio representation and does not replace the original floor-plan drawings.

```mermaid
flowchart TB
    HALL[Hallway\nProposed MNSi Business Router]
    SR[Server Room\nProposed 42U Air-Conditioned Rack]
    FW[Cisco ASA 5516-X]
    SW[Cisco Catalyst 9200L PoE\n2 switches]
    PLANT[Plant-wide Work Areas]
    LAP[70 × Proposed HP Elite Dragonfly]
    DESK[50 × Proposed Adjustable Standing Desk]
    MON[20 × Existing Dell Monitors]
    PROD[Production Area\n2 × Label Printers]
    OFFICE[Plant-wide\n3 × Office Printers]
    CAB[Existing Cat5e + Fiber Cabling]

    HALL --> SR
    SR --> FW
    FW --> SW
    SW --> CAB
    CAB --> PLANT
    PLANT --> LAP
    PLANT --> DESK
    PLANT --> MON
    CAB --> PROD
    CAB --> OFFICE
```

## Planned Physical Changes

- Replace the existing leased Dell Inspiron 5000 fleet with the proposed HP Elite Dragonfly notebooks.
- Install a larger 42U air-conditioned rack in the server room.
- Retain the documented Cisco Catalyst 9200L switches and Cisco ASA 5516-X firewall.
- Retain selected monitors, peripherals, printers, Cat5e, and fiber cabling.
- Introduce adjustable-height staff desks across the planned work areas.

## Status

The physical design was completed as part of the project. The diagram represents the **proposed physical plan**; the student team did not carry out the production installation.
