# OctoAcme Project Management Docs

This repository contains the shared process documentation for running OctoAcme cross-functional projects. Use this README as the entry point; the linked documents provide detailed guidance, checklists, templates, and role-specific information.

## How OctoAcme Runs Projects

OctoAcme uses a customer-first, iterative, and data-informed approach with clear ownership and a focus on psychological safety. Projects move through a lightweight lifecycle:

1. **Initiation** — Validate the problem and expected outcome, identify stakeholders, define success metrics, and decide whether to proceed to planning.
2. **Planning** — Turn the approved initiative into a prioritized backlog, define acceptance criteria and the Definition of Done, estimate work, and align milestones, dependencies, risks, and responsibilities.
3. **Execution and tracking** — Deliver small increments through the project board and pull request workflow. Use regular standups, delivery syncs, demos, testing, reviews, and risk tracking to maintain progress and transparency.
4. **Release and deployment** — Confirm acceptance criteria, CI and security checks, release notes, smoke tests, and rollback plans before deploying. Verify the deployment and communicate the release to stakeholders.
5. **Retrospective and continuous improvement** — Review what went well and what could improve after each sprint, release, milestone, or incident. Track a small number of owned action items and measure their impact.

### Core Roles

- **Project Manager (PM):** Coordinates delivery, schedules, risks, dependencies, communications, and project documentation.
- **Product Manager (PdM):** Defines outcomes, prioritizes the backlog, and measures customer and business impact.
- **Developers:** Design, implement, test, review, and document solutions that meet acceptance criteria.
- **QA/Testing:** Validates quality and feature acceptance through appropriate automated and manual testing.
- **Stakeholders:** Provide input, context, decisions, and approvals.

### Shared Practices

- Maintain a single source of truth for status, risks, dependencies, and decisions.
- Communicate through agreed cadences, including standups, PM/PdM alignment, delivery syncs, demos, and stakeholder updates.
- Identify, assess, mitigate, and monitor risks; escalate from the team to the PM, Product Lead, and sponsor when needed.
- Apply quality practices such as unit and integration tests, end-to-end smoke tests for critical flows, CI, linting, security scanning, and manual QA when appropriate.
- Capture learnings in retrospectives and convert them into actionable, owned improvements.

## Process Documents

- [Project Management Overview](docs/octoacme-project-management-overview.md) — Principles, roles, lifecycle, artifacts, and communication cadence.
- [Project Initiation Guide](docs/octoacme-project-initiation.md) — Validate and authorize work, align stakeholders, and prepare the project one-pager.
- [Project Planning](docs/octoacme-project-planning.md) — Build the backlog, release plan, Definition of Done, and initial risk and dependency plan.
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) — Manage day-to-day delivery, quality, progress reporting, metrics, and blocker escalation.
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md) — Maintain the risk register and communicate status, incidents, and escalations.
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md) — Prepare, deploy, verify, communicate, and roll back releases safely.
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and track improvement actions.
- [Roles & Personas](docs/octoacme-roles-and-personas.md) — Detailed responsibilities, goals, and communication patterns for common roles.
