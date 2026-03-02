# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Technical Lead

### Role Summary
The Technical Lead guides the engineering direction of a project, sets standards for code quality and architecture, and acts as the primary technical decision-maker for the delivery team.

### Responsibilities
- Define and communicate technical approach, architecture decisions, and ADRs
- Review and approve significant design and code changes
- Identify and mitigate technical risks and blockers
- Support developers with guidance, pair programming, and unblocking
- Coordinate integration points with other teams or systems
- Contribute to estimation and sprint planning from a technical perspective

### Goals
- Deliver a maintainable, scalable codebase
- Reduce technical debt and unplanned outages
- Ensure engineering best practices are consistently applied

### Typical Communication
- Daily standups and technical design reviews
- ADRs and PR review comments
- Weekly sync with PM and PdM on technical trade-offs

### Interactions with existing roles
- **PM:** Reports technical blockers and timeline risks; escalates scope changes.
- **PdM:** Translates business requirements into technical constraints and trade-offs.
- **Developers:** Provides day-to-day guidance, performs design and code reviews.
- **QA:** Aligns on test strategy and reviews test coverage gaps.
- **Stakeholders:** Presents technical options and their impact during key decision points.

---

## UX/UI Designer

### Role Summary
The UX/UI Designer owns the user experience and visual design of product features, ensuring interfaces are intuitive, accessible, and aligned with user needs and brand guidelines.

### Responsibilities
- Conduct user research, usability tests, and design reviews
- Create wireframes, prototypes, and high-fidelity mockups
- Define interaction patterns and accessibility requirements
- Collaborate with developers on feasibility and implementation fidelity
- Maintain and evolve the design system or component library
- Deliver annotated design specs to the engineering team

### Goals
- Improve user satisfaction and task-completion rates
- Ensure accessibility compliance (WCAG AA or higher)
- Reduce design-related rework during implementation

### Typical Communication
- Design critiques and async reviews in design tooling (Figma, etc.)
- Sprint planning to flag UX requirements before work begins
- Sync with developers during handoff and implementation

### Interactions with existing roles
- **PM:** Aligns design timeline with project milestones and scope.
- **PdM:** Validates designs against user research and product goals.
- **Developers:** Provides specs and clarifies design intent during implementation.
- **QA:** Reviews implemented UI for fidelity and accessibility issues.
- **Stakeholders:** Presents design concepts for review and approval.

---

## Security Champion

### Role Summary
The Security Champion embeds security practices into the development lifecycle, identifies vulnerabilities early, and ensures the team follows secure coding and deployment standards.

### Responsibilities
- Review code and infrastructure changes for security issues
- Run or coordinate security scans (SAST, DAST, dependency audits)
- Maintain a list of security findings and drive remediation
- Train the team on secure coding practices and common vulnerability patterns
- Coordinate with external security reviews or pen tests when required
- Ensure secrets management and access control policies are followed

### Goals
- Zero critical or high unmitigated vulnerabilities at release
- Reduce mean time to remediate security findings
- Increase team security awareness and self-sufficiency

### Typical Communication
- Security review notes in PRs and issue comments
- Monthly or milestone-based security review reports
- Ad-hoc escalations for critical findings

### Interactions with existing roles
- **PM:** Flags security risks that may affect the release timeline.
- **PdM:** Advises on compliance or regulatory requirements that shape features.
- **Developers:** Reviews PRs, provides remediation guidance, and pairs on fixes.
- **QA:** Coordinates on security test cases and vulnerability regression tests.
- **Stakeholders:** Reports security posture and remediation status at key checkpoints.

---

## Business Analyst

### Role Summary
The Business Analyst bridges business stakeholders and the delivery team, translating business needs into structured requirements, process flows, and acceptance criteria.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Create process flow diagrams, use cases, and user stories
- Facilitate requirements workshops with stakeholders and the team
- Manage requirements traceability and change requests
- Review delivered features against agreed requirements
- Identify gaps in business process coverage and propose improvements

### Goals
- Ensure requirements are complete, unambiguous, and testable
- Reduce rework caused by misunderstood or missing requirements
- Improve stakeholder satisfaction with delivered outcomes

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written specs, user stories, and acceptance criteria in the backlog
- Regular sync with PM and PdM to refine scope

### Interactions with existing roles
- **PM:** Provides scoped, prioritized requirements to feed planning.
- **PdM:** Aligns requirements with product vision and user outcomes.
- **Developers:** Clarifies requirements, answers questions during implementation.
- **QA:** Shares acceptance criteria and edge cases to inform test plans.
- **Stakeholders:** Facilitates sign-off on requirements and change requests.

