# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

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
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Role-based Responsibilities During Execution

| Activity | Responsible Role |
|----------|-----------------|
| Facilitate daily standup | Project Manager (PM) |
| Merge PRs and own release branches | Technical Lead (with Developer support) |
| Own deployments and release gates | Release Manager |
| Incident triage and initial response | Technical Lead + QA Automation Lead |
| Escalate business-impacting blockers | PM → Product Manager (PdM) → Sponsor |
| Update risk register | PM (owners recorded per risk) |
| Drive customer-facing communication | Support / Customer Success Lead |

**Escalating blockers by role level:**
- **Developer / Designer blocker:** Raise in daily standup; Technical Lead resolves or escalates.
- **Technical Lead blocker:** Escalates to PM who coordinates with dependent teams.
- **PM / cross-team blocker:** PM escalates to PdM and Sponsor as needed (see Blocker Escalation levels below).

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly (each risk has a named owner)
- [ ] Daily standup facilitated by PM; blockers recorded and actioned
- [ ] Merge and release responsibilities assigned to Technical Lead / Release Manager
- [ ] Incident triage runbook in place (owned by Technical Lead + QA Automation Lead)
- [ ] Role-based escalation path communicated to all team members
