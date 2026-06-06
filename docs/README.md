# OctoAcme Project Management Docs

This folder contains OctoAcme's process documents for planning, executing, and improving cross-functional projects. Use this README as the single entry point to understand our approach, roles, and the key artifacts you should keep updated in each project repo.

## Quick overview of our project management processes
OctoAcme runs lightweight, iterative projects that emphasize delivering measurable customer value while keeping clear ownership and predictable delivery:

- Initiation: capture the problem, success metrics, stakeholders, and a lightweight one-pager to authorize planning.
- Planning: break work into shippable backlog items, estimate, map milestones, and capture risks and dependencies.
- Execution & Tracking: use a project board with defined workflow columns, small PRs, CI gating, regular demos, and a weekly rhythm for status and escalation.
- Risk & Communication: maintain a risk register, use regular stakeholder updates, and follow defined escalation paths for business- or security-impacting issues.
- Release & Deployment: follow pre-release checks, automated pipelines where possible, rollback plans, and post-deploy verifications.
- Retrospective & Continuous Improvement: run timeboxed retrospectives, track action items with owners and due dates, and measure the impact of improvements.

## Docs index
- Project Management Overview: octoacme-project-management-overview.md
- Project Initiation Guide: octoacme-project-initiation.md
- Project Planning: octoacme-project-planning.md
- Execution & Tracking: octoacme-execution-and-tracking.md
- Risk Management & Communication: octoacme-risks-and-communication.md
- Release & Deployment Guide: octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement: octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: octoacme-roles-and-personas.md

## How to use and maintain these docs
- Keep the project one-pager, roadmap, and release notes in the project repo.
- Update the relevant doc(s) in this folder when a process changes or a new checklist is introduced.
- For process changes, use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` template to propose additions or edits, and link the issue to the PR.
- Add process-specific artifacts into `.copilot/` if you want Copilot Spaces to use them as context.

## Acceptance criteria (for README and new/updated process docs)
- Content aligns with existing process docs.
- The update improves clarity or closes a documented gap.
- Proposed content has been reviewed with stakeholders when required.

## Related issue
This change implements the content proposed in issue #2 (Add README for OctoAcme Project Management Docs).
