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

## QA / Testing

(Existing QA/testing responsibilities - unchanged.)

---

## Additional Cross-functional & Practitioner Personas (NEW)

The following personas are proposed to clarify ownership, interactions, and accountability across planning, execution, release, and incident response.

### Technical Lead / Architect
- Role Summary: Provides technical direction and architectural decisions for the project.
- Responsibilities:
  - Define and communicate high-level architecture and design patterns.
  - Review major design decisions and significant PRs impacting architecture.
  - Ensure non-functional requirements (scalability, security, performance) are addressed.
  - Mentor engineers and guide technical trade-offs.
- Interactions:
  - Works closely with Developers on design/implementation and code reviews.
  - Advises PM/PdM on technical feasibility, risks, and schedule impacts.
  - Coordinates with Release/Platform Engineer for deployment constraints and environment needs.

### Engineering Manager
- Role Summary: Manages engineering team health, capacity, and career development.
- Responsibilities:
  - Resource allocation and capacity planning.
  - Performance coaching and career development.
  - Resolve personnel and cross-team conflicts.
  - Support hiring and onboarding.
- Interactions:
  - Collaborates with PM to align resourcing and timelines.
  - Works with Technical Lead to promote engineering best practices.
  - Supports Developers by clearing organizational blockers.

### UX / Product Designer
- Role Summary: Owns product UX and design deliverables that ensure usability and accessibility.
- Responsibilities:
  - Produce user flows, wireframes, high-fidelity designs, and prototypes.
  - Define UX acceptance criteria and participate in usability testing.
  - Perform accessibility reviews and remediation recommendations.
- Interactions:
  - Partners with PdM on requirements and success metrics.
  - Handoffs specs to Developers and supports implementation questions.
  - Participates in sprint planning, demos, and acceptance reviews.

### Data Analyst / Data Engineer
- Role Summary: Ensures projects capture required data and produce measurable insights.
- Responsibilities:
  - Define instrumentation and data collection requirements.
  - Build dashboards and validate metrics used for success criteria.
  - Ensure data quality and advise on analytics trade-offs.
- Interactions:
  - Works with PdM to define measurable success metrics.
  - Coordinates with Developers/Platform to implement instrumentation.
  - Supports PM in tracking metric-driven milestones and reporting.

### Release / Platform Engineer
- Role Summary: Owns CI/CD pipelines, staging environments, and deployment reliability.
- Responsibilities:
  - Build and maintain deployment pipelines, infrastructure-as-code, and staging environments.
  - Define rollback strategies and assist with release automation.
  - Support smoke tests, canary rollouts, and post-deploy verifications.
- Interactions:
  - Coordinates deploy windows and rollback decisions with PM.
  - Assists Developers during release and incident activities.
  - Works with Observability Owner and Data teams to ensure monitoring is in place.

### Security Liaison / Security Engineer
- Role Summary: Provides security guidance and ensures compliance with security standards.
- Responsibilities:
  - Conduct threat modeling and security reviews for features.
  - Coordinate security scans and remediation workflows.
  - Advise on secure coding practices and compliance needs.
- Interactions:
  - Reviews designs/PRs with Developers and Technical Lead.
  - Flags security-related risks to PM and escalates when necessary.
  - Works with Release/Platform to ensure secure deployment practices.

### On-call / Observability Owner
- Role Summary: Maintains production reliability and alerting for the product area.
- Responsibilities:
  - Define alerting thresholds, runbooks, and on-call rotations.
  - Participate in incident response and post-incident reviews.
  - Drive improvements to observability and operational runbooks.
- Interactions:
  - Partners with Release/Platform and Developers to ensure operability.
  - Reports incidents and severity to PM and stakeholders.
  - Works with Data and Security where relevant for incident triage.

### Business Analyst / Domain SME
- Role Summary: Acts as a proxy for specialized domain knowledge and business rules.
- Responsibilities:
  - Translate stakeholder needs into detailed acceptance criteria and edge cases.
  - Validate scenarios and support acceptance testing.
  - Maintain domain documentation and act as subject-matter contact.
- Interactions:
  - Partners with PdM and Stakeholder Representatives to clarify requirements.
  - Works with QA to design acceptance tests and test data.
  - Supports Developers by clarifying domain rules during implementation.

---

## How to adopt these personas
- Add a short listing of these personas to project READMEs where relevant.
- For each project, identify which personas are in-scope and assign named owners.
- Use the Role Handoff Checklist (docs/role-handoff-checklist.md) to document critical interactions at planning, pre-release, and post-release stages.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
