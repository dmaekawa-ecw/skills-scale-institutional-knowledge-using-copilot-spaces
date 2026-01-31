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
- Identify: during planning and ongoing execution (all team members can raise risks)
- Assess: estimate impact and likelihood (PM with input from relevant roles)
- Mitigate: reduced via actions, contingency plans (assigned to appropriate role owner)
- Monitor: review at weekly syncs and update status
- Document: significant risks and decisions in [Decision Log](octoacme-decision-log-template.md)

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- See [Communication Plan Template](octoacme-communication-plan-template.md) for detailed guidance
- Coordinate communication with Release Manager for deployment announcements

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level (Scrum Master/Tech Lead) -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- For production incidents, Release Manager coordinates response
- See [Communication Plan](octoacme-communication-plan-template.md) for detailed escalation matrix
