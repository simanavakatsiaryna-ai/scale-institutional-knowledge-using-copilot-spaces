# OctoAcme Project Management Processes

This folder centralizes OctoAcme’s project management process documents. These guides describe how we initiate, plan, execute, release, and improve work across teams. The goal is to provide a single, consistent source of truth that helps new and existing team members understand our lifecycle, roles, responsibilities, communication cadence, and quality expectations.

Overview

OctoAcme runs projects through a stage-gated lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. Projects begin with a concise One-pager to capture the problem, measurable outcomes, stakeholders, and a high-level timeline. Planning turns approved initiatives into a prioritized backlog with clear acceptance criteria and estimates. Execution focuses on delivering small, testable increments using the project board (Backlog → Ready → In Progress → In Review → QA → Done), a disciplined pull request workflow, and a steady team rhythm (daily standups, weekly delivery syncs, and demos). Releases follow a checklist-driven process including pre-release verification, smoke tests, and rollback plans. Each project closes with a retrospective that converts learnings into tracked action items.

Key Workflows & Practices

- Backlog & Board: Use a project board with columns Backlog → Ready → In Progress → In Review → QA → Done. Capture dependencies and escalate during weekly syncs.
- Pull Requests: Keep PRs small (<= 400 lines when possible), include the linked issue and acceptance criteria, run CI and security scans before requesting review, and require approvals per team policy.
- Testing & QA: Implement unit and integration tests, run end-to-end smoke tests for critical flows, enforce linting and security scans in CI, and perform manual QA for feature acceptance when needed.
- Releases: Categorize releases (patch/minor/major), prepare release notes and rollback plans, deploy to staging with smoke tests prior to production, and run post-deploy verifications.

Roles & Communication

- Product Managers: Define outcomes, prioritize the backlog, and measure success.
- Project Managers: Coordinate delivery, manage risks, schedules, and stakeholder communication.
- Developers: Implement, test, and document features.
- QA/Testing: Validate acceptance criteria and run test plans.
- Stakeholders: Provide inputs and approvals.

Communication cadence includes daily standups (15 minutes) for progress and blockers, weekly delivery syncs for progress reviews and risk escalation, and milestone demos. Escalation path: team → PM → Product Lead → Sponsor. Incident communications follow a triage summary and blameless post-incident retrospective.

Documentation by Project Phase

- Project Initiation
  - [Project Initiation Guide](../docs/octoacme-project-initiation.md) — Problem validation, One-pager, stakeholder alignment.
- Project Planning
  - [Project Planning Guide](../docs/octoacme-project-planning.md) — Backlog breakdown, estimates, Definition of Done.
- Execution & Tracking
  - [Execution & Tracking Guide](../docs/octoacme-execution-and-tracking.md) — Team rhythm, workflows, PR conventions, blocker escalation.
- Release & Deployment
  - [Release & Deployment Guide](../docs/octoacme-release-and-deployment.md) — Release types, pre-release checks, rollback playbooks.
- Close & Retrospective
  - [Retrospective & Continuous Improvement](../docs/octoacme-retrospective-and-continuous-improvement.md) — Retros, action items, follow-up.

Cross-cutting Guidance

- [Project Management Overview](../docs/octoacme-project-management-overview.md) — Principles, lifecycle, artifacts.
- [Risk Management & Communication](../docs/octoacme-risks-and-communication.md) — Risk register, stakeholder communication templates, escalation.
- [OctoAcme Personas](../docs/octoacme-roles-and-personas.md) — Role definitions for Product, Project, Development, and QA.

How to Contribute

Use the "Add Content to Project Management Process Docs" issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml to request changes or additions. For larger edits, open a branch and a PR that links to the issue and includes reviewers.
