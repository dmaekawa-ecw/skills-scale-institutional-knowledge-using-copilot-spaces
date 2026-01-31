# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks (PM, Tech Lead, Scrum Master)
- Demo/Review at the end of each sprint or milestone (includes UX Designer for design validation)
- Weekly metrics review with Data Analyst (if applicable)
- Bi-weekly design reviews with UX Designer (as needed for user-facing features)

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
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown (maintained by Scrum Master)
- Monitor success metrics identified in the Project One-pager (tracked by Data Analyst)
- Use dashboards for key signals (errors, latency, usage)
- Update stakeholders per [Communication Plan](octoacme-communication-plan-template.md)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- See [Communication Plan](octoacme-communication-plan-template.md) for detailed escalation paths

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Documentation maintained by Technical Writer (if applicable)
- [ ] Design reviews scheduled with UX Designer (for user-facing work)
- [ ] Metrics dashboards configured and monitored (with Data Analyst)
