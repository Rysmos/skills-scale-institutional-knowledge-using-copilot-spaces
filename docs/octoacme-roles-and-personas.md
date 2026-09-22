# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. The roles may be combined or assigned to different people depending on project size and complexity; accountability should remain explicit even when one person performs multiple roles.

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

## Executive Sponsors

### Role Summary
Executive Sponsors provide strategic sponsorship and organizational support. They ensure the project remains connected to business priorities and help resolve issues that exceed the project team's authority.

### Responsibilities
- Confirm strategic alignment, desired outcomes, and success measures
- Secure organizational support, funding, and resources when needed
- Approve major scope, priority, or direction changes
- Remove escalated organizational blockers
- Provide timely decisions when risks or trade-offs require executive authority

### Interaction with Existing Roles
- Receive status, risk, and decision updates from the Project Manager
- Partner with Product Managers to confirm business priorities and outcomes
- Support Developers and other delivery roles indirectly by resolving organizational constraints rather than directing technical implementation

---

## Product Owners or Business Representatives

### Role Summary
Product Owners or Business Representatives translate business needs into clear, actionable priorities. They represent users and business stakeholders throughout delivery and confirm that completed work meets the intended need.

### Responsibilities
- Define desired outcomes, business value, and acceptance expectations
- Clarify requirements and prioritize work with the Product Manager
- Answer business questions during planning and execution
- Review completed work and confirm business acceptance
- Identify stakeholder impacts and communicate changes in business priorities

### Interaction with Existing Roles
- Work with Product Managers to align product vision, roadmap priorities, and project scope
- Work with Project Managers to sequence priorities, manage decisions, and resolve scope questions
- Collaborate with Developers on acceptance criteria and requirement clarification without prescribing implementation details

---

## PMO or Process Governance Leads

### Role Summary
PMO or Process Governance Leads promote consistent project practices, reporting, and continuous improvement across projects. They provide standards and oversight while leaving day-to-day delivery ownership with the Project Manager.

### Responsibilities
- Maintain project management standards, templates, and guidance
- Define reporting and documentation expectations
- Help teams apply consistent planning, risk, and decision practices
- Review project health and identify systemic issues or improvement opportunities
- Capture lessons learned and update shared processes when appropriate

### Interaction with Existing Roles
- Support Project Managers with planning, reporting, and process questions
- Provide the Executive Sponsor and other governance stakeholders with cross-project insight when requested
- Coordinate with Product Managers and delivery teams to improve practices without taking ownership of product or technical decisions

---

## Technical Leads or Solution Architects

### Role Summary
Technical Leads or Solution Architects guide technical direction, feasibility, architecture, and technical risk management. They create the connection between delivery strategy and implementation details.

### Responsibilities
- Define or review technical approaches and architectural decisions
- Assess feasibility, estimates, dependencies, and technical constraints
- Identify technical risks and recommend mitigations
- Establish technical standards and support consistent implementation
- Facilitate technical alignment across Developers and dependent teams

### Interaction with Existing Roles
- Partner with Project Managers on estimates, dependencies, risks, and schedule impacts
- Collaborate with Product Managers and Product Owners to evaluate trade-offs between value, scope, cost, and feasibility
- Guide Developers through design and implementation while preserving their ownership of code and detailed delivery work

---

## Quality or Validation Leads

### Role Summary
Quality or Validation Leads define quality expectations and coordinate verification activities so that deliverables are fit for purpose and ready for release.

### Responsibilities
- Define quality goals, validation plans, and readiness criteria
- Coordinate testing, validation, defect tracking, and quality reporting
- Confirm that acceptance criteria and required evidence are addressed
- Identify quality risks early and recommend mitigation activities
- Support release decisions with objective quality information

### Interaction with Existing Roles
- Work with Developers and Technical Leads to plan validation and resolve defects
- Coordinate with Product Managers and Product Owners to confirm acceptance expectations
- Provide Project Managers with quality status, risks, and readiness information for project reporting and release coordination

---

## Change and Communications Leads

### Role Summary
Change and Communications Leads help affected audiences understand, adopt, and support project outcomes. They make sure important decisions and updates reach the right stakeholders at the right time.

### Responsibilities
- Identify stakeholder groups, communication needs, and change impacts
- Create communication and adoption plans
- Coordinate project updates, decision announcements, and readiness messaging
- Gather feedback and surface adoption risks
- Support training, rollout, and transition activities where needed

### Interaction with Existing Roles
- Partner with Project Managers to align communications with milestones, risks, and decisions
- Work with Product Managers and Product Owners to communicate customer and business value
- Coordinate with Executive Sponsors on high-impact messages and with Developers or Technical Leads when technical changes need clear stakeholder explanation

---

## Risk or Compliance Owners

### Role Summary
Risk or Compliance Owners monitor material delivery risks and applicable regulatory, security, policy, or control obligations. They help ensure risks are visible, assigned, and addressed before they affect project outcomes.

### Responsibilities
- Identify and assess delivery, compliance, security, or policy risks
- Maintain risk and issue information for assigned areas
- Define or track mitigation, contingency, and evidence requirements
- Escalate risks when their impact or authority threshold is exceeded
- Confirm that required controls or approvals are addressed before release

### Interaction with Existing Roles
- Collaborate with Project Managers on the risk register, reporting, mitigation tracking, and escalation
- Work with Technical Leads and Developers on technical controls and remediation
- Coordinate with Product Managers, Product Owners, Quality Leads, and Executive Sponsors when risk acceptance or release decisions are required

---

## Role Interaction Across the Project Lifecycle

The following interaction model clarifies how the expanded roles support existing project responsibilities:

| Lifecycle stage | Primary interactions | Accountability focus |
| --- | --- | --- |
| Initiation | Executive Sponsor, Product Manager, Product Owner, Project Manager, PMO Lead | Confirm strategic alignment, outcomes, sponsorship, scope, governance, and initial stakeholders. |
| Planning | Project Manager, Product Owner, Technical Lead, Quality Lead, Risk or Compliance Owner | Establish the plan, priorities, estimates, dependencies, quality expectations, risks, and decision paths. |
| Execution and tracking | Project Manager, Developers, Technical Lead, Product Manager, Change and Communications Lead | Coordinate delivery, manage dependencies, report progress, resolve questions, and keep stakeholders aligned. |
| Risk and communication | Project Manager, Risk or Compliance Owner, Executive Sponsor, Change and Communications Lead | Make risks visible, assign mitigations, escalate decisions, and communicate material impacts. |
| Release and deployment | Quality Lead, Technical Lead, Product Owner, Risk or Compliance Owner, Project Manager | Confirm readiness, acceptance, controls, operational handoffs, and release communications. |
| Retrospective and improvement | Project Manager, PMO Lead, Product Manager, delivery roles, and stakeholders | Capture lessons learned, assign improvement actions, and update processes or role guidance. |

These roles are not required to be separate people. Smaller projects may combine responsibilities, but the project should document who is acting in each capacity, who has decision authority, and how handoffs occur. Explicit role assignments improve accountability, reduce ambiguity, strengthen risk management, and make delivery outcomes more predictable.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the interaction model to identify the right decision-maker, contributor, reviewer, and audience for each project activity.
