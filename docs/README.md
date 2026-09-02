# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with a customer-first, iterative approach that emphasizes clear ownership, measurable outcomes, and small, testable increments. Projects begin with a lightweight initiation that defines the problem, stakeholders, and success metrics, move into planning where work is broken into a prioritized, estimable backlog, then progress through execution, release, and retrospective phases to continuously improve outcomes.

Work is organized using a project board (Backlog → Ready → In Progress → In Review → QA → Done), timeboxed sprints or iterations, and a disciplined pull request process that favors small changes, linked issues, acceptance criteria, automated CI checks, and required approvals. Releases are categorized (patch/minor/major) with pre-release checks (CI, security scanning, smoke tests), rollback plans, and release notes to reduce risk.

Roles are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedules, risks, and communications; Developers implement and test features; QA validates acceptance criteria and runs manual or automated verification. Key artifacts (Project One-pager, roadmap, backlog, acceptance criteria, risk register, and retrospectives) are maintained in the docs/ folder as the single source of truth.

Communication and quality practices include daily standups, weekly delivery syncs, sprint demos, and stakeholder updates; an escalation path (team → PM → Product Lead → Sponsor); and automated testing (unit, integration, smoke), CI-based security scans and linting, plus manual QA where needed. Dashboards and metrics close the feedback loop so progress and improvements are measurable.

## Table of Contents
- Project Management Overview  
  - [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- Initiation  
  - [Project Initiation Guide](octoacme-project-initiation.md)
- Planning  
  - [Project Planning](octoacme-project-planning.md)
- Execution & Tracking  
  - [Execution & Tracking](octoacme-execution-and-tracking.md)
- Risk & Communication  
  - [Risk Management & Communication](octoacme-risks-and-communication.md)
- Release & Deployment  
  - [Release & Deployment Guide](octoacme-release-and-deployment.md)
- Retrospective & Continuous Improvement  
  - [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- Roles & Personas  
  - [Roles & Personas](octoacme-roles-and-personas.md)

## Getting Started
1. Read this README for a high-level orientation.
2. Open the Project Management Overview for role and artifact details.
3. Use the process guides for initiation, planning, execution, release, and retrospectives.
4. Add process updates via the repository issue template for process-doc updates (.github/ISSUE_TEMPLATE).

## Acceptance Criteria (from issue #2)
- Content aligns with existing process docs.
- Update improves clarity and discoverability.
- README serves as a central entry point linking to the process documents.
