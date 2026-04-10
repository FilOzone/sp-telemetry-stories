# SP Telemetry Stories

User stories for Storage Provider telemetry — metrics, instrumentation, and visualizations across the upload pipeline (Select → Store → Pull → Commit).

## Scope

Post-GA work. This repo tracks the breakdown of SP-reported telemetry into Epics and Features so we can align with Curio maintainers (Zenground Zero), Rod, and the FOC WG on what to build, measure, and surface.

## Source

Stories in this repo derive from the internal **SP Telemetry — GA Launch** design doc, which enumerates six metric groups across the upload pipeline (Upload Funnel, Store, Datasets, Pull, Commit, SP Availability) plus a Curio Telemetry questions list. Access is limited to FilOz / FOC working group members.

## Structure

Issues use GitHub's native types:
- **Epic** — a Job To Be Done, usually one per metric group
- **Feature** — a specific story under an Epic
- **Bug** — defects
- **Task** — engineering work items

### Labels

- Personas: `foc-team`, `sp`, `dapp-builder`
- Surfaces: `surface:dashboard`, `surface:instrumentation`, `surface:subgraph`, `surface:pipeline`

### Milestone

- `Post-GA` — all stories target work after the Filecoin Pay / FOC GA release.
