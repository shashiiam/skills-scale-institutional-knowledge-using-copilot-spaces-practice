# Role Handoff Checklist

Purpose: practical checklist to make cross-role handoffs explicit and reduce miscommunication.

- For each backlog item/feature, confirm the following before "Ready":
  - [ ] Product Manager: success metrics & acceptance criteria documented
  - [ ] Technical Lead: high-level approach and major risks documented
  - [ ] UX Designer: designs and accessibility notes attached (if applicable)
  - [ ] Data Analyst: instrumentation requirements defined (if metrics required)
  - [ ] QA: testing strategy and acceptance tests defined
  - [ ] PM: release constraints/coordination notes included

- Pre-release (before merge / release window):
  - [ ] Release Engineer: deployment plan and rollback procedure documented
  - [ ] Observability Owner: alerts/runbooks prepared for new behavior
  - [ ] Security Liaison: security review completed (if required)
  - [ ] Stakeholder(s) notified for feature-impact (if applicable)

- Post-release:
  - [ ] Observability: smoke checks executed and results documented
  - [ ] Data: metrics validated in dashboards
  - [ ] PM/PdM: confirm success metrics and next steps
  - [ ] Retrospective: capture any handoff issues as action items

- Communication & Ownership:
  - For each checklist item, add the owner (name) and expected completion date in the project board or issue.

Usage:
- Add this checklist to the project issue template or link from the project README.
- Use it during planning grooming and before scheduling releases.
