# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, five-phase project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decision-making.

### Project Lifecycle

Projects begin with **Initiation**, where teams create a Project One-pager that defines the problem statement, success metrics, stakeholders, and high-level timeline. Once approved, work moves into **Planning**, where teams conduct a kickoff meeting, create a prioritized backlog with acceptance criteria, estimate scope using T-shirt sizing or story points, and identify dependencies and risks in a Risk Register. The **Execution & Tracking** phase follows a disciplined cadence of daily standups, weekly delivery syncs, and end-of-sprint demos, with teams using GitHub Projects boards to manage work through columns from Backlog to Done. Projects conclude with **Release & Deployment**, following a standardized checklist that includes staging smoke tests, rollback plans, and post-deployment verification, before entering a **Retrospective** phase to capture learnings and convert them into actionable improvements.

### Roles & Collaboration

Three core personas drive OctoAcme's collaborative model: **Developers** implement features and maintain quality through code reviews and testing; **Product Managers** define the product vision, prioritize the backlog, and measure customer outcomes; and **Project Managers** coordinate delivery, manage schedules and risks, facilitate meetings, and ensure transparent communication across stakeholders. This clear separation of responsibilities—with Product Managers owning the "what" and "why," Project Managers coordinating the "when" and "how," and Developers executing the "how"—creates accountability while enabling cross-functional collaboration through weekly PM-PdM syncs and regular stakeholder updates.

### Communication & Risk Management

Communication at OctoAcme is built on transparency and consistency. Teams follow a standard weekly status template covering progress, next steps, risks and blockers, and decisions needed. Risk management uses a simple register tracking ID, description, impact, likelihood, owner, mitigation plan, and status, with three-level escalation paths (team → PM → Product Lead → Sponsor). For critical issues, the organization maintains incident communication protocols and security runbooks. This communication framework ensures all stakeholders—from engineering to sales to support—have access to a single source of truth, typically maintained in the project README or release documentation.

### Quality Assurance

Quality assurance is embedded throughout OctoAcme's workflows rather than treated as a separate phase. Pull requests must be small (≤400 lines when possible), include issue links and acceptance criteria, and pass automated tests, linting, and security scans before requesting review. Teams maintain a documented Definition of Done, require at least one approval before merging, and implement multiple testing layers including unit tests for new logic, integration tests, end-to-end smoke tests for critical flows, and manual QA for feature acceptance when needed. Pre-release requirements mandate passing CI, drafted release notes, documented rollback plans, and successful staging smoke tests. This quality-first approach, combined with continuous monitoring of velocity, burndown, and key signals like errors and latency, ensures teams deliver reliable, maintainable software while maintaining the psychological safety to learn from incidents through blameless retrospectives.

---

Project management at OctoAcme prioritizes customer value, clear ownership, continuous improvement, and transparent communication. All processes are documented and reviewed to ensure repeatable success and easy onboarding.

## Process Documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective &amp; Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles &amp; Personas](octoacme-roles-and-personas.md)
