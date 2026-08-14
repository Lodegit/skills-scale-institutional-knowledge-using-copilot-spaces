# OctoAcme Project Management Docs

OctoAcme follows an iterative, customer-focused project management approach with clear ownership (Project Manager and Product Lead), a lightweight initiation and planning phase, a steady execution cadence, and continuous improvement through retrospectives. These documents consolidate the standard artifacts, workflows, and escalation paths teams should use to plan, execute, and release work reliably.

Key workflows include a one-pager initiation to validate business need and success metrics, a planning phase that produces a prioritized backlog and release milestones, and an execution model driven by a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a PR-based development workflow (small PRs, CI checks, acceptance criteria in PRs). Releases are handled using the Release & Deployment Guide with pre-release checks, smoke tests, and rollback plans, while incidents follow the incident playbook and a blameless retrospective practice.

Core personas and responsibilities are described so teams have clear ownership: Product Managers define outcomes and success metrics; Project Managers coordinate schedule, risks, and stakeholder communications; Developers implement features, tests, and reviews; QA validates acceptance criteria through automated and manual testing. Communication cadence includes daily standups for blockers, weekly delivery syncs and demos, regular PM–PdM alignment, and monthly stakeholder updates.

Quality assurance is emphasized through automated unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA when necessary. Teams track velocity, burndown, and success metrics with dashboards, keep a running risk register, and convert retrospective action items into backlog tasks for continuous improvement.

Links to process documents
- docs/octoacme-project-management-overview.md — Overview: purpose, principles, roles, and lifecycle  
- docs/octoacme-project-initiation.md — Initiation: one-pager, stakeholders, decision gate  
- docs/octoacme-project-planning.md — Planning: backlog, estimates, Definition of Done, release plan  
- docs/octoacme-execution-and-tracking.md — Execution & tracking: cadence, board workflow, PR and QA checklist  
- docs/octoacme-risks-and-communication.md — Risk management & communication: risk register, templates, escalation  
- docs/octoacme-release-and-deployment.md — Release & deployment: pre-release checks, deployment checklist, rollback playbook  
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospectives: running retros, tracking action items  
- docs/octoacme-roles-and-personas.md — Roles & personas: responsibilities and communication patterns

How to use
- Read the overview to understand lifecycle and roles, then consult the initiation/planning docs when starting new work, the execution doc during delivery, and the release/retrospective docs when deploying or closing work.
- Keep the project one-pager, risk register, and release notes updated in the project repo so these docs remain the single source of truth.
