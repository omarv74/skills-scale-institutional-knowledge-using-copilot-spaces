# OctoAcme Project Management Docs

This folder is the institutional knowledge hub for OctoAcme's program and process documentation. It captures how we initiate, plan, execute, release, and retrospect on cross-functional projects so that any team member—new or seasoned—can quickly understand our approach and find the right guidance.

## Overview

OctoAcme runs projects through a lightweight, repeatable lifecycle: **initiation → planning → execution/tracking → release/deployment → close/retrospective**. In the initiation phase the team validates the business need, defines measurable outcomes using a Project One-pager (problem statement, SMART objectives, success metrics), identifies stakeholders, drafts an initial timeline, and captures early risks and dependencies. A clear decision gate—success metrics understood, stakeholder alignment confirmed, team availability secured—must be met before work progresses to planning.

Planning turns an approved initiative into a concrete delivery plan. The team holds a kickoff, builds a prioritized backlog with acceptance criteria, estimates work (T-shirt sizing or story points), documents a Definition of Done, and maps milestones and releases. Risks and cross-team dependencies are tracked in a **Risk Register** and reviewed at weekly syncs so that timelines and responsibilities stay realistic. Execution is managed through a consistent team rhythm: the delivery board moves work through **Backlog → Ready → In Progress → In Review → QA → Done**, with daily standups, a weekly delivery sync, and end-of-sprint demos keeping the team aligned. Blockers escalate in defined levels—team triage, PM + Product Lead coordination, then sponsor-level escalation for business-impacting issues—so that decisions never stall.

Roles are kept unambiguous to preserve clear ownership. The **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; the **Product Manager (PdM)** defines outcomes and prioritizes the backlog; **Developers** implement features, collaborate on design and testability, and contribute to estimates; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide inputs and approvals. Communication follows a structured cadence—weekly PM/PdM sync, twice-weekly delivery standups, monthly stakeholder updates—with a single source of truth (project README or release doc) for status and a standard Weekly Status template covering progress, next steps, risks/blockers, and decisions needed. Escalation flows from team level to PM to Product Lead to Sponsor, with a separate security-incident runbook for security issues.

Quality and release discipline close the loop. Engineers submit small, reviewable pull requests linked to issues and acceptance criteria, with required approvals and CI checks (lint, unit and integration tests, security scanning) before merge. Releases follow a checklist-driven process—release notes, rollback/mitigation plan, staging validation, post-deploy verification—and each project closes with a **retrospective** that converts learnings into owned, time-bound action items tracked back in the backlog.

## Key docs in this folder

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
