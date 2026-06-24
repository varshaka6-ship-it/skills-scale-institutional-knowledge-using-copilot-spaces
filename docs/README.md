# OctoAcme Project Management Docs

This README provides an overview and links to the canonical OctoAcme project management process documents stored in the `docs/` folder.

## OctoAcme Project Management Processes Overview

OctoAcme follows a structured, five-phase project lifecycle designed to balance flexibility with clear governance. Projects progress through **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with acceptance criteria), **Execution** (daily delivery with continuous tracking), **Release** (standardized deployment with risk mitigation), and **Retrospective** (capturing learnings and improvements). The approach is grounded in customer-first principles, iterative delivery, clear ownership, and data-informed decisions. Each project is owned by a named Project Manager (PM) and Product Manager (PdM), ensuring accountability and clear decision-making authority throughout the lifecycle.

Execution relies on a disciplined team rhythm and defined workflows. Daily 15-minute standups focus on progress and blockers, weekly delivery syncs review milestones and flagged risks, and sprint-based planning ensures work is prioritized and estimated before beginning. The team uses GitHub Projects for backlog management with standard columns (Backlog, Ready, In Progress, In Review, QA, Done), enforces small pull requests (≤400 lines), and requires at least one approval before merging. Quality is built into every phase through unit testing, integration testing, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance—all tracked via velocity, burndown, and key dashboards.

Risk and communication are managed proactively through a formalized Risk Register (tracking ID, description, impact, probability, owner, and mitigation) reviewed at weekly syncs, and a three-level escalation path (team triage → PM escalation to Product Lead → sponsor-level escalation). Stakeholder communication follows a consistent cadence with weekly status templates, monthly updates, and role-specific messaging to engineering, sales, and support teams. The organization also maintains psychological safety and continuous improvement by running structured retrospectives after each sprint or release, using blameless post-incident reviews, and tracking action items to completion.

The personas—Developers, Product Managers, and Project Managers—each have defined responsibilities aligned to the overall process. Developers own implementation, testing, and technical risk identification; Product Managers define the problem, prioritize the backlog, and measure outcomes; and Project Managers coordinate schedules, manage risks, and ensure transparency. This role clarity, combined with shared artifacts (project charters, release plans, risk registers, and retrospective notes stored in the repository), enables OctoAcme teams to execute consistently, onboard new members quickly, and scale knowledge across the organization.

## Process Documents

The following documents provide detailed guidance on each phase and aspect of OctoAcme project management:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level principles, core roles, key artifacts, and project lifecycle overview.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — One-pager template, stakeholder alignment, decision gates, and initiation checklist.
- **[Project Planning](octoacme-project-planning.md)** — Backlog templates, planning activities, Definition of Done, risk capture, and milestone mapping.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Team rhythm, PR/CI guidance, quality standards, reporting metrics, and execution checklist.
- **[Risks & Communication](octoacme-risks-and-communication.md)** — Risk register format, communication templates, escalation paths, and incident communication.
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure, running retros, tracking improvements, and continuous improvement culture.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Role summaries, responsibilities, and goals for Developers, Product Managers, and Project Managers.

## How to Contribute

To add or update a process document:

1. Open an issue using the **"Add Content to Project Management Process Docs"** template (`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`)
2. Clearly describe the gap, rationale, and suggested content
3. Draft or update the document in the `docs/` folder
4. Submit a pull request referencing the issue
5. Incorporate feedback and merge when approved

This workflow ensures that process updates are tracked, aligned with stakeholders, and integrated into our living knowledge base.

## Quick Links

- **Getting Started?** Start with [Project Management Overview](octoacme-project-management-overview.md) for principles and roles
- **Starting a New Project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
- **In Execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risks & Communication](octoacme-risks-and-communication.md)
- **Preparing to Release?** See [Release & Deployment](octoacme-release-and-deployment.md)
- **Learning from a Sprint?** Check [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
