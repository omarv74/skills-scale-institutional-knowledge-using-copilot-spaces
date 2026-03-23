# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master / Delivery Facilitator enables the delivery team to operate effectively by facilitating agile ceremonies, coaching agile practices, removing impediments, and nurturing a healthy team culture.

### Responsibilities
- Facilitate sprint ceremonies: standups, planning, reviews, and retrospectives
- Coach team members on agile principles and practices
- Identify and remove impediments that slow delivery
- Track and improve team health, morale, and collaboration
- Shield the team from external distractions during sprint execution
- Surface systemic blockers to the Project Manager for escalation

### Goals
- Maximize team flow and reduce cycle time
- Foster a culture of continuous improvement
- Keep delivery cadence predictable and sustainable

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment log and action items shared with Project Manager
- Retrospective summaries and improvement tracking

### Interactions with Existing Roles
- **Project Manager:** Coordinate delivery rhythm, share impediment escalations, and align on cross-team dependencies.
- **Product Manager:** Collaborate on backlog refinement ceremonies and ensure stories meet the Definition of Ready before sprint planning.
- **Developers / QA:** Support delivery flow, coach on agile practices, and remove blockers that affect development and testing velocity.

---

## UX Designer / Product Designer

### Role Summary
The UX Designer / Product Designer ensures that features and products are designed with users in mind, creating user flows, wireframes, prototypes, and usability standards that guide development.

### Responsibilities
- Conduct user research and translate insights into design decisions
- Define user flows, wireframes, mockups, and interactive prototypes
- Ensure usability and accessibility standards are met
- Provide detailed design specifications and assets to developers
- Collaborate on design systems and reusable UI components
- Participate in usability testing and validate designs with end users

### Goals
- Deliver user-centered designs that reduce friction and increase satisfaction
- Align visual and interaction design with product goals
- Ensure accessibility compliance and inclusive design

### Typical Communication
- Design reviews and critiques with Product and Engineering
- Handoff documentation (e.g., Figma specs, annotated mockups)
- Usability test reports and research summaries

### Interactions with Existing Roles
- **Product Manager:** Collaborate on requirements, success outcomes, and validation of design decisions against business goals.
- **Developers:** Provide implementation guidance, answer design questions during development, and ensure specifications are followed accurately.
- **QA:** Partner on usability and accessibility testing to validate the final implementation against design intent.

---

## DevOps / Platform Engineer

### Role Summary
The DevOps / Platform Engineer owns the infrastructure, CI/CD pipelines, observability, and reliability practices that enable the delivery team to ship software safely and repeatedly.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage infrastructure-as-code and cloud/platform configuration
- Implement and monitor observability (logging, metrics, alerting, tracing)
- Enforce security controls and compliance within the deployment pipeline
- Support test environment provisioning for development and QA
- Coordinate release readiness and communicate deployment status

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize infrastructure risk and unplanned downtime
- Drive platform improvements that improve developer productivity

### Typical Communication
- Release readiness and deployment status updates
- On-call runbooks and incident playbooks
- Infrastructure change proposals and post-incident reviews

### Interactions with Existing Roles
- **Developers:** Automate build, test, and deployment workflows; support developer tooling and local environment consistency.
- **Project Manager:** Provide release readiness assessments and flag infrastructure risks that may affect timelines.
- **QA:** Provision and maintain test environments; integrate automated test suites into CI/CD pipelines.
- **Stakeholders:** Communicate release schedules, deployment windows, and any service-impacting maintenance as needed.

---

## Solutions Architect / Technical Lead

### Role Summary
The Solutions Architect / Technical Lead (when separate from individual contributors) provides architectural guidance, ensures design decisions align with business goals, and manages technical risk across the project.

### Responsibilities
- Define and document system architecture and integration patterns
- Evaluate technical trade-offs and recommend approaches
- Establish standards for non-functional requirements (performance, security, scalability)
- Identify and mitigate technical risks and dependencies early
- Guide developers on implementation patterns and best practices
- Review architectural decisions to ensure long-term maintainability

### Goals
- Ensure technical solutions are fit for purpose and scalable
- Reduce technical debt and architectural risk
- Align engineering decisions with business objectives and constraints

### Typical Communication
- Architecture decision records (ADRs) and design documents
- Technical design reviews with the engineering team
- Feasibility and trade-off discussions with Product and Project Managers

### Interactions with Existing Roles
- **Developers:** Provide architectural guidance, review technical designs, and support implementation of complex integration patterns.
- **Product Manager / Project Manager:** Advise on technical feasibility, surface trade-offs, and flag constraints that affect scope or timelines.
- **DevOps / Platform Engineer:** Align on platform constraints, infrastructure requirements, and deployment architecture.

---

## Data Analyst / Analytics Engineer

### Role Summary
The Data Analyst / Analytics Engineer defines success metrics, builds dashboards and reports, ensures proper instrumentation, and delivers data-driven insights to guide product and project decisions.

### Responsibilities
- Define and document key metrics, KPIs, and measurement frameworks
- Design and maintain dashboards and reports for ongoing monitoring
- Specify instrumentation and telemetry requirements for developers
- Analyze data to surface insights and inform product decisions
- Partner on A/B tests and outcome measurement for shipped features
- Support reporting and progress signals for project governance

### Goals
- Ensure meaningful metrics guide product and delivery decisions
- Provide clear visibility into project progress and product outcomes
- Reduce reliance on anecdote by making data accessible and actionable

### Typical Communication
- KPI dashboards and weekly metrics summaries
- Instrumentation requirements shared with development teams
- Analytical reports and outcome reviews tied to releases

### Interactions with Existing Roles
- **Product Manager:** Collaborate on defining KPIs, success metrics, and outcome measurement for product goals.
- **Developers:** Specify events, telemetry, and instrumentation requirements needed to support dashboards and analytics.
- **Project Manager:** Provide data-backed progress reporting signals and highlight metric trends relevant to delivery health.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For an overview of how each role maps to key lifecycle activities, see the [OctoAcme RACI Ownership Map](./octoacme-raci-ownership-map.md).
- For reusable handoff checklists (Definition of Ready, Release Readiness), see [OctoAcme Checklists & Templates](./octoacme-checklists.md).