---

## Support / Customer Success Lead

### Role Summary
The Support / Customer Success Lead represents the voice of the customer within the project team, surfacing real-world usage patterns and ensuring the team delivers features that customers can successfully adopt.

### Responsibilities
- Provide customer context, feedback, and usage patterns to PdM and PM
- Define and review in-product help, documentation, and release notes
- Coordinate customer-facing communications around new releases
- Manage escalations from customers during or after rollout
- Track adoption metrics and surface friction points post-release
- Work with QA to validate real-world usage scenarios

### Goals
- Increase feature adoption and reduce support ticket volume post-launch
- Ensure customers receive timely, accurate communications about changes
- Reduce time to resolution for customer-reported issues

### Typical Communication
- Weekly sync with PdM and PM on customer feedback trends
- Release notes and customer announcement drafts
- Ad-hoc escalations for high-impact customer issues

### Interactions with existing roles
- **PM:** Escalates customer-impacting risks and coordinates release timing.
- **PdM:** Shares customer feedback to inform prioritization decisions.
- **Developers:** Reports reproducible bugs and validates fixes against customer scenarios.
- **QA:** Contributes real-world edge cases to test plans.
- **Stakeholders:** Communicates adoption data and customer satisfaction signals.

---

## Data Analyst

### Role Summary
The Data Analyst measures product and project outcomes, builds dashboards, and surfaces insights to support data-informed decisions.

### Responsibilities
- Define and instrument key metrics and success indicators
- Build and maintain dashboards for project and product health
- Analyse data to surface trends, anomalies, and improvement opportunities
- Partner with PdM to validate hypotheses with data

### Goals
- Provide timely, reliable data to guide decisions
- Improve visibility into product and delivery performance

### Typical Communication
- Sprint reviews with metrics updates
- Async reports and dashboard links shared with PM and PdM

### Interactions with existing roles
- **PM / PdM:** Delivers metrics and analysis to inform planning and prioritization.
- **Developers:** Coordinates on instrumentation and event tracking implementation.
- **Stakeholders:** Presents outcome data at key milestones.

---

## Release Manager

### Role Summary
The Release Manager coordinates the safe, repeatable deployment of software releases, ensuring the right artifacts reach the right environments with minimal risk.

### Responsibilities
- Own the release calendar and coordinate release readiness reviews
- Gate deployments on passing quality and security criteria
- Communicate release status and deployment windows to the team
- Maintain rollback and incident response playbooks

### Goals
- Zero unplanned outages caused by releases
- Predictable, low-friction deployment cadence

### Typical Communication
- Release readiness meetings before each deployment
- Deployment announcements and post-deploy verification notes

### Interactions with existing roles
- **PM / Tech Lead:** Confirms release scope and go/no-go decisions.
- **Developers / QA:** Validates that release criteria (tests, scans) are met.
- **Stakeholders:** Communicates deployment windows and any customer impact.

---

## QA Automation Lead

### Role Summary
The QA Automation Lead designs and maintains the automated test strategy, ensuring reliable test coverage that supports continuous delivery.

### Responsibilities
- Define the automated test strategy (unit, integration, end-to-end)
- Build and maintain the test automation framework and CI integration
- Review test coverage metrics and drive improvements
- Coordinate with Developers and QA on test data and environment needs

### Goals
- Achieve and maintain agreed coverage thresholds
- Reduce manual regression effort and time to validate releases

### Typical Communication
- Sprint planning and retrospectives on test health
- PR reviews for test quality and coverage
- Regular reports on automation pass rate and flaky tests

### Interactions with existing roles
- **Tech Lead / Developers:** Collaborates on testability design and CI pipeline integration.
- **QA:** Guides manual testers on what is covered by automation versus what requires manual validation.
- **Release Manager:** Confirms automated gate criteria are met before deployments.

---

## How to use these persona entries

Each section above follows the same structure: Role Summary, Responsibilities, Goals, Typical Communication, and Interactions with existing roles. To document a role for your project:

1. Copy the relevant entry into your project one-pager, team roster, or README.
2. Customise responsibilities and goals to reflect project-specific context.
3. For a fully structured template (including escalation paths, interaction matrix, and onboarding checklist), use [`docs/templates/role-responsibility-template.md`](templates/role-responsibility-template.md).

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

