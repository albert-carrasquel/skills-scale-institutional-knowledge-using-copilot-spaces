# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This collection of process documents provides comprehensive guidance for managing projects from initiation through delivery and continuous improvement.

## Overview

OctoAcme follows a structured, five-phase project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decision-making. Projects begin with **Initiation**, where teams create a Project One-pager that defines the problem statement, success metrics, stakeholders, and high-level timeline. Once approved, work moves into **Planning**, where teams conduct a kickoff meeting, create a prioritized backlog with acceptance criteria, estimate scope using T-shirt sizing or story points, and identify dependencies and risks in a Risk Register. The **Execution & Tracking** phase follows a disciplined cadence of daily standups, weekly delivery syncs, and end-of-sprint demos, with teams using GitHub Projects boards to manage work through columns from Backlog to Done. Projects conclude with **Release & Deployment**, following a standardized checklist that includes staging smoke tests, rollback plans, and post-deployment verification, before entering a **Retrospective** phase to capture learnings and convert them into actionable improvements.

Three core personas drive OctoAcme's collaborative model: **Developers** implement features and maintain quality through code reviews and testing; **Product Managers** define the product vision, prioritize the backlog, and measure customer outcomes; and **Project Managers** coordinate delivery, manage schedules and risks, facilitate meetings, and ensure transparent communication across stakeholders. This clear separation of responsibilities—with Product Managers owning the "what" and "why," Project Managers coordinating the "when" and "how," and Developers executing the "how"—creates accountability while enabling cross-functional collaboration through weekly PM-PdM syncs and regular stakeholder updates.

Communication at OctoAcme is built on transparency and consistency. Teams follow a standard weekly status template covering progress, next steps, risks and blockers, and decisions needed. Risk management uses a simple register tracking ID, description, impact, likelihood, owner, mitigation plan, and status, with three-level escalation paths (team → PM → Product Lead → Sponsor). For critical issues, the organization maintains incident communication protocols and security runbooks. This communication framework ensures all stakeholders—from engineering to sales to support—have access to a single source of truth, typically maintained in the project README or release documentation.

Quality assurance is embedded throughout OctoAcme's workflows rather than treated as a separate phase. Pull requests must be small (≤400 lines when possible), include issue links and acceptance criteria, and pass automated tests, linting, and security scans before requesting review. Teams maintain a documented Definition of Done, require at least one approval before merging, and implement multiple testing layers including unit tests for new logic, integration tests, end-to-end smoke tests for critical flows, and manual QA for feature acceptance when needed. Pre-release requirements mandate passing CI, drafted release notes, documented rollback plans, and successful staging smoke tests. This quality-first approach, combined with continuous monitoring of velocity, burndown, and key signals like errors and latency, ensures teams deliver reliable, maintainable software while maintaining the psychological safety to learn from incidents through blameless retrospectives.

## Core Principles

OctoAcme's project management approach is built on five foundational principles:

- **Customer Value First** — Prioritize features and decisions that deliver measurable customer and business value
- **Clear Ownership** — Every project has defined roles with explicit responsibilities for outcomes, delivery, and communication
- **Continuous Improvement** — Learn from every sprint, release, and incident through structured retrospectives and action tracking
- **Transparent Communication** — Maintain a single source of truth and ensure all stakeholders have visibility into progress, risks, and decisions
- **Repeatable Success** — Document processes, templates, and best practices to enable consistent execution and smooth onboarding

## Process Documentation

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Initial steps to validate and authorize work
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiatives into actionable plans
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution and progress tracking
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks effectively
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release process to reduce risk
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role definitions and responsibilities

## Getting Started

- **New to OctoAcme projects?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
- **Mid-project?** Check [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management](octoacme-risks-and-communication.md)
- **Preparing for release?** Review the [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Just finished a sprint or release?** Run a [Retrospective](octoacme-retrospective-and-continuous-improvement.md)
