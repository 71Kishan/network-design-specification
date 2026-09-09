# Documentation Guide

This directory contains the narrative documentation for the Network Design Specification project.

## Recommended reading order

1. Start with [Project Overview](project-overview.md) for scope, project history, design process, and outcome.
2. Review [Requirements Analysis](requirements-analysis.md) to understand the documented environment and identified problems.
3. Review [Requirements-to-Design Traceability](requirements-to-design-traceability.md) to follow each requirement from evidence to proposed response.
4. Review [Traffic & Wi-Fi Analysis](traffic-and-wifi-analysis.md), then the focused [Bandwidth Analysis](../analysis/bandwidth-analysis.md) and [Packet Analysis](../analysis/packet-analysis.md) for supporting measurements.
5. Review [Network Architecture](network-architecture.md), [Logical Design](logical-design.md), and [Physical Design](physical-design.md) for the proposed solution.
6. Review [Asset Inventory](asset-inventory.md), [Implementation & Cost Analysis](implementation-and-cost-analysis.md), and [Implementation Timeline](../planning/implementation-timeline.md) for the planned execution model.
7. Review [Technical Limitations & Assumptions](technical-limitations.md) and [Source Validation Notes](source-validation.md) for evidence boundaries and known source inconsistencies.
8. Finish with the [Final Repository Review](final-review.md) for the portfolio quality gate and deliberate non-claims.

## Source-of-truth rule

The original academic PDF and presentation in `source-documents/` are the primary project evidence. Portfolio documentation summarizes and restructures that evidence; it must not imply work that the source material does not support.

Where the source documents contain an internal inconsistency, the portfolio documentation records the inconsistency rather than silently inventing a resolution. See [Source Validation Notes](source-validation.md).

## Scope language

The repository uses the following distinction consistently:

- **Observed:** information measured, documented, or recorded in the project.
- **Analyzed:** conclusions or calculations derived from the documented evidence.
- **Proposed:** equipment, architecture, or improvements selected for the design.
- **Planned:** implementation steps, effort, duration, or cost estimates.
- **Implemented:** production work actually performed by the project team. The project does not claim this stage.

## Portfolio principle

The repository should make the technical reasoning easier to evaluate without overstating the project's real-world outcome. The source deliverables preserve the original project record; the Markdown documentation provides the curated engineering narrative.