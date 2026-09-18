# OctoAcme Project Management Docs

This repository contains the core process documentation OctoAcme uses to guide project work from concept through delivery. The operating model follows a clear lifecycle: initiation, planning, execution, release, and closeout. During initiation, teams validate the business need, define goals and success metrics, and create a lightweight project one-pager that captures stakeholders, milestones, risks, and resource needs. Planning then turns this direction into a prioritized backlog, concrete acceptance criteria, a definition of done, and a release plan so the work is actionable and measurable.

OctoAcme’s project management model emphasizes clear roles and shared accountability. Developers build and validate software, Product Managers define customer value and prioritize what matters most, Project Managers coordinate schedules, risks, communication, and project health, and stakeholders provide sponsorship and decisions. The documents also reinforce guiding principles such as customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety, which helps teams collaborate effectively and learn quickly during execution.

Communication is built into the workflow through daily standups, weekly delivery syncs, milestone demos, and stakeholder updates. Risks and dependencies are tracked in a risk register and escalated through a defined path from team-level triage to PM, Product Lead, and sponsor-level intervention when needed. This ensures the team can surface blockers early, align on priorities, and maintain a shared source of truth for progress, decisions, and escalation needs.

Quality assurance is an explicit part of the delivery process. OctoAcme expects teams to use CI, write unit and integration tests where applicable, run smoke tests on critical flows, and complete security scans before release. Pull requests are expected to be small and reviewable, include issue links and acceptance criteria, and require at least one approval before merge. Release and deployment work includes staging validation, rollback planning, and post-deploy verification, while retrospectives capture lessons learned and convert them into backlog action items. Together, these practices create a repeatable, transparent project rhythm that balances speed, quality, and accountability.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — high-level overview of roles, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — how to validate ideas, align stakeholders, and create a lightweight plan.
- [Project Planning](octoacme-project-planning.md) — backlog creation, sprint planning, risks, dependencies, and delivery planning.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — daily delivery rhythm, PR workflow, blockers, and reporting.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk register, escalation paths, and stakeholder communication practices.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release classification, deployment checklist, rollback, and incident response steps.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — how to capture lessons and turn them into action.
- [Roles and Personas](octoacme-roles-and-personas.md) — definitions of the core personas and responsibilities used across the program.

## Related issue template

- [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) — template for proposing updates to the project management process documentation.
