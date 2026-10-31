# Learning Progress

> Living record. Update after every meaningful learning or build session. Do not claim completion without evidence.

## Current focus

- **Stage:** 0 — Baseline and workstation
- **Topic:** Initial technical assessment and lab environment discovery
- **Status:** In progress
- **Completed:** Round 1 self-assessment and Round 2 workstation questionnaire
- **Next action:** Verify Windows build and virtualization support; then run practical baseline checks.

## Self-reported starting point

- DevOps: some theoretical knowledge.
- Linux: basic terminal commands.
- Python: basic syntax and scripts.
- Git/GitHub: can use branches and resolve conflicts.
- Docker: understands concepts; hands-on experience not established.
- Kubernetes: knows basic concepts.
- Cloud: has used Azure, but has no current access.
- Ansible: basic familiarity.

These are self-reported starting points, not validated competency ratings.

## Workstation constraints

- Windows 10; 8 GB RAM; 256 GB SSD.
- VS Code.
- Virtualization support and current Windows build are unknown.
- No current Azure access.
- Prefers a $0 learning setup.

Initial lab direction: lightweight, local-first. Check WSL2 support before installing or configuring it. Avoid multiple VMs and heavy local Kubernetes labs on this hardware.

## Competency snapshot

| Domain | Current level | Evidence | Next proof required |
|---|---|---|---|
| Linux | Self-reported basic commands; practical level unverified | Round 1 answer | Complete filesystem, permissions, process, and service tasks |
| Networking | Not assessed | | Explain and test DNS, IP, ports, and HTTP connectivity |
| Python / shell | Self-reported basic Python; shell unassessed | Round 1 answer | Write and explain a small useful script |
| Git | Self-reported branch and conflict experience; workflow unverified | Round 1 answer | Complete a repository workflow and explain conflict resolution |
| Docker | Concepts only, self-reported | Round 1 answer | Build and run a small container |
| CI/CD | Some theory, self-reported | Round 1 answer | Build a working pipeline |
| Cloud / IaC | Azure exposure self-reported; no current access | Round 1 answer | Complete a safe, cost-controlled cloud/IaC exercise when access is available |
| Kubernetes | Basic concepts, self-reported | Round 1 answer | Deploy and inspect a workload in a lab |
| Platform engineering | Not assessed | | Build and document a reusable platform capability |
| Observability / SRE | Not assessed | | Instrument, observe, and troubleshoot a service |
| Security | Not assessed | | Demonstrate secure configuration and secret handling |
| MLOps | Not assessed | | Build and operate a reproducible ML delivery workflow |

## Session history

### 2026-10-31 — Stage 0 baseline, Rounds 1 and 2
- Captured self-reported experience across DevOps, Linux, Python, Git, Docker, Kubernetes, Azure, and Ansible.
- Captured workstation constraints: Windows 10, 8 GB RAM, 256 GB SSD, VS Code, unknown virtualization support, no current Azure access, $0 preferred budget.
- No practical challenge has been passed yet.
- Next: verify Windows build and virtualization, then begin hands-on diagnostics.

Use [the session log template](templates/SESSION-LOG.md) for each substantial session.

## Update rules

For each session, record:
- Concepts learned and explanations the learner can give in their own words.
- What was actually implemented and where the code/evidence lives.
- Tests and validation performed, including results.
- Errors encountered and how they were diagnosed.
- What required hints or assistance.
- Remaining gaps and weaknesses.
- Next assignment and its acceptance criteria.

Keep this file concise. Put detailed notes and implementation artifacts in the relevant topic or project folder.
