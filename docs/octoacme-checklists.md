# OctoAcme — Checklists & Templates

## Purpose
Provide reusable checklists that reduce ambiguity in handoffs and improve the consistency of common project activities. Use these templates as-is or adapt them for your project.

---

## Definition of Ready (DoR) — Backlog Item Checklist

A backlog item is **Ready** for sprint planning when all of the following are true:

### Problem & Value
- [ ] Problem statement or user story is clearly written (As a ___, I want ___, so that ___)
- [ ] Business value and impact are understood and documented
- [ ] Success criteria / acceptance criteria are defined and unambiguous
- [ ] KPIs or metrics that the item contributes to are identified (coordinate with Data Analyst)

### Design & UX
- [ ] UX flows, wireframes, or mockups are available and approved (if UI work is involved)
- [ ] Accessibility requirements are noted (coordinate with UX Designer)
- [ ] Any design dependencies are resolved or explicitly deferred

### Technical Readiness
- [ ] Technical approach is understood by the implementing developer(s)
- [ ] Architecture or integration decisions have been reviewed (coordinate with Solutions Architect where needed)
- [ ] External dependencies, APIs, or service contracts are identified and available
- [ ] Non-functional requirements (performance, security, scalability) are noted

### Estimation & Scope
- [ ] Item is estimated (story points or T-shirt size)
- [ ] Item can be completed within one sprint (or split if larger)
- [ ] Owner / assignee is identified

### QA & Testing
- [ ] Test cases or QA approach is documented
- [ ] Test environment is available (coordinate with DevOps / Platform Engineer)

---

## Kickoff Checklist

Use this checklist before or during the project kickoff meeting.

### Before Kickoff
- [ ] Project One-pager / charter is drafted and shared in advance
- [ ] Key stakeholders and team members are invited
- [ ] Agenda is prepared (problem, goals, roles, timeline, next steps)
- [ ] Relevant background materials (design specs, architecture notes) are linked
- [ ] UX Designer has initial research or context if user-facing work is in scope
- [ ] Solutions Architect has reviewed technical scope and flagged any early risks

### During Kickoff
- [ ] Problem statement and goals are confirmed by the team
- [ ] Roles and responsibilities are reviewed (see [Roles & Personas](./octoacme-roles-and-personas.md))
- [ ] Success metrics / KPIs are agreed upon
- [ ] High-level timeline and milestones are reviewed
- [ ] Initial risk and dependency list is reviewed
- [ ] Decisions and open questions are captured

### After Kickoff
- [ ] Meeting notes and decisions published to the project repo
- [ ] Open questions have assigned owners and due dates
- [ ] Backlog creation and refinement sessions are scheduled
- [ ] RACI / ownership map reviewed by the team (see [RACI Ownership Map](./octoacme-raci-ownership-map.md))
- [ ] Communication cadence is agreed and calendar invites are sent

---

## Release Readiness Checklist

Use this checklist before promoting a build to production. See also [Release & Deployment Guide](./octoacme-release-and-deployment.md) for the Deployment Checklist.

### Functional & Quality
- [ ] All acceptance criteria for in-scope items are met
- [ ] All PRs for this release are merged and CI is green
- [ ] Security scan passed (no new critical/high vulnerabilities unresolved)
- [ ] QA sign-off received for the release candidate
- [ ] Regression tests (automated and/or manual) completed

### Infrastructure & Deployment (coordinate with DevOps / Platform Engineer)
- [ ] Deployment pipeline is configured for the target environment
- [ ] Infrastructure changes (if any) are reviewed and approved
- [ ] Database migrations tested in staging (if applicable)
- [ ] Rollback plan is documented and validated
- [ ] Monitoring, alerting, and observability are in place for new components

### Stakeholder & Communications
- [ ] Release notes are drafted and reviewed
- [ ] Stakeholder communication / announcement is prepared
- [ ] Support team is briefed on changes and known issues
- [ ] Deployment window is agreed with relevant teams

### Post-Release
- [ ] Post-deploy smoke tests are scheduled
- [ ] On-call / incident response coverage is confirmed for the release window
- [ ] Metrics and dashboards are reviewed within 24–48 hours of release (coordinate with Data Analyst)
- [ ] Retrospective or post-release review is scheduled

---

## Related Documents
- [OctoAcme Roles & Personas](./octoacme-roles-and-personas.md)
- [OctoAcme RACI Ownership Map](./octoacme-raci-ownership-map.md)
- [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme Project Planning](./octoacme-project-planning.md)
- [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md)
