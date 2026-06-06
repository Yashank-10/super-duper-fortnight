# Octoacme — Roles and Personas

This document describes project roles and personas, their primary responsibilities, and how they interact across the project lifecycle. Use these definitions to clarify ownership, accelerate handoffs, and reduce coordination friction.

## How to use this document
- Each persona includes a short description, key responsibilities, collaboration points, escalation contacts, and example tasks.
- For new roles, follow the Role Responsibility Template in docs/templates/role-responsibility-template.md.

---

## Project Manager (PM) / Delivery Lead
- Purpose: Owns project schedule, scope, and stakeholder communications.
- Responsibilities:
  - Define project plan and milestones.
  - Track progress, risks, and issues.
  - Coordinate cross-functional work and stakeholder updates.
- Interactions:
  - Works with Product Owner on priorities.
  - Coordinates with Technical Lead, QA Lead, and Release Engineer on delivery timelines.
- Escalation:
  - Primary escalation for timeline, resource, and external dependency issues.

---

## Product Owner (PO)
- Purpose: Owns product vision, backlog, and prioritization.
- Responsibilities:
  - Maintain and prioritize backlog.
  - Define acceptance criteria for features.
  - Validate that deliverables meet business needs.
- Interactions:
  - Collaborates with PM, Business Analyst, and QA Lead during planning and acceptance.
- Escalation:
  - Business/product decisions and prioritization conflicts.

---

## Technical Lead (Tech Lead)
- Purpose: Guide technical approach and ensure engineering quality.
- Responsibilities:
  - Define architecture and technical standards.
  - Review design and code for major deliverables.
  - Mentor engineers and identify technical risks.
- Interactions:
  - Works with Developers, QA Lead, and PM to align technical plans with schedules.
- Escalation:
  - Technical trade-offs, major design changes, and production incidents.

---

## QA Lead
- Purpose: Ensure product quality through structured testing and verification.
- Responsibilities:
  - Define QA strategy, test plans, and acceptance testing approach.
  - Coordinate test cycles, defect triage, and UAT.
  - Validate acceptance criteria and sign off on releases.
- Interactions:
  - Engages with Developers, Tech Lead, PO, and BA to define test scope and acceptance criteria.
- Escalation:
  - Critical quality issues and release-blocking defects.

---

## Business Analyst (BA)
- Purpose: Translate stakeholder needs into actionable, testable requirements.
- Responsibilities:
  - Elicit requirements and document user stories and acceptance criteria.
  - Facilitate stakeholder reviews and clarify requirements to the delivery team.
- Interactions:
  - Works with PO, Developers, QA, and UX to ensure requirements are complete and testable.

---

## Developer / Engineering Team
- Purpose: Implement features and maintain the codebase.
- Responsibilities:
  - Deliver code that meets acceptance criteria and quality standards.
  - Write unit/integration tests and respond to defects.
- Interactions:
  - Collaborates with Tech Lead, QA Lead, and PO for clarity on requirements.

---

## Release Engineer / Release Manager
- Purpose: Own deployment, release pipelines, and rollback plans.
- Responsibilities:
  - Maintain CI/CD pipelines and coordinate release steps.
  - Validate deployment readiness and perform or supervise deployments.
  - Document rollback procedures and post-release verification steps.
- Interactions:
  - Works with PM, Tech Lead, QA Lead, and on-call engineers during releases.

---

## Scrum Master / Delivery Facilitator
- Purpose: Facilitate team ceremonies and remove impediments to flow.
- Responsibilities:
  - Run retrospectives, stand-ups, and sprint planning.
  - Track team process health and continuous improvement.
- Interactions:
  - Partners with PM and Tech Lead to resolve team impediments.

---

## Stakeholder Representative / Domain SME
- Purpose: Provide domain expertise and final business acceptance.
- Responsibilities:
  - Validate business requirements and acceptance criteria.
  - Participate in UAT and sign-off where required.

---

## UX Designer
- Purpose: Own product UX and ensure design consistency.
- Responsibilities:
  - Provide design deliverables and acceptance criteria for UX.
  - Participate in design reviews and usability testing.

---

## Example: Interaction Map (high level)
- Planning: PO + BA + PM + Tech Lead define scope & acceptance; QA validates testability.
- Build: Developers implement; Tech Lead reviews; QA prepares test plans.
- Release: Release Engineer, PM, QA, and Tech Lead verify readiness and execute release plan.

---

## RACI-style guidance
- For each major deliverable define: Responsible, Accountable, Consulted, Informed.
- Include RACI table entries in feature-level docs or release checklists where helpful.

(End of roles document.)
