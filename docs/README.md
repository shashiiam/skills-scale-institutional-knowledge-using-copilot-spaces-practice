# OctoAcme Project Management Process Docs

## Overview

OctoAcme uses a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decisions. This directory contains the complete OctoAcme project management process documentation.

## Project Lifecycle

All OctoAcme projects follow these phases:

1. **Initiation** → Validate business need and align stakeholders
2. **Planning** → Create actionable backlog and release plan
3. **Execution** → Build, test, and track progress
4. **Release** → Deploy with confidence and verify success
5. **Close & Retrospective** → Capture learnings and improve

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Framework

OctoAcme follows a structured, lifecycle-based project management approach grounded in clear ownership, iterative delivery, and data-informed decision-making. The organization applies five core phases—**Initiation, Planning, Execution, Release, and Close & Retrospective**—to manage cross-functional projects. Each project is led by a **Project Manager** (who coordinates schedules, risks, and communications) and a **Product Manager** (who defines outcomes, prioritizes the backlog, and measures success), supported by developers, QA/testing specialists, and stakeholders. This dual leadership model ensures both delivery accountability and product value alignment.

Communication is structured through a regular cadence: **weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates**, with ad-hoc escalations for blockers. OctoAcme uses a three-level escalation path (team → PM → Product Lead → Sponsor) to surface risks and dependencies quickly. The organization maintains a **Risk Register** (tracking ID, description, impact, likelihood, owner, and mitigation) updated weekly, and uses a single source of truth—typically a project README or GitHub Projects board—to communicate status, progress, and decisions to all stakeholders.

Quality and execution rigor are embedded throughout the lifecycle. OctoAcme enforces small pull requests (≤400 lines), requires automated testing and security scanning in CI, mandates at least one approval before merging, and conducts manual QA for feature acceptance when needed. The project board follows a standard workflow (Backlog → Ready → In Progress → In Review → QA → Done), and teams define a clear **Definition of Done** during planning. Pre-release requirements include passing all acceptance criteria, CI checks, security scans, and smoke tests, with a documented rollback plan.

## Process Documentation

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** - High-level introduction to OctoAcme processes, roles, and artifacts. Start here.
- **[Roles and Personas](./octoacme-roles-and-personas.md)** - Define typical roles (Developers, Product Managers, Project Managers) and responsibilities.

### Project Phases

- **[Project Initiation Guide](./octoacme-project-initiation.md)** - Steps to validate business need, align stakeholders, and authorize work.
- **[Project Planning](./octoacme-project-planning.md)** - Convert approved initiatives into actionable plans and prioritized backlogs.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Manage day-to-day execution, track progress, and maintain team rhythm.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** - Standardize release processes to reduce risk and improve observability.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and convert them into actionable improvements.

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Identify, manage, and communicate risks and dependencies throughout the project lifecycle.

## Quick Reference: When to Use Each Document

| Scenario | Document |
|----------|----------|
| Starting a new project | Project Initiation Guide |
| Planning work and creating backlog | Project Planning |
| Tracking daily progress and risks | Execution & Tracking |
| Preparing for a release | Release & Deployment Guide |
| After a project or sprint | Retrospective & Continuous Improvement |
| Managing cross-team risks | Risk Management & Communication |
| Understanding team roles | Roles and Personas |

## Key Contacts & Communication

- **Weekly PM sync**: Product Manager + Project Manager alignment
- **Twice-weekly standups**: Delivery team progress and blockers
- **Monthly stakeholder updates**: High-level status and decisions
- **Ad-hoc escalations**: Critical risks and blockers

## Contributing

These process docs are living documents. If you identify gaps, improvements, or best practices to share, please create an issue using the "Add Content to Project Management Process Docs" template.
