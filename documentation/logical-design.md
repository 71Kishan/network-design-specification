# Logical Network Design

## Design Objective

The logical design translated the requirements and analysis into a proposed network and infrastructure architecture. The project included network diagrams, hardware/software selection, and a revised logical design.

## Proposed Infrastructure Direction

### Internet and Wireless

The project evaluated higher-speed business connectivity as a response to the documented 50/50 Mbps environment and observed performance concerns. Two business-connectivity options were documented for consideration:

- MNSi for Business 500/500 Mbps
- Bell Gigabit Business Fibe 940/940 Mbps

### Endpoint Upgrade

The proposed workstation refresh covered 70 employee systems. The documented options included business-class systems such as:

- HP Elite Dragonfly
- Lenovo ThinkPad X1 Carbon

The intent was to improve workstation responsiveness and provide more capable hardware for the documented Microsoft 365 and Epicor workloads.

### Server-Room Infrastructure

The logical/physical planning included a larger, actively cooled rack to address the documented rack capacity and cooling concerns.

### Network Security and Switching

The design retained selected existing network infrastructure where appropriate, including the Cisco ASA 5516-X firewall and Cisco Catalyst switching equipment.

**Source note:** The source documents contain an internal switch-model discrepancy: some design material references a Cisco Catalyst 9300 48-port PoE switch, while the physical asset list identifies two Cisco Catalyst 9200L 48-port PoE switches for reuse. The portfolio inventory follows the explicit physical asset-list entry and does not present the 9300 reference as a confirmed physical asset. See [Source Validation Notes](source-validation.md).

## Design Workflow

The logical design was developed from the preceding requirements and analysis work:

1. Identify operational requirements
2. Review measured network behavior
3. Define infrastructure changes
4. Select candidate equipment/services
5. Produce logical diagrams
6. Translate the logical plan into the physical design

## Important Scope Note

This is a proposed design. The project team did not deploy the documented logical architecture in production, and the repository does not claim that the proposed configuration became the client's final network.
