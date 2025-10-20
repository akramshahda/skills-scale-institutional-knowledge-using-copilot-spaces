# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents — a lightweight, living set of guidance the team uses to plan, execute, and improve project delivery. These docs centralize roles, rhythms, artifacts, checklists, and escalation paths so teams can deliver predictably and learn continuously.

Quick overview
- Purpose: centralize and share how OctoAcme runs projects — roles, rhythms, artifacts, and checklists so teams can deliver predictably and learn continuously.
- Principles: customer-first, iterative delivery, clear ownership, data-informed decisions, and psychological safety.
- Scope: applies to cross-functional projects that deliver product features, services, or integrations.

Project lifecycle (high-level)
1. Initiation — capture problem, success metrics, stakeholders, and go/no-go (see: octoacme-project-initiation.md).
2. Planning — create backlog, define Definition of Done, estimate, and map release milestones (see: octoacme-project-planning.md).
3. Execution & Tracking — run work via project board and PR conventions, keep CI and tests green, and use team rhythms to maintain momentum (see: octoacme-execution-and-tracking.md).
4. Release & Deployment — follow pre-release checklist, smoke tests, and rollback playbook for production releases (see: octoacme-release-and-deployment.md).
5. Retrospective & Continuous Improvement — capture learnings, convert to action items, and track impact (see: octoacme-retrospective-and-continuous-improvement.md).
6. Risk Management & Communication — maintain a Risk Register, communicate status to stakeholders, and follow escalation paths when needed (see: octoacme-risks-and-communication.md).

Team rhythm & artifacts
- Typical cadence: daily standups, weekly delivery sync, sprint demos/reviews, monthly stakeholder updates.
- Key artifacts: Project One-pager (charter), backlog & acceptance criteria, risk register, release notes, retrospective action items.
- Role expectations: PM (delivery & communications), PdM (outcome & prioritization), Developers (build & test), QA (validate acceptance). See octoacme-roles-and-personas.md for details.

How to use these docs
- Keep project-specific artifacts (Project One-pager, release notes, risk register) in the project repo under docs/ or the project README.
- Use the ".github/ISSUE_TEMPLATE/Add Content to Project Management Process Docs" template to propose changes to these central docs.
- When updating processes, prefer small, incremental PRs that include rationale and acceptance criteria so changes can be reviewed and versioned.
- Treat these as living docs — capture improvements and link retrospective action items or decisions to issues/PRs.

Files in this folder
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-risks-and-communication.md
- octoacme-roles-and-personas.md

Acceptance checklist for this README
- [ ] Content aligns with existing process docs
- [ ] Update improves discoverability and onboarding
- [ ] PR links to issue #2 for traceability and review

Contact / governance
- To propose a change to these docs: open a PR, reference the relevant issue or use the ISSUE_TEMPLATE, and request review from the Project Management owners.

(Adapted from OctoAcme process documents in this folder)
