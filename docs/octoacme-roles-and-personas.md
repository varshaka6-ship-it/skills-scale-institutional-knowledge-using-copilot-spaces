# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Additional Personas

The following personas represent specialist and cross-functional roles that commonly appear on OctoAcme projects. Adding clarity around these roles reduces ambiguity, accelerates decision-making, and ensures accountability for critical delivery concerns.

---

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers coordinate cross-team technical delivery for large or multi-team features. They own integration plans, unblock technical dependencies, and ensure alignment between engineering teams and product goals.

### Responsibilities
- Coordinate cross-team technical delivery and integration planning
- Own unblocking technical dependencies across teams
- Run technical kickoffs and regular syncs with Engineering Managers and Tech Leads
- Identify and escalate technical risks early
- Maintain technical roadmap alignment with product timelines
- Facilitate architecture reviews and design decisions

### Goals
- Ensure seamless integration across multiple engineering teams
- Minimize delays caused by cross-team dependencies
- Maintain technical feasibility of product commitments
- Enable faster delivery of complex features

### Typical Communication
- Technical kickoff and planning sessions
- Weekly cross-team technical syncs
- Risk and dependency escalations to PM/Product Lead
- Technical roadmap updates and trade-off discussions

---

## Release Engineer / DevOps Owner

### Role Summary
Release Engineers maintain release pipelines, define deployment gates, own rollback procedures, and support staging/production verification. They ensure reliable, repeatable, and observable deployments.

### Responsibilities
- Maintain and improve release pipelines and CI/CD infrastructure
- Define deployment gates, approval workflows, and safety checks
- Own and test rollback procedures for all releases
- Support staging and production verification and monitoring setup
- Configure observability (dashboards, alerts, logging) for deployments
- Coordinate with QA and Support on deployment readiness
- Triage post-deployment incidents and escalate critical issues

### Goals
- Enable fast, safe, and reliable releases
- Reduce mean time to recovery (MTTR) for incidents
- Minimize deployment-related downtime and risk
- Maintain clear visibility into deployment health

### Typical Communication
- Pre-release deployment checklists and coordination
- Deployment windows and post-deployment verification calls
- Incident response and rollback decisions
- Release notes and deployment documentation

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers lead user research, validate designs against user needs, produce wireframes and acceptance criteria for UX, and run usability testing. They ensure products are usable and meet user expectations.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, prototypes, and design specifications
- Define UX acceptance criteria and hand off to development teams
- Validate designs against user needs and accessibility standards
- Run usability testing and gather feedback on features
- Collaborate with Product Managers on feature prioritization
- Ensure consistency across product experiences

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user friction and support burden
- Validate product decisions with user evidence
- Maintain design consistency and quality standards

### Typical Communication
- User research findings and insights briefings
- Design reviews and feedback sessions with Developers and QA
- Acceptance criteria and UX testing plans
- Success metrics and user satisfaction data

---

## Security Owner / Security Engineer

### Role Summary
Security Owners perform threat modeling, review architecture and PRs for security risks, require and verify security scans, and sign off on security-related gates. They ensure products meet security standards and compliance requirements.

### Responsibilities
- Perform threat modeling for new features and architecture
- Review PRs, designs, and infrastructure for security risks
- Configure and verify security scanning in CI/CD pipelines
- Sign off on security-related release gates
- Advise Developers on secure coding practices
- Coordinate with Developers and Release Engineers on remediation
- Notify PM of security impact and trade-offs
- Escalate critical security issues to Product Lead and Sponsor as needed

### Goals
- Minimize security vulnerabilities and compliance gaps
- Enable secure, confident releases
- Build a culture of security awareness and best practices
- Maintain customer trust and regulatory compliance

### Typical Communication
- Threat modeling and architecture review meetings
- PR security feedback and code review comments
- Security scan results and remediation timelines
- Release gate sign-off and security incident escalations

---

## Data Engineer / Analytics Lead

### Role Summary
Data Engineers and Analytics Leads define event schemas, metrics instrumentation, data pipelines, and validation checks. They enable data-driven decision-making by ensuring metrics capture success criteria and powering dashboards for monitoring.

### Responsibilities
- Define event schemas and metrics instrumentation for features
- Build and maintain data pipelines and ETL processes
- Create validation checks for success metrics and data quality
- Power dashboards for monitoring KPIs and business metrics
- Partner with Product Managers to translate success criteria into measurable metrics
- Support post-release analysis and impact measurement
- Advise Developers on instrumentation requirements

### Goals
- Enable data-driven product decisions and prioritization
- Ensure accurate, timely measurement of product impact
- Reduce time to insight on feature performance
- Build trust in product metrics and dashboards

### Typical Communication
- Metrics definition and instrumentation planning sessions
- Weekly sync with Product Managers on success metric tracking
- Data quality and pipeline health updates
- Post-release impact analysis and insights briefings

---

## Customer Success / Support Lead

### Role Summary
Customer Success and Support Leads coordinate release communications to customers, capture field feedback, define support runbooks, and triage post-release issues. They bridge customer needs with product and engineering teams.

### Responsibilities
- Coordinate release communications and announcements to customers
- Define support runbooks and troubleshooting guides for new features
- Capture and prioritize customer feedback and issues
- Triage post-release customer issues and escalate to engineering
- Track customer satisfaction and support metrics
- Participate in release planning to identify customer impact
- Inform Product Managers of field trends and customer pain points

### Goals
- Minimize customer confusion and support burden during releases
- Capture valuable customer feedback for product improvements
- Enable fast resolution of customer-facing issues
- Maintain high customer satisfaction and trust

### Typical Communication
- Release notes and customer communication drafts
- Support runbooks and training for new features
- Customer feedback summaries and trend reports
- Post-release incident triage and escalations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference persona interactions when documenting cross-functional workflows (e.g., in Release & Deployment, Risks & Communication, Execution & Tracking).
