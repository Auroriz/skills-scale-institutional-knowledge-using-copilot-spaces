# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles describe areas of accountability, not necessarily separate people: teams may combine or scale assignments to fit project size and complexity. Make ownership explicit for each project, especially for product decisions, delivery coordination, technical implementation, quality, and release approval. Specialist roles advise and coordinate within their expertise; final decisions remain with the designated accountable owner and applicable organizational policies.

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

## Additional Project Roles

The following specialist and operational roles may contribute where the work requires them. They collaborate with the core delivery roles above; assigning one does not imply every project needs a separate person for that role.

### Business Analysts

#### Role Summary
Business Analysts elicit and clarify business needs, map workflows, and translate stakeholder input into requirements and acceptance criteria.

#### Responsibilities
- Facilitate discovery and document business rules, workflows, and requirements
- Identify unanswered questions, assumptions, and requirement changes
- Help make requirements testable and traceable to intended outcomes

#### Goals
- Give the team a shared, validated understanding of the problem and constraints
- Reduce ambiguity, rework, and missed requirements

#### Typical Communication
- Stakeholder interviews and discovery workshops
- Requirements, workflow diagrams, and backlog refinement
- Clarifications and change-impact notes shared with the delivery team

#### Collaboration and Accountability
- Partners with the Product Manager to clarify needs and options; the Product Manager remains accountable for product scope and prioritization
- Works with the Project Manager to surface dependencies, open questions, and change impacts for plans and risks
- Collaborates with Developers and QA/Testing to make requirements feasible and acceptance criteria verifiable; does not independently approve scope changes

### UX/UI Designers

#### Role Summary
UX/UI Designers research user needs and shape accessible, usable interaction flows and visual designs.

#### Responsibilities
- Research user needs and translate findings into journeys, wireframes, and interface designs
- Specify interaction behavior and accessibility considerations
- Validate designs through usability feedback and iterate with the team

#### Goals
- Make the product intuitive, accessible, and aligned with user needs
- Identify usability issues early enough to address them efficiently

#### Typical Communication
- Research readouts, design reviews, prototypes, and design-system guidance
- Ongoing collaboration with product and engineering during refinement and implementation

#### Collaboration and Accountability
- Works with the Product Manager to connect user research and design choices to desired outcomes; the Product Manager owns product priorities
- Partners with Developers to assess feasibility and resolve implementation questions
- Coordinates with QA/Testing on usability and accessibility checks and relevant acceptance criteria; design recommendations do not replace agreed product or compliance decisions

### QA Automation Leads

#### Role Summary
QA Automation Leads guide test automation strategy, coverage, and regression safeguards so the team can assess quality consistently.

#### Responsibilities
- Identify appropriate automation layers and priority test coverage
- Coordinate maintainable automated regression checks and quality signals
- Work with the team to make features testable and to investigate failures
- Communicate coverage gaps, defects, and quality risks

#### Goals
- Detect regressions early and provide dependable feedback
- Improve confidence in changes without treating automation as a substitute for all testing

#### Typical Communication
- Test plans, automation reviews, CI results, defect reports, and release-readiness updates

#### Collaboration and Accountability
- Partners with Developers on testability, test design, and integration of checks into CI
- Aligns with QA/Testing practitioners on functional, exploratory, and automation coverage
- Shares quality status and risks with the Project Manager and Release Manager; advises on readiness but does not unilaterally waive acceptance criteria or authorize a release

### Release Managers

#### Role Summary
Release Managers coordinate release readiness, deployment timing, communications, and rollback preparedness across participating teams.

#### Responsibilities
- Maintain a release checklist, schedule, and coordination plan
- Confirm readiness inputs, including acceptance status, CI and security results, release notes, verification, and rollback plans
- Coordinate deployment communications and operational handoffs
- Track release issues and ensure follow-up actions are assigned

#### Goals
- Make releases predictable, observable, and recoverable
- Ensure stakeholders and support teams know what is changing and when

#### Typical Communication
- Release readiness reviews, deployment plans, go/no-go inputs, and stakeholder announcements

