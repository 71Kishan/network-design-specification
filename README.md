# Network Design Specification

A portfolio presentation of a network design and infrastructure planning project completed as part of a college project for a real client.

## Project Overview

This project documents the assessment and proposed redesign of a client network environment. The work connected requirements gathering and user feedback with traffic analysis, Wi-Fi analysis, logical network design, physical infrastructure planning, implementation planning, and cost analysis.

The project was completed through the design and planning phases. The client reviewed the work and considered it as a reference point, but did not implement the exact solution documented here. Subsequent infrastructure changes were made independently by the client and are outside the scope of this project.

## Documentation

| Document | Focus |
|---|---|
| [Project Overview](documentation/project-overview.md) | Background, scope, design process, and outcome |
| [Requirements Analysis](documentation/requirements-analysis.md) | Existing environment, user requirements, and identified problems |
| [Traffic & Wi-Fi Analysis](documentation/traffic-and-wifi-analysis.md) | Capture method, Wi-Fi mapping, and performance findings |
| [Bandwidth Analysis](analysis/bandwidth-analysis.md) | Application bandwidth estimates and capacity planning |
| [Packet Analysis](analysis/packet-analysis.md) | Packet capture findings and traffic observations |
| [Network Architecture](documentation/network-architecture.md) | High-level proposed architecture and design boundaries |
| [Logical Design](documentation/logical-design.md) | Proposed infrastructure alternatives and logical design decisions |
| [Physical Design](documentation/physical-design.md) | Equipment, rack, endpoint, cabling, and workplace planning |
| [Asset Inventory](documentation/asset-inventory.md) | Proposed purchases, reused equipment, and planned returns |
| [Implementation & Cost Analysis](documentation/implementation-and-cost-analysis.md) | Effort estimates and documented project costing |
| [Implementation Timeline](planning/implementation-timeline.md) | Proposed work sequence, hours, and duration |

## What This Project Demonstrates

- Network requirements gathering and documentation
- Translating user and business requirements into infrastructure decisions
- Packet capture and traffic analysis using Wireshark
- Wi-Fi coverage and performance mapping
- Bandwidth estimation and capacity planning
- Logical network and infrastructure design
- Physical equipment, rack, and cabling planning
- Workstation and endpoint upgrade planning
- Implementation scheduling and effort estimation
- Infrastructure cost analysis
- Technical documentation and presentation

## Project Scope

The design process addressed four primary improvement areas:

1. Network backbone and wireless performance
2. Employee workstation performance
3. Server-rack capacity and cooling
4. Workplace ergonomics

The analysis included a network walkthrough, user survey, packet capture, Wi-Fi mapping, infrastructure assessment, equipment selection, and proposed implementation planning.

## Key Analysis

A traffic capture was performed through a SPAN-connected laptop using Wireshark and scheduled capture intervals. The project documented approximately 900 MB of captured traffic and 6,436,267 packets in the referenced capture.

The documented application traffic estimates included 0.144 Mbps for email, 12 Mbps for FTP-server traffic, and 4.8 Mbps for security-camera traffic, for a combined estimate of 16.944 Mbps across those modeled applications.

## Proposed Improvements

The proposed design included:

- Higher-speed business Internet connectivity
- Replacement of the existing employee workstation fleet
- A larger, actively cooled server rack
- Adjustable sit/stand desks
- Continued use of selected existing network and peripheral equipment where appropriate

The project also documented an implementation plan covering equipment procurement, server-room management, cabling, wireless work, workstation management, and ergonomics.

## Repository Structure

```text
.
├── README.md
├── documentation/
│   ├── project-overview.md
│   ├── requirements-analysis.md
│   ├── traffic-and-wifi-analysis.md
│   ├── bandwidth-analysis.md
│   ├── packet-analysis.md
│   ├── network-architecture.md
│   ├── logical-design.md
│   ├── physical-design.md
│   ├── asset-inventory.md
│   └── implementation-and-cost-analysis.md
├── analysis/
│   ├── bandwidth-analysis.md
│   └── packet-analysis.md
├── planning/
│   └── implementation-timeline.md
├── diagrams/
├── source-documents/
│   ├── NDP - GDrive.pdf
│   ├── NDP - GDrive.pptx
│   └── README.md
└── assets/
    └── diagrams/
        └── README.md
```

## Project Status

**Completed by the team:** Requirements gathering, traffic/performance analysis, logical design, physical design, implementation planning, and cost analysis.

**Not completed by the project team:** Physical installation, production configuration, deployment, testing, and maintenance.

**Important:** This repository presents the work as a proposed design and planning project. It does not claim that the documented solution was deployed in production.

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

This repository is intended to make the technical reasoning, analysis, planning, and documentation behind the project easier to review than the original academic submission alone.
