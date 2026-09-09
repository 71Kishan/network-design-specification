# Network Design Specification

A portfolio presentation of a network design and infrastructure planning project completed as part of a college project for a real client.

## Project Overview

This project documents the analysis and proposed redesign of a client network environment. The work covered requirements gathering, traffic and Wi-Fi analysis, logical network design, physical infrastructure planning, implementation planning, and cost analysis.

The project was completed through the design and planning phases. The client reviewed the work and used it as a reference point, but did not implement the exact solution documented here. Subsequent infrastructure changes were made independently by the client and are outside the scope of this project.

## Documentation

| Document | Focus |
|---|---|
| [Project Overview](documentation/project-overview.md) | Background, scope, process, and outcome |
| [Requirements Analysis](documentation/requirements-analysis.md) | Requirements gathering and identified problems |
| [Traffic & Wi-Fi Analysis](documentation/traffic-and-wifi-analysis.md) | Packet capture, bandwidth estimates, and wireless analysis |
| [Logical Design](documentation/logical-design.md) | Proposed network and infrastructure architecture |
| [Physical Design](documentation/physical-design.md) | Equipment, rack, cabling, endpoint, and workplace planning |
| [Implementation & Cost Analysis](documentation/implementation-and-cost-analysis.md) | Schedule, effort, and documented project costing |

## What This Project Demonstrates

- Network requirements gathering and documentation
- Analysis of network performance and user requirements
- Packet capture and traffic analysis using Wireshark
- Wi-Fi coverage and performance mapping
- Bandwidth estimation and capacity planning
- Logical network design and infrastructure planning
- Physical equipment and rack planning
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

A traffic capture was performed through a SPAN-connected laptop using Wireshark and scheduled capture intervals. The project documented approximately 900 MB of captured traffic over the analysis period, with 6,436,267 packets recorded in the referenced capture.

The documented application traffic estimates included approximately 0.144 Mbps for email, 12 Mbps for FTP-server traffic, and 4.8 Mbps for security-camera traffic, for a combined estimate of 16.944 Mbps across those applications.

## Proposed Improvements

The proposed design included:

- Higher-speed business Internet connectivity
- Replacement of existing employee workstations
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
│   ├── logical-design.md
│   ├── physical-design.md
│   └── implementation-and-cost-analysis.md
├── source-documents/
│   └── README.md
└── assets/
    └── diagrams/
        └── README.md
```

## Project Status

**Completed:** Requirements, analysis, logical design, physical design, implementation planning, and cost analysis.

**Not completed by the project team:** Physical installation/deployment.

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
