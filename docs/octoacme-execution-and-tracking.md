# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies; include Technical Lead and QA/Testing Lead
- Weekly delivery sync — show progress, updates, and flagged risks; QA/Testing Lead reports test status, UX Designer shares design progress
- Demo/Review at the end of each sprint or milestone — include Customer Success/Support Liaison for user perspective feedback
- Design handoff sessions — UX Designer presents completed designs to Developers before implementation begins

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed — coordinated by QA/Testing Lead
- UX Designer conducts usability reviews at design handoff and post-implementation
- Customer Success/Support Liaison validates user-facing changes with select customers before release

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Design handoff sessions scheduled with UX Designer before each implementation sprint
- [ ] QA/Testing Lead engaged in sprint planning and ready for test execution
- [ ] Documentation Specialist reviewing and updating docs at each milestone
- [ ] Customer Success/Support Liaison invited to sprint demos for user-facing changes
