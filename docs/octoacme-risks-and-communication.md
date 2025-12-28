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
- Identify: during planning and ongoing execution (input from all roles)
- Assess: estimate impact and likelihood (with Technical Lead for technical risks)
- Mitigate: reduced via actions, contingency plans (assign owners across roles)
- Monitor: review at weekly syncs and update status (PM tracks, Scrum Master surfaces team concerns)

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, legal, compliance)
- Define specific stakeholder roles and their information needs (see [Roles and Personas](octoacme-roles-and-personas.md))
- Provide regular updates (weekly or milestone-based) tailored to stakeholder interests
- Use a single source of truth (project README or release doc) for status
- Involve Business Analyst for requirements-related stakeholder communications
- Include UX Designer in discussions with user-facing stakeholders
- Coordinate with Scrum Master on team health and velocity communications

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
- For security incidents, follow the security incident runbook and notify Security on-call
