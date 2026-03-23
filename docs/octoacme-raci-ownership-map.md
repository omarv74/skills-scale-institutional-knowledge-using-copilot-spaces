# OctoAcme — RACI Ownership Map

## Purpose
Provide a lightweight accountability reference showing which roles are **Responsible**, **Accountable**, **Consulted**, or **Informed** for key lifecycle activities. Use this map to resolve ambiguity and ensure clear ownership across the project team.

## RACI Key
| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final decision-maker |
| **C** | **Consulted** — provides input before/during; two-way communication |
| **I** | **Informed** — kept up to date; one-way communication |

---

## Lifecycle Activity Ownership Map

| Activity | Project Manager | Product Manager | Scrum Master | Developers | QA | UX Designer | DevOps / Platform Eng. | Solutions Architect | Data Analyst | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| **INITIATION** | | | | | | | | | | |
| Define problem statement & goals | C | A/R | I | C | I | C | I | C | C | C |
| Identify stakeholders & comms plan | A/R | C | I | I | I | I | I | I | I | C |
| Draft Project One-pager / charter | A/R | R | I | C | I | C | I | C | I | A |
| Define success metrics / KPIs | C | A/R | I | I | I | C | I | C | R | C |
| Initial user research & UX framing | I | C | I | I | I | A/R | I | C | C | C |
| Approve initiation / go-to-planning | C | C | I | I | I | I | I | I | I | A |
| **PLANNING** | | | | | | | | | | |
| Run project kickoff | A/R | C | R | C | C | C | C | C | I | C |
| Backlog creation & prioritization | C | A/R | R | C | C | C | I | C | C | I |
| Definition of Ready (DoR) | C | C | A/R | R | R | C | I | C | I | I |
| Architecture & integration design | I | C | I | C | I | C | C | A/R | I | I |
| UX flows & design specifications | I | C | I | C | C | A/R | I | C | I | I |
| Release plan & milestone map | A/R | C | C | C | C | I | C | C | I | I |
| Infrastructure & CI/CD planning | C | I | I | C | C | I | A/R | C | I | I |
| **EXECUTION** | | | | | | | | | | |
| Sprint planning & ceremony facilitation | C | C | A/R | R | C | C | I | C | I | I |
| Feature implementation | I | C | C | A/R | C | C | I | C | I | I |
| Design implementation & handoff | I | C | C | C | C | A/R | I | C | I | I |
| Code reviews & technical guidance | I | I | I | A/R | C | I | C | R | I | I |
| QA & acceptance testing | C | C | C | C | A/R | C | C | C | I | I |
| CI/CD pipeline management | I | I | I | C | C | I | A/R | C | I | I |
| Impediment removal | C | C | A/R | R | R | R | R | C | I | I |
| Risk register updates | A/R | C | C | C | C | C | C | C | I | I |
| Progress & metrics reporting | A/R | C | C | I | I | I | I | I | R | I |
| **RELEASE** | | | | | | | | | | |
| Release readiness assessment | A/R | C | C | C | C | C | R | C | I | I |
| Deployment execution | C | I | I | C | C | I | A/R | C | I | I |
| Smoke & post-deploy verification | C | I | C | C | A/R | C | R | C | I | I |
| Release notes & stakeholder comms | A/R | R | C | C | I | I | C | I | I | I |
| Rollback decision (if needed) | A | C | C | C | C | I | R | C | I | I |
| **RETROSPECTIVE & CLOSE** | | | | | | | | | | |
| Facilitate retrospective | C | C | A/R | R | R | R | R | R | R | I |
| Action item tracking | A/R | C | R | C | C | C | C | C | C | I |
| Outcome / metrics review | C | A/R | I | C | I | C | I | C | R | C |
| Lessons learned documentation | A/R | C | R | C | C | C | C | C | C | I |

---

## Notes
- A single cell may show `A/R` where the same role is both accountable and doing the work.
- QA role is referenced throughout but not yet expanded in the Personas doc; this reflects standard cross-functional team composition.
- Adjust this table as your team composition evolves. For a full description of each role, see [OctoAcme Roles & Personas](./octoacme-roles-and-personas.md).
