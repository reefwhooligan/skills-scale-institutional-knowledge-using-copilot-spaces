# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, UX, QA)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Customer Success/Support Liaison serves as the communication bridge between customers and the delivery team
- Documentation Specialist ensures all stakeholder-relevant information is documented and accessible

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:
- QA/Testing status (from QA/Testing Lead):
- Design/UX status (from UX Designer, if applicable):
- Customer feedback highlights (from Customer Success/Support Liaison, if applicable):

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

Role-Specific Handoff Checklist:
- [ ] UX Designer: design assets reviewed and handed off to Developers
- [ ] Technical Lead: architecture decision records (ADRs) documented
- [ ] QA/Testing Lead: test plan shared with team; defect triage up to date
- [ ] Customer Success/Support Liaison: customer impact assessed and communicated
- [ ] Documentation Specialist: all deliverables and process docs updated

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
