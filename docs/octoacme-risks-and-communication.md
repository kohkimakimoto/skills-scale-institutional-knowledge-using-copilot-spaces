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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

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
- Team-level -> PM -> Product Lead -> Sponsor
- Technical blockers: Scrum Master coordinates with Developers and PM
- Requirements clarification: Business Analyst bridges stakeholders and technical teams
- Release issues: Release Manager coordinates with QA, Developers, and PM
- Documentation gaps: Technical Writer collaborates with subject matter experts
- Design concerns: UX/UI Designer works with Product Manager and Developers
- For security incidents, follow the security incident runbook and notify Security on-call

For detailed interaction patterns between roles, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).
