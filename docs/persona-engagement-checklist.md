# Persona Engagement Checklist

Purpose: Quick reference for who to involve at each stage of project work and why.

How to use: For each major activity (Planning, Implementation, Release, Incident), check the personas that must be involved and add notes.

Template:

## Planning (kickoff, estimation, acceptance criteria)
- Required:
  - PM
  - PdM
  - Technical Lead
  - Developers (representatives)
  - UX Researcher (if user-facing)
  - Data Analyst (if metrics required)
- Optional:
  - Security Reviewer (if security-sensitive)
  - Stakeholder Liaison (if external stakeholders need alignment)
- Notes: [add decisions, open questions, actions]

## Implementation (design reviews, checkpoints)
- Required:
  - Developers
  - Technical Lead
  - QA
- Optional:
  - UX Researcher (for ongoing design feedback)
  - Data Analyst (for instrumentation implementation)
- Notes: [progress checkpoints, blockers]

## Pre-release (release rehearsals, sign-offs)
- Required:
  - Release Engineer
  - QA
  - PM
  - Technical Lead
- Optional:
  - Security Reviewer (for security sign-off)
  - Stakeholder Liaison (for communications)
- Checklist:
  - [ ] CI green
  - [ ] Security scan results reviewed
  - [ ] Rollback plan documented
  - [ ] Stakeholder announcement drafted

## Post-release (validation, metrics, retrospective)
- Required:
  - Data Analyst
  - PM
  - PdM
  - QA
- Optional:
  - UX Researcher
  - Technical Lead
- Notes: [early signals, dashboards, action items]

## Incident response
- Required:
  - PM (incident lead)
  - Technical Lead
  - Developers on-call
  - Release Engineer (if rollback required)
- Optional:
  - Security Reviewer (if security incident)
  - Stakeholder Liaison (for external communications)

Usage guidance:
- Add this checklist to the project README or release playbook.
- For each item checked, add a short owner and ETA in the project board or issue.
