# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. These docs capture how we initiate, plan, execute, release, and continuously improve projects. They’re intended to give new and existing team members a single entry point to understand roles, workflows, key artifacts, and the operating rhythm used across cross-functional work.

OctoAcme uses a lightweight, iterative lifecycle: Initiation (validate problem, create a Project One‑pager, align stakeholders), Planning (create a prioritized backlog, estimate, and define Definition of Done), Execution (small PRs, CI gates, project board workflow, daily standups and weekly syncs), Release (staging smoke tests, rollback plans, release notes), and Retrospective (capture learnings and track action items). Quality is enforced via automated tests (unit, integration, security scans), manual QA where needed, and CI required before requesting reviews. Risks are tracked in a simple Risk Register and escalated through defined tiers when needed.

Navigation
- Start with the Project Management Overview to get the big picture and core roles.
- Read Project Initiation when launching a new initiative (one‑pager template included).
- Use Project Planning for backlog templates, estimation, and the release/milestone map.
- Follow Execution & Tracking for the day-to-day board workflow, PR conventions, and escalation paths.
- Consult Release & Deployment for pre-release checks, deployment steps, and rollback playbooks.
- Use Retrospective & Continuous Improvement for running retros and tracking improvements.
- Reference Roles & Personas to understand responsibilities for PM, PdM, Developers, and QA.
- For risk and stakeholder communications, see Risk Management & Communication.

Docs (files in this folder)
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-risks-and-communication.md
- octoacme-roles-and-personas.md

How to use and contribute
- Keep project-specific artifacts (one‑pagers, release notes, risk registers) inside your project repo under docs/ or .copilot/ so Copilot Spaces can use them as context.
- To request new content or updates to these process docs, use the issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml.
- Proposed changes should align with existing principles (customer-first, iterative delivery, clear ownership) and include acceptance criteria and rationale.

If you want adjustments to wording, link format, or structure before I create the PR, tell me what to change. Otherwise confirm and I will create the branch, add this file at docs/README.md, and open a pull request.
