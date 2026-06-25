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
Technical Leads connect product goals to implementation strategy. They guide architecture, technical trade-offs, and engineering execution quality.

### Responsibilities
- Own technical approach for major initiatives and complex changes
- Break large efforts into technically feasible milestones
- Mentor developers and unblock delivery risks
- Align non-functional requirements (reliability, performance, maintainability)

### Interactions with Existing Roles
- Partners with Product Managers to shape scope and technical constraints
- Works with Project Managers to sequence dependencies and delivery risks
- Supports Developers with design reviews and implementation guidance
- Aligns with QA on test strategy for high-risk paths

### When to Involve
- Planning for new architecture, major refactors, or high-risk dependencies
- Implementation milestones where trade-offs affect scope or timeline
- Incident response for root-cause triage and remediation strategy

---

## Release Engineer

### Role Summary
Release Engineers own release flow reliability across CI/CD, deployment orchestration, and rollback readiness.

### Responsibilities
- Maintain release automation and deployment pipelines
- Define release gates and environment readiness checks
- Coordinate release execution, rollback plans, and deployment runbooks
- Track and improve deployment reliability metrics

### Interactions with Existing Roles
- Coordinates with Project Managers on release schedule and change windows
- Works with Developers and QA to validate release artifacts and smoke tests
- Partners with Product Managers on release scope and communication readiness

### When to Involve
- Planning release milestones and deployment constraints
- Release readiness reviews and go/no-go decisions
- Incident response when rollback or deployment triage is required

---

## UX Researcher

### Role Summary
UX Researchers ensure product decisions are grounded in user behavior, usability evidence, and clear experience expectations.

### Responsibilities
- Run lightweight discovery and usability validation
- Synthesize insights into actionable requirements and acceptance criteria
- Identify usability risks before release
- Provide evidence for prioritization and iteration decisions

### Interactions with Existing Roles
- Partners with Product Managers to refine problem statements and success criteria
- Collaborates with Developers to clarify UX constraints and implementation impact
- Works with Project Managers to schedule research activities into delivery plans

### When to Involve
- Planning for initiatives with new user journeys or workflow changes
- Implementation checkpoints where UX trade-offs are being made
- Post-release reviews when adoption or satisfaction targets are missed

---

## Data Analyst

### Role Summary
Data Analysts define, validate, and interpret product and delivery metrics used to make prioritization and improvement decisions.

### Responsibilities
- Define measurement plans and event tracking requirements
- Build dashboards for outcome, quality, and adoption metrics
- Validate metric quality and investigate anomalies
- Provide analysis for post-release and retrospective decisions

### Interactions with Existing Roles
- Partners with Product Managers to define success metrics
- Supports Developers with instrumentation requirements
- Helps Project Managers report delivery and outcome trends to stakeholders

### When to Involve
- Planning for metric definitions and instrumentation scope
- Implementation before code freeze to validate required tracking
- Post-release and retrospective analysis for impact validation

---

## Security Reviewer

### Role Summary
Security Reviewers reduce delivery risk by identifying and addressing security concerns before release and during incidents.

### Responsibilities
- Perform threat modeling and security design reviews
- Validate security controls and compliance requirements
- Review high-risk changes before release
- Advise on incident containment and remediation actions

### Interactions with Existing Roles
- Works with Developers on secure implementation patterns and fixes
- Partners with Technical Leads on architecture-level risk decisions
- Aligns with Project Managers on security risk tracking and escalation timing

### When to Involve
- Planning when handling sensitive data, auth, or external integrations
- Implementation of high-risk features before production rollout
- Incident response involving potential security exposure

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons provide structured communication between delivery teams and external business groups to improve alignment and reduce surprises.

### Responsibilities
- Consolidate stakeholder inputs, constraints, and feedback
- Coordinate release communications and expectation management
- Surface cross-functional dependency risks early
- Ensure escalation paths are clear during major changes

### Interactions with Existing Roles
- Works with Project Managers to align updates, decisions, and escalations
- Partners with Product Managers to translate stakeholder needs into backlog inputs
- Coordinates with Release Engineers for launch and support communications

### When to Involve
- Planning for stakeholder mapping and communication cadence
- Release planning and launch-readiness communications
- Post-release and incident updates requiring broad stakeholder coordination

---

## Persona Engagement Guidance (Accountability & Handoffs)

Use this lightweight model to avoid role ambiguity:

- **Planning:** PM and PdM assign accountable owners for architecture (Technical Lead), measurement (Data Analyst), security (Security Reviewer), and stakeholder communication (Stakeholder Liaison).
- **Implementation:** Developers and QA pull in Technical Lead, UX Researcher, and Security Reviewer at predefined checkpoints instead of late-stage escalation.
- **Release:** Release Engineer leads release readiness with PM coordination; Security Reviewer and Technical Lead confirm risk acceptance.
- **Post-release:** Data Analyst and UX Researcher validate outcomes and user impact, then PM/PdM convert findings into backlog actions.
- **Incident response:** PM coordinates communications, Technical Lead and Release Engineer drive technical mitigation, and Security Reviewer leads security-specific containment.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
