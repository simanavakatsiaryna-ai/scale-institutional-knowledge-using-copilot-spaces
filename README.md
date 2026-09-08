# OctoAcme Project Management Processes

This repository houses OctoAcme’s project management process documents. These guides describe how we initiate, plan, execute, release, and improve work across teams. The goal is to provide a single, consistent source of truth that helps new and existing team members understand our lifecycle, roles, responsibilities, communication cadence, and quality expectations.

OctoAcme runs projects through a stage-gated lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. Projects start with a concise One-pager to capture the problem, measurable outcomes, stakeholders, and a high-level timeline. Planning turns approved initiatives into a prioritized backlog with clear acceptance criteria and estimates. Execution focuses on delivering small, testable increments using the project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request workflow. Releases are validated through pre-release checks, smoke tests, and rollback plans, and each workstream closes with retrospectives to capture learnings and action items.

Roles and ownership are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, schedules, and risks; Developers implement and test features; QA validates acceptance criteria; and Stakeholders provide inputs and approvals. Communication is structured around daily standups for team-level coordination, weekly delivery syncs for progress and risk review, and demos at the end of sprints or milestones. Escalation paths are defined (team → PM → Product Lead → Sponsor) and incident communications follow a triage and blameless post‑mortem approach.

Quality assurance is integrated into the pipeline. The docs prescribe unit and integration tests, end-to-end smoke tests for critical flows, CI-enforced linting and security scans, and manual QA when needed. Release checklists and playbooks ensure deployments are observable and recoverable, while retrospectives and tracked action items drive continuous improvement.

Documentation by Project Phase

- Project Initiation
  - [Project Initiation Guide](./docs/octoacme-project-initiation.md) — Validate business need, create the One‑pager, align stakeholders.
- Project Planning
  - [Project Planning Guide](./docs/octoacme-project-planning.md) — Prioritize backlog, estimate scope, define Definition of Done.
- Execution & Tracking
  - [Execution & Tracking Guide](./docs/octoacme-execution-and-tracking.md) — Team rhythm, workflows, PR conventions, blocker escalation.
- Release & Deployment
  - [Release & Deployment Guide](./docs/octoacme-release-and-deployment.md) — Release types, pre-release checks, rollback playbooks.
- Close & Retrospective
  - [Retrospective & Continuous Improvement](./docs/octoacme-retrospective-and-continuous-improvement.md) — Run retrospectives, track action items, measure impact.

Cross-cutting Guidance

- [Project Management Overview](./docs/octoacme-project-management-overview.md) — High-level principles, lifecycle, and artifacts.
- [Risk Management & Communication](./docs/octoacme-risks-and-communication.md) — Risk register, stakeholder communication templates, escalation.
- [OctoAcme Personas](./docs/octoacme-roles-and-personas.md) — Role definitions for Product, Project, Development, and QA.

How to Contribute

To propose additions or changes to these process documents, use the "Add Content to Project Management Process Docs" issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml. That template collects the target document, a summary of the update, rationale, suggested content, and acceptance criteria. For larger changes, open a branch and a PR with links to relevant issues and reviewers.

If you have questions or need help applying these processes to a specific project, contact the Project Management team or open an issue in this repo.
