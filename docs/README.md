# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This folder contains comprehensive guides for running cross-functional projects using the OctoAcme framework.

## Quick Navigation

- **[Project Management Overview](octoacme-project-management-overview.md)** — Core principles, roles, key artifacts, and lifecycle overview
- **[Project Initiation](octoacme-project-initiation.md)** — Validating business need, aligning stakeholders, and decision gates
- **[Project Planning](octoacme-project-planning.md)** — Breaking work into shippable increments, backlog creation, and risk identification
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, quality standards, and blocker escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk registers, stakeholder updates, and escalation paths
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardized release process, checklists, and rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and driving improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of Developers, Product Managers, and Project Managers

---

## OctoAcme Project Management Overview

### Lifecycle & Core Approach

OctoAcme operates on a structured five-phase project lifecycle: **Initiation → Planning → Execution → Release → Retrospective**. This customer-first, iterative delivery model emphasizes delivering small, testable increments rather than large-batch releases. Each project begins with a **Project One-pager** that validates business need, defines success metrics, and identifies stakeholders. The framework balances flexibility with governance through lightweight but consistent artifacts—such as the Project Charter, prioritized backlog with acceptance criteria, risk register, and release checklists—ensuring clarity without heavy overhead.

### Roles & Accountability

Three core personas drive project success:

- **Project Managers** coordinate schedules, risks, and communications
- **Product Managers** define what should be built and measure outcomes
- **Developers** implement features with quality and maintainability as core responsibilities

This clear separation of concerns ensures that strategy, execution, and delivery are each owned by the right function. Regular rhythms keep everyone aligned:
- Daily standups (15 min)
- Weekly PM/PdM syncs
- Twice-weekly team standups
- Sprint planning and end-of-sprint demos

These enable rapid decision-making and dependency management.

### Risk Management & Communication

OctoAcme maintains a formal **Risk Register** that tracks ID, description, impact, likelihood, owner, and mitigation plans, reviewed weekly during syncs. A tiered escalation path ensures blockers are surfaced quickly:

1. **Level 1**: Team-level triage in standups
2. **Level 2**: PM escalation to Product Lead and dependent teams
3. **Level 3**: Sponsor-level escalation for business-impacting issues

Stakeholder communication is standardized through weekly status templates covering progress, next steps, risks, and decisions needed. Incident communication follows a blameless retrospective approach, with post-mortems capturing learnings and action items tracked to completion.

### Quality & Execution Standards

The Execution & Tracking phase enforces quality through:
- Automated CI/CD pipelines (tests, linting, security scanning)
- Small PRs (≤400 lines)
- Peer reviews
- Definition of Done enforcement

Teams track velocity and burndown, run unit and integration tests, conduct manual QA for feature acceptance, and perform smoke tests before production releases. Releases are standardized by type (patch, minor, major) with pre-release checklists, staged deployment to production, post-deploy verification, and documented rollback procedures.

**Continuous improvement** is embedded: retrospectives after each sprint or milestone capture what went well and what could improve, with 2–3 prioritized action items feeding back into the backlog.

---

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Initiation](octoacme-project-initiation.md) and [Planning](octoacme-project-planning.md) guides
3. **Running a project?** Use the [Execution & Tracking](octoacme-execution-and-tracking.md), [Risk Management](octoacme-risks-and-communication.md), and [Release](octoacme-release-and-deployment.md) guides
4. **Improving your process?** Check [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

For questions or suggestions about these docs, please open an issue in the repository using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
