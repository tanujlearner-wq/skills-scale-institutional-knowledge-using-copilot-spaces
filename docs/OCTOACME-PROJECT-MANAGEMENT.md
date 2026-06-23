# OctoAcme — Project Management Docs

This folder contains OctoAcme’s core project management process documents. They capture how we move work from idea to production — from a lightweight initiation through planning, execution, release, and retrospective — and serve as a single source of truth for teams and new hires.

Overview
OctoAcme follows a stage-based lifecycle that begins with project initiation (one-pager and stakeholder alignment), moves into planning (prioritized backlog, estimates, and Definition of Done), then into execution and tracking using a project board and PR-driven development, and finishes with release and retrospective activities. The planning stage focuses on breaking approved initiatives into shippable increments, identifying dependencies and risks, and producing a clear release/milestone map to guide delivery.

Key workflows emphasize small, reviewable changes and clear acceptance criteria. Teams use a project board (Backlog 1m Ready 1m In Progress 1m In Review 1m QA 1m Done), pull requests that link to issues and acceptance criteria, automated CI checks (unit/integration/security scans), and a requirement for at least one approval before merging. Release practices include staging verification, smoke tests, release notes, and documented rollback plans to reduce production risk.

Roles, communication, and quality assurance are explicit. Product Managers (PdM) define outcomes and success metrics; Project Managers (PM) coordinate schedules, risks, and stakeholder communications; Developers implement and maintain tests and docs; QA validates acceptance criteria and runs manual checks as needed. Communication is structured: short daily standups for blockers, weekly delivery syncs and PM1mPdM alignment, sprint demos, and templated stakeholder updates. Risk management uses a simple risk register and an escalation path (Team 1m PM 1m Product Lead 1m Sponsor), with a separate path for security incidents. Quality is enforced via CI (unit, integration, smoke tests), security scanning, manual QA for feature acceptance, and a release checklist.

Docs in this folder:
- docs/octoacme-project-management-overview.md 1m— Overview: principles, roles, lifecycle, and how to use the docs
- docs/octoacme-project-initiation.md 1m— Project initiation guide and one-pager template
- docs/octoacme-project-planning.md 1m— Planning: backlog, estimation, release planning
- docs/octoacme-execution-and-tracking.md 1m— Execution & tracking: team rhythm, PR workflow, CI expectations
- docs/octoacme-risks-and-communication.md 1m— Risk management and communication templates
- docs/octoacme-release-and-deployment.md 1m— Release & deployment checklist and rollback playbook
- docs/octoacme-retrospective-and-continuous-improvement.md 1m— Retrospectives and tracking improvements
- docs/octoacme-roles-and-personas.md 1m— Role summaries and responsibilities

Purpose
Use this README as the landing page for OctoAcme project management processes so team members can quickly find guidance, follow consistent practices, and onboard more efficiently.
