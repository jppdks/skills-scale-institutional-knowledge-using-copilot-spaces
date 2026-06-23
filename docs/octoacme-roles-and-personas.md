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

## Technical Lead

### Role Summary
Technical Leads own technical direction and architecture decisions for a project area. They provide guidance on design patterns, code quality, and scalability while mentoring team members.

### Responsibilities
- Define and document technical architecture and design patterns
- Lead technical design reviews and code reviews on critical components
- Ensure code maintainability, scalability, and performance standards
- Identify and mitigate technical risks early in the project lifecycle
- Mentor developers and facilitate knowledge sharing across the team
- Collaborate with Product and Project Managers on technical trade-offs

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and rework
- Build team capability and reduce knowledge silos
- Enable fast, confident delivery through clear technical standards

### Typical Communication
- Design review discussions with developers and architects
- Technical guidance in code reviews and PR comments
- Architecture documentation and decision logs
- One-on-ones with team members for mentoring

### Interactions
- Works with **Developers** for implementation details and code quality
- Collaborates with **PM** and **PdM** on prioritization and technical trade-offs
- Partners with **Security Owner** on secure design practices
- Coordinates with **Delivery Lead** on cross-team technical dependencies

---

## Delivery Lead

### Role Summary
Delivery Leads coordinate day-to-day execution across multiple teams for complex initiatives. They resolve blockers, manage dependencies, and maintain visibility into cross-team schedules.

### Responsibilities
- Drive sprint commitments and facilitate daily standups across teams
- Identify and escalate inter-team blockers and dependencies
- Maintain cross-team schedule and dependency map
- Coordinate resource allocation and capacity planning
- Communicate status and risks to Project Manager and Product Lead
- Facilitate handoffs and integration between teams

### Goals
- Ensure smooth execution across multiple teams
- Minimize delays caused by dependencies and blockers
- Maintain clear visibility into progress and risks
- Accelerate delivery through proactive coordination

### Typical Communication
- Daily cross-team standups and syncs
- Dependency tracking and escalation reports
- Status updates to PM and Product Lead
- Meeting facilitation for integration points

### Interactions
- Works with **Project Manager** for scope and priority alignment
- Collaborates with **Technical Leads** to align technical delivery across teams
- Coordinates with **Product Manager** on feature interdependencies
- Escalates risks and blockers to **Product Lead** as needed

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers lead user research, design interfaces, and validate UX decisions. They ensure products are usable, accessible, and meet user needs.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and design specifications
- Define UX acceptance criteria based on user needs and research insights
- Collaborate on design reviews and iterate based on feedback
- Document design decisions and maintain design systems
- Validate designs with stakeholders and users before development

### Goals
- Deliver intuitive, accessible, and user-centered solutions
- Reduce rework by validating designs early
- Build shared understanding of user needs across the team
- Ensure consistency and quality in user experience

### Typical Communication
- Research findings and user insights presentations
- Design specs and wireframes/prototypes
- Participation in design and acceptance reviews
- UX acceptance criteria in backlog items

### Interactions
- Partners with **Product Manager** to align on user outcomes and success metrics
- Hands off validated designs to **Developers** with clear specifications
- Participates in demos and acceptance reviews with stakeholders
- Collaborates with **Technical Lead** on UX feasibility and technical constraints

---

## Security Owner

### Role Summary
Security Owners are the point-of-contact for security requirements, threat modeling, and compliance checks. They ensure security is built in throughout the project lifecycle.

### Responsibilities
- Conduct threat modeling and security reviews during design phase
- Define security acceptance criteria for features and releases
- Ensure security scanning and vulnerability remediation are tracked
- Review PRs and designs for security implications
- Maintain compliance with relevant standards and regulations
- Communicate security risks and their impact to Product and Project leadership

### Goals
- Build security into the product from the start
- Reduce security vulnerabilities and compliance gaps
- Enable fast, secure delivery through proactive security practices
- Maintain stakeholder confidence in product security

### Typical Communication
- Security threat reviews and design consultations
- Security acceptance criteria and compliance checklists
- Vulnerability reports and remediation tracking
- Risk escalations to PM and PdM when security impacts scope or timeline

### Interactions
- Engages with **Technical Leads** and **Developers** during design and code review for secure implementation
- Works with **Product Manager** on security requirements and prioritization
- Escalates security risks to **Project Manager** that impact timeline or scope
- Coordinates with **Delivery Lead** on security dependencies across teams

---

## Data Analyst / Analytics Owner

### Role Summary
Data Analysts and Analytics Owners ensure success metrics are measurable and the product emits correct telemetry. They enable data-driven decision-making throughout the project lifecycle.

### Responsibilities
- Define instrumentation and telemetry needs for success metrics
- Create dashboards and reports for release and ongoing metrics
- Validate data quality and identify instrumentation gaps
- Partner on interpretation of metrics and user behavior insights
- Document analytics requirements and acceptance criteria
- Track and report on success metrics post-release

### Goals
- Enable data-driven decisions about product health and success
- Ensure accurate measurement of business and user impact
- Reduce rework by validating hypotheses with data
- Support continuous improvement through measurement

### Typical Communication
- Metrics definition and instrumentation requirements
- Data dashboards and metric reports
- Insights and analysis of user behavior and product performance
- Participation in retrospectives with data insights

### Interactions
- Works with **Product Manager** on defining success metrics and business outcomes
- Collaborates with **Developers** on instrumentation implementation and data accuracy
- Partners with **Project Manager** for reporting cadence and stakeholder communication
- Provides insights to **Technical Lead** on performance metrics and data infrastructure

---

## Support Liaison / SRE Representative

### Role Summary
Support Liaisons and SRE Representatives represent on-call and support teams to ensure operability and maintainability. They advocate for reliability, runbooks, and post-release support readiness.

### Responsibilities
- Define runbook and operational requirements for new features
- Validate monitoring, alerting, and observability before release
- Ensure post-release support resources are prepared and trained
- Coordinate incident response and escalation procedures
- Identify operational risks and suggest mitigations
- Provide feedback on reliability and supportability issues

### Goals
- Ensure smooth operations and rapid incident response
- Reduce on-call burden through clear runbooks and automation
- Build team capability to support and troubleshoot issues
- Minimize customer impact during incidents and outages

### Typical Communication
- Operational requirements and runbook templates
- Monitoring and alerting checklists
- Support readiness reviews and training coordination
- Incident response and post-mortem participation

### Interactions
- Collaborates with **Project Manager** and **Delivery Lead** for deployment readiness
- Works with **Developers** on instrumentation, logging, and runbook accuracy
- Partners with **Technical Lead** on architectural reliability and resilience
- Coordinates with **Security Owner** on security incident response procedures

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, identify which personas are needed and ensure clear ownership and communication paths.
- Reference typical interactions to understand how roles collaborate and where dependencies exist.
