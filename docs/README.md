# OctoAcme Project Management Docs

Welcome to OctoAcme's central project management documentation hub. This README serves as the single entry point to all process documentation, providing a concise overview of how OctoAcme plans, executes, and delivers projects. Whether you are a new team member getting oriented or a seasoned contributor looking for a quick reference, these docs are here to support you.

The documents in this folder capture OctoAcme's shared process knowledge: from project initiation and planning all the way through release, risk management, and continuous improvement. Keep this README up to date as process documents evolve so that it remains a reliable guide for the entire team.

---

## OctoAcme Project Management: Overview

OctoAcme's project management processes are built around clear roles, structured communication, and disciplined workflows designed for cross-functional collaboration and incremental delivery. The core framework follows the typical project lifecycle phases: **Initiation → Planning → Execution → Release → Retrospective**. For project initiation, teams develop a project one-pager that aligns stakeholders around the problem statement, success metrics, and resource needs. Planning involves breaking work into prioritized, shippable increments with defined acceptance criteria, a documented Definition of Done, estimation, and risk identification via a risk register. A Project Manager (PM) and Product Manager (PdM) jointly coordinate project launch, while developers and QA roles contribute technical execution and quality validation.

Key project management workflows rely on the disciplined use of GitHub Projects and boards for task tracking, employing standard columns such as Backlog, In Progress, QA, and Done. Small, frequently merged pull requests are encouraged, with requirements for linking to tracked issues and including acceptance criteria in the PR description. Automated CI pipelines enforce test and linting requirements before reviews, and a defined policy (such as minimum reviewer approvals) must be met before merging. Regular demos, risk register updates, and metric monitoring (such as velocity and burndown) help teams stay aligned on progress and surface blockers early.

Personas within OctoAcme are explicitly defined to ensure accountability. Project Managers handle delivery coordination, risk management, and status reporting. Product Managers focus on defining product outcomes, backlog prioritization, and stakeholder engagement. Developers are responsible for implementation, testing, and contributing to design and planning, while QA engineers ensure features meet acceptance criteria before release. The documentation emphasizes **psychological safety**, **data-informed decisions**, and **clear ownership** as guiding principles—each project mandates a named PM and PdM for accountability.

Communication at OctoAcme is intentionally structured and frequent. Standard cadences include twice-weekly standups for status and blockers, weekly PM + PdM syncs, and monthly stakeholder updates. Retrospectives occur after each release or milestone, capturing learnings and action items for continuous improvement. Escalation paths for blockers and incidents are detailed across team, product lead, and sponsor levels, ensuring risks are addressed at the right altitude. All of this is underpinned by a focus on quality: new logic is covered by unit and integration tests, end-to-end smoke tests are run before releases, and manual QA or acceptance checks are performed as needed. Security scanning in CI and incident/rollback processes round out a robust quality assurance practice.

---

## Guiding Principles

- **Customer-first:** prioritize customer value and usability in every decision.
- **Iterative delivery:** deliver small, testable increments rather than big-bang releases.
- **Clear ownership:** every project has a named PM and PdM accountable for delivery and outcomes.
- **Data-informed decisions:** measure impact and iterate based on evidence.
- **Psychological safety:** encourage feedback, learning, and open communication.

---

## Process Documents

The following documents provide actionable guidance, templates, and checklists for each phase of the project lifecycle. Click a link to jump directly to the relevant process doc.

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management approach, core roles, key artifacts, and communication cadence. |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and produce the project one-pager. |
| [Project Planning](./octoacme-project-planning.md) | How to define scope, build a sprint backlog, set milestones, and establish a Definition of Done. |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery workflows including board usage, PR practices, CI requirements, and progress monitoring. |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication templates, and escalation paths. |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Release checklist, deployment steps, smoke testing, rollback procedures, and post-release verification. |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives, capture learnings, and turn action items into durable process improvements. |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Definitions, responsibilities, and communication norms for each role: PM, PdM, Developers, QA, and Stakeholders. |

---

## Keeping This README Up to Date

This README is the front door to OctoAcme's process knowledge. Please follow these guidelines to keep it accurate and useful:

1. **When adding a new process document** to `docs/`, add a corresponding row to the table above with a short description and a relative link.
2. **When renaming or restructuring a document**, update the link and description in the table.
3. **When major process changes are introduced**, update the overview paragraphs above to reflect the new approach.
4. **Review this file** as part of every retrospective to ensure it still accurately represents the team's processes.
