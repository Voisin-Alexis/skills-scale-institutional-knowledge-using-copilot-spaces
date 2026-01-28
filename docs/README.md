# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This directory centralizes the team's processes, checklists, templates, and artifacts used to initiate, plan, execute, release, and learn from projects.

## Purpose of this Copilot Space
- Centralize scattered project management knowledge in Copilot Spaces.
- Convert tacit team insights into searchable, versioned artifacts.
- Give all team members equal access to processes, decisions, and rationale.
- Connect repositories as structured knowledge sources for Copilot Spaces.
- Extract, refine, and standardize workflows collaboratively.
- Feed validated improvements back into the living documentation.
- Accelerate onboarding and reduce single-person dependency risk.
- Enable consistent, repeatable project execution.

## Brief overview of OctoAcme project management processes
Purpose: Centralize clear, repeatable processes so teams deliver predictable outcomes and preserve institutional knowledge.

Principles:
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead (PdM).
- Data-informed decisions: define success metrics and iterate based on evidence.
- Psychological safety: encourage open feedback and continuous learning.

High-level lifecycle:
1. Initiation — validate problem, stakeholders, measurable outcomes, create one‑pager.
2. Planning — create prioritized backlog, estimate, define Definition of Done, identify dependencies and risks.
3. Execution & Tracking — small PRs, CI tests, daily standups, weekly delivery syncs, risk monitoring.
4. Release — verification, automated pipeline deployments when possible, release notes and rollback plans.
5. Retrospective & Continuous Improvement — capture learnings, convert into action items and track impact.

Key artifacts & practices:
- Project One-pager / Charter (Problem, Goal, Success metrics)
- Backlog items with acceptance criteria and estimates
- Risk register with owners and mitigation plans
- Definition of Done and test plan
- CI with automated tests and security scanning
- Release notes and rollback playbook
- Retrospectives and tracked action items

Team rhythm & communication:
- Daily standups for team-level coordination
- Weekly PM + PdM sync and delivery syncs
- Sprint demos / reviews at end of each sprint or milestone
- Monthly stakeholder updates and ad-hoc escalations as needed

## Docs in this folder
(Each document is a focused process doc referenced by the ISSUE_TEMPLATE)
- octoacme-project-management-overview.md — Project-level overview, roles, and lifecycle
- octoacme-project-initiation.md — How to start and validate a project
- octoacme-project-planning.md — Planning activities, backlog templates, and checklist
- octoacme-execution-and-tracking.md — Team rhythms, PR conventions, QA, and execution checklist
- octoacme-risks-and-communication.md — Risk register and stakeholder communication templates
- octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook
- octoacme-retrospective-and-continuous-improvement.md — Retrospectives and improvement tracking
- octoacme-roles-and-personas.md — Role descriptions and responsibilities

Program process documents are stored in this `docs/` folder. Issue templates for requesting updates to these docs live in `.github/ISSUE_TEMPLATE/` (see `Add Content to Project Management Process Docs` template).

## How to use
- Start with the Project One-pager template in `octoacme-project-initiation.md`.
- Open requests to add or update docs using the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`.
- Keep the project README updated in the project repo and reference these process docs.
- If you want Copilot Spaces to use specific process docs as training/context, add them into `.copilot/` for that Space.

## Changes in this PR
- Adds docs/README.md as an entry point to OctoAcme process documentation and links to individual process documents.
