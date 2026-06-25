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

## Additional Operational & Cross-functional Personas (new)

These personas improve operational clarity and show when and how to involve them across planning, execution, release, and incidents.

- Technical Lead
  - Responsibilities: Drive architectural decisions for the project, mentor developers, maintain technical runway, and own major technical trade-offs.
  - Interactions: Partners with PM/PdM to translate product goals into technical scope; leads design reviews with Developers and QA to ensure feasibility and testability.
  - When to involve: Planning (architecture & estimations), design reviews, high-risk technical decisions.

- Release Engineer
  - Responsibilities: Manage CI/CD pipelines, automate releases, own deployment strategies and rollback plans, and verify release artifacts.
  - Interactions: Works with Developers and QA to validate build artifacts; coordinates deployment timing and communications with PM/PdM; maintains deployment/runbook documentation.
  - When to involve: Before gating a release, during release rehearsals, and when introducing significant pipeline changes.

- UX Researcher
  - Responsibilities: Plan and run user research, synthesize findings, and provide usability-focused acceptance criteria and design recommendations.
  - Interactions: Collaborates with PdM to define success metrics and acceptance criteria; informs Developers and Designers of usability constraints and prioritized fixes.
  - When to involve: Discovery and planning, defining acceptance criteria for user-facing features, post-release usability validation.

- Data Analyst
  - Responsibilities: Define tracking and instrumentation needs, create dashboards for success metrics, and validate outcomes post-release.
  - Interactions: Works with PdM to confirm success metrics, with Developers to instrument events and metrics, and with PM to report outcomes and retrospective metrics.
  - When to involve: Planning (metric definition), pre-release (validation of instrumentation), post-release (metric analysis).

- Security Reviewer
  - Responsibilities: Conduct threat modeling, security reviews, and compliance checks; provide remediation guidance and verify fixes.
  - Interactions: Engages with Developers and Technical Leads during planning and before release; escalates significant findings to PM and PdM.
  - When to involve: Feature planning for security-sensitive work, pre-release security sign-off, incident response.

- Stakeholder Liaison
  - Responsibilities: Serve as the main contact for external stakeholder groups (e.g., Sales, Support), translate requests, and coordinate stakeholder communications.
  - Interactions: Works with PM to ensure stakeholder updates are aligned and with PdM to surface feature requests and feedback.
  - When to involve: Stakeholder briefings, release announcements, major scope changes.

---

## Interaction Mapping (applies to all roles)
For each role, add a one-line mapping showing who they typically coordinate with and on what topics. Example:
- Developers ↔ Technical Lead: design & implementation details
- PM ↔ PdM: schedule, scope, and stakeholder communications
- Release Engineer ↔ QA: release validation and rollback plans

---

## How these personas are used
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Keep persona descriptions concise (1–3 bullets) and include “When to involve” to reduce ambiguity in handoffs.
