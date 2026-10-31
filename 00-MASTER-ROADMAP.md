# Master Roadmap

## Mission

Develop the ability to independently design, build, deploy, automate, secure, troubleshoot, and operate production-grade infrastructure, cloud platforms, delivery systems, and ML platforms.

## Training method

Every topic follows this loop:

1. **Understand** the concepts, terminology, and underlying mechanisms.
2. **Design** a solution and explain alternatives and trade-offs.
3. **Build** a working implementation from a clean starting point.
4. **Validate** expected behavior, edge cases, and failure scenarios.
5. **Operate** it with logs, metrics, alerts, backups, and runbooks where relevant.
6. **Review** security, reliability, cost, maintainability, and technical debt.
7. **Demonstrate** independent competence through a practical challenge.

Reading or following a tutorial is not sufficient evidence of mastery.

## Roadmap

The sequence is a proposed progression. The exact pace and depth will be adjusted after the technical baseline is assessed.

| Stage | Focus | Practical outcome | Gate to progress |
|---|---|---|---|
| 0 | Baseline and workstation | Reproducible development environment and baseline assessment | Can use the terminal, Git, editor, and basic troubleshooting workflow |
| 1 | Linux and networking | Administer a Linux host; diagnose processes, storage, DNS, routing, and ports | Solve common host/network incidents without step-by-step instructions |
| 2 | Python and shell automation | Write tested scripts and command-line tools | Handle errors, inputs, logging, tests, and documentation |
| 3 | Git and software delivery foundations | Use branches, reviews, commits, tags, and release workflows | Explain and demonstrate a safe change workflow |
| 4 | Containers and Docker | Build, inspect, secure, and run containerized applications | Debug image, networking, storage, and runtime issues |
| 5 | CI/CD | Build automated test, build, scan, and deployment pipelines | Deliver a change through a repeatable pipeline |
| 6 | Cloud and infrastructure as code | Provision and manage cloud resources reproducibly | Recreate and safely change infrastructure from code |
| 7 | Kubernetes | Deploy and operate workloads and troubleshoot cluster behavior | Explain and diagnose scheduling, networking, storage, and rollout issues |
| 8 | GitOps and platform engineering | Build a declarative delivery workflow and reusable platform capabilities | Demonstrate controlled reconciliation and developer self-service |
| 9 | Observability and SRE | Instrument services and manage reliability objectives | Diagnose a failure using telemetry and a runbook |
| 10 | Security and production operations | Apply identity, secrets, policy, backup, recovery, and incident practices | Demonstrate least privilege and recover from a planned failure |
| 11 | MLOps foundations | Build reproducible ML delivery and serving workflows | Version data/models and deploy an observable model service |
| 12 | Capstone | Deliver an integrated production-style platform | Defend architecture, demonstrate operations, and explain trade-offs |

## Topic tracks

- Linux, networking, and Python
- Git and software engineering foundations
- Docker and container fundamentals
- CI/CD and release engineering
- Cloud fundamentals and infrastructure as code
- Kubernetes and cloud-native operations
- GitOps and platform engineering
- Observability, SRE, and incident response
- Security and governance
- MLOps and model serving

Topic-specific entry points live in [learning-paths/](learning-paths/README.md).

## Competency levels

- **Not assessed:** no reliable evidence yet.
- **Learning:** concepts are being studied; work still needs substantial guidance.
- **Practicing:** can complete guided tasks and explain the main steps.
- **Working independently:** can design, implement, test, and troubleshoot a bounded task without a recipe.
- **Production-ready evidence:** can justify trade-offs, handle failure modes, document operations, and demonstrate repeatable results.

These labels describe demonstrated evidence, not confidence or time spent.

## Initial assessment questions

The first mentoring milestone is to establish:
- Current Linux, networking, Git, programming, Docker, cloud, and Kubernetes experience.
- Operating system, machine resources, editor, terminal, and local virtualization/container options.
- Existing cloud accounts and budget constraints (never record credentials).
- Weekly learning time and target role or job-market direction.
- Existing projects, certifications, and practical work worth documenting.

Until assessed, no stage is marked complete.