#### Collaboration and Accountability
- Aligns release milestones and dependencies with the Project Manager
- Coordinates with Developers and QA/Testing on merged changes, verification, and unresolved quality risks
- Works with DevOps/Platform Engineers and Support/Customer Success on deployment operations and handoffs
- Coordinates the release process and presents readiness information; release authorization remains with the designated accountable owner under team policy

### DevOps/Platform Engineers

#### Role Summary
DevOps/Platform Engineers support environments, CI/CD pipelines, infrastructure, observability, and operational reliability.

#### Responsibilities
- Build and maintain delivery pipelines and development, test, and production environments
- Support reliable infrastructure, deployment automation, and operational monitoring
- Advise on capacity, resilience, and operational risks
- Help teams prepare runbooks and diagnose deployment or environment issues

#### Goals
- Enable safe, repeatable delivery and reliable services
- Improve visibility into system health and reduce avoidable operational toil

#### Typical Communication
- Infrastructure and pipeline documentation, operational reviews, dashboards, and incident or deployment coordination

#### Collaboration and Accountability
- Partners with Developers on build, deployment, and runtime needs, and with QA/Testing on stable test environments
- Coordinates with the Release Manager on deployment automation, observability, and rollback execution
- Advises the Project Manager on operational dependencies and risks; infrastructure changes follow the relevant technical and operational approval processes

### Security Partners / Security Champions

#### Role Summary
Security Partners or designated Security Champions advise teams on secure design, risk assessment, security requirements, and escalation of security concerns.

#### Responsibilities
- Help identify security threats, requirements, and appropriate review needs
- Advise on secure implementation and mitigation options
- Track or route security findings to the designated security process and appropriate owners
- Support security readiness reviews and incident escalation when needed

#### Goals
- Address security risks early and make security expectations clear
- Ensure concerns are handled through the appropriate review and incident processes

#### Typical Communication
- Design and threat-model reviews, security findings, risk registers, and security incident channels

#### Collaboration and Accountability
- Works with Developers on secure design and remediations, and with the Product Manager on the impact of product trade-offs
- Coordinates with the Project Manager and Release Manager to track risks and readiness dependencies
- Provides expert advice and escalates through security policy; a champion does not replace the designated Security team's authority or independently accept organizational risk

### Support / Customer Success Partners

#### Role Summary
Support or Customer Success Partners bring customer issues, support readiness needs, and feedback trends into project planning and delivery.

#### Responsibilities
- Share customer-reported issues, usage patterns, and recurring feedback
- Identify support documentation, training, and service-readiness needs
- Coordinate customer-impact information and route urgent issues through established channels
- Help verify that fixes address the reported customer impact

#### Goals
- Improve continuity between delivery and customer-facing teams
- Prepare support teams and customers for changes and known limitations

#### Typical Communication
- Customer feedback summaries, support briefings, knowledge-base updates, and incident communications

#### Collaboration and Accountability
- Partners with the Product Manager to inform discovery and prioritization; product priority remains the Product Manager's responsibility
- Works with the Project Manager to route customer-impacting risks, decisions, and readiness actions
- Provides Developers and QA/Testing with reproducible context and impact details and helps confirm support readiness; does not make technical or release decisions on their behalf

### Data / Analytics Leads

#### Role Summary
Data / Analytics Leads define instrumentation, reporting, and measurement approaches for project success metrics.

#### Responsibilities
- Translate success metrics into measurable events, data requirements, and reporting plans
- Advise on instrumentation, data quality, privacy, and interpretation
- Coordinate implementation and validate that dashboards or analyses answer the intended questions
- Communicate findings and measurement limitations after launch

#### Goals
- Provide trustworthy evidence of product outcomes
- Help teams learn whether changes achieved their intended impact

#### Typical Communication
- Metric definitions, instrumentation plans, dashboards, analysis readouts, and data-quality notes

#### Collaboration and Accountability
- Partners with the Product Manager to ensure measures reflect intended outcomes; the Product Manager owns product goals and prioritization
- Works with Developers to plan and validate instrumentation and with the Project Manager to include measurement work and dependencies in delivery plans
- Explains findings and limitations to stakeholders; interpretation informs decisions but does not replace the accountable owner's decision-making

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Treat role assignments as adaptable: one person may cover multiple roles, and specialist support may be consulted only when needed. Make final decision owners explicit for each project.
