# Release Checklist (Template)

Use this checklist for every release. Fill in owners and dates.

- Release identifier:
- Release owner: @
- Scheduled date/time:

Pre-release
- [ ] All critical/high defects triaged and flagged for release? (Owner: QA Lead)
- [ ] Acceptance criteria for all release items are met? (Owner: PO)
- [ ] Release notes drafted and reviewed? (Owner: PM/PO)
- [ ] Backout/rollback plan documented and tested? (Owner: Release Engineer)
- [ ] Deployment runbook prepared and reviewed? (Owner: Release Engineer)
- [ ] Stakeholders notified of timeline & impact? (Owner: PM)

CI/CD & Testing
- [ ] Build artifacts verified and stored in artifact registry (Owner: Release Engineer)
- [ ] End-to-end smoke test executed in staging (Owner: QA)
- [ ] Performance/security run (if applicable) completed (Owner: Tech Lead / QA)

Approvals
- [ ] Product Owner sign-off for release (Owner: PO)
- [ ] QA Lead sign-off (Owner: QA Lead)
- [ ] Release Engineer sign-off (Owner: Release Engineer)

Deployment
- [ ] Execute deployment steps in runbook (Owner: Release Engineer)
- [ ] Post-deploy smoke tests pass (Owner: QA)
- [ ] Monitor metrics & logs for X minutes (Owner: On-call Engineers)
- [ ] Confirm stakeholder notification of successful release (Owner: PM)

Post-release
- [ ] Create post-release notes and lessons learned (Owner: PM)
- [ ] Open follow-up actions / backlog items if needed (Owner: PM/PO)
