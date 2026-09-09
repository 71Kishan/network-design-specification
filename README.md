# Network Design Specification

A portfolio presentation of a network design and infrastructure planning project completed as part of a college project for a real client.

> **Project status:** Proposed design and planning project. The project team completed the documented design phases but did not perform the production installation or deployment. The client reviewed the work as a reference, did not implement the exact solution documented here, and later made infrastructure changes independently.

## Project Overview

This project connects requirements gathering and user feedback with traffic analysis, Wi-Fi analysis, logical network design, physical infrastructure planning, implementation planning, and cost analysis.

The repository separates **source evidence** from **portfolio reconstructions**. The original academic PDF and presentation are retained under `source-documents/`; the Markdown documentation reorganizes the technical substance into focused, reviewable sections.

## Start Here

- [Documentation Guide](documentation/README.md) — recommended reading order and scope language
- [Project Overview](documentation/project-overview.md) — background, process, and outcome
- [Source Validation Notes](documentation/source-validation.md) — documented inconsistencies and interpretation boundaries
- [Source Documents](source-documents/README.md) — original anonymized project deliverables

## Documentation Map

| Area | Document | Purpose |
|---|---|---|
| Requirements | [Requirements Analysis](documentation/requirements-analysis.md) | Existing environment, user requirements, and identified problems |
| Analysis | [Traffic & Wi-Fi Analysis](documentation/traffic-and-wifi-analysis.md) | Capture method, Wi-Fi mapping, and performance findings |
| Analysis | [Bandwidth Analysis](analysis/bandwidth-analysis.md) | Application bandwidth estimates and capacity planning |
| Analysis | [Packet Analysis](analysis/packet-analysis.md) | Packet-capture findings and traffic observations |
| Design | [Network Architecture](documentation/network-architecture.md) | High-level proposed architecture and design boundaries |
| Design | [Logical Design](documentation/logical-design.md) | Proposed infrastructure alternatives and logical design decisions |
| Design | [Physical Design](documentation/physical-design.md) | Equipment, rack, endpoint, cabling, and workplace planning |
| Inventory | [Asset Inventory](documentation/asset-inventory.md) | Proposed purchases, reused equipment, and planned returns |
| Planning | [Implementation & Cost Analysis](documentation/implementation-and-cost-analysis.md) | Effort estimates and documented project costing |
| Planning | [Implementation Timeline](planning/implementation-timeline.md) | Proposed work sequence, hours, and duration |

## Diagrams

- [Logical Network Diagram](diagrams/logical-network.md)
- [Physical Network Design Diagram](diagrams/physical-network.md)

These are simplified portfolio reconstructions of the documented design. They intentionally avoid inventing detailed addressing, VLAN IDs, routing protocols, firewall rules, access-point models, or production configurations that are not supported by the source material.

## What This Project Demonstrates

- Network requirements gathering and technical documentation
- Translating user and business requirements into infrastructure decisions
- Packet capture and traffic analysis using Wireshark
- Wi-Fi coverage and performance mapping
- Bandwidth estimation and capacity planning
- Logical network and infrastructure design
- Physical equipment, rack, and cabling planning
- Workstation and endpoint upgrade planning
- Implementation scheduling and effort estimation
- Infrastructure cost analysis

## Four Primary Improvement Areas

1. Network backbone and wireless performance
2. Employee workstation performance
3. Server-rack capacity and cooling
4. Workplace ergonomics

The analysis combined a network walkthrough, user survey, packet capture, Wi-Fi mapping, infrastructure assessment, equipment selection, and proposed implementation planning.

## Key Analysis

The project used a SPAN-connected laptop with Wireshark and scheduled capture intervals. The documented capture contained approximately **900 MB** of traffic and **6,436,267 packets**.

The documented application estimates were:

| Modeled traffic | Estimated bandwidth |
|---|---:|
| Email | 0.144 Mbps |
| FTP server | 12 Mbps |
| Security cameras | 4.8 Mbps |
| **Combined modeled traffic** | **16.944 Mbps** |

The 16.944 Mbps figure represents only the modeled applications in the project analysis; it is not presented as the complete bandwidth requirement of the organization.

## Proposed Improvements

The documented design considered:

- Higher-speed business Internet connectivity
- Replacement of the existing employee workstation fleet
- A larger, actively cooled server rack
- Adjustable sit/stand desks
- Continued use of selected existing network and peripheral equipment where appropriate

The proposed implementation plan covered equipment procurement, server-room management, cabling, wireless work, workstation management, and ergonomics.

## Project Status & Scope Boundary

**Completed by the team:** Requirements gathering, traffic/performance analysis, logical design, physical design, implementation planning, and cost analysis.

**Not completed by the project team:** Physical installation, production configuration, deployment, production testing, and maintenance.

**Client outcome:** The client reviewed and considered the project as a reference point but did not implement the exact solution documented here. Later infrastructure changes were made independently by the client and are outside this project's scope.

**Cost boundary:** The documented CAD cost figures are proposed/estimated planning values, not evidence of actual procurement expenditure by the project team.

## Repository Structure

```text
.
├── README.md
├── documentation/
│   ├── README.md
│   ├── project-overview.md
│   ├── requirements-analysis.md
│   ├── traffic-and-wifi-analysis.md
│   ├── network-architecture.md
│   ├── logical-design.md
│   ├── physical-design.md
│   ├── asset-inventory.md
│   ├── implementation-and-cost-analysis.md
│   └── source-validation.md
├── analysis/
│   ├── bandwidth-analysis.md
│   └── packet-analysis.md
├── planning/
│   └── implementation-timeline.md
├── diagrams/
│   ├── logical-network.md
│   └── physical-network.md
└── source-documents/
    ├── NDP - GDrive.pdf
    ├── NDP - GDrive.pptx
    └── README.md
```

## Technologies and Tools Referenced

- Wireshark
- Task Scheduler
- Cisco networking equipment
- Microsoft Windows
- AWS-hosted services referenced in the client environment
- Network topology and physical-layout documentation

## Authors

- Kishan Panchal
- Siem Tekleweini
- Markus Hanna
- Harjas Kaur

**Project date:** April 27, 2023

## Portfolio Note

This repository is designed to make the technical reasoning, analysis, planning, and documentation behind the project easier to review than the original academic submission alone.
