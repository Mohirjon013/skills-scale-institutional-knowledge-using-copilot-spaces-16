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

## Release Managers

### Role Summary
Release Managers coordinate release readiness, deployment planning, and post-release verification so that approved work reaches users safely.

### Responsibilities
- Confirm that acceptance criteria, quality gates, and release dependencies are complete
- Coordinate deployment windows, rollout sequencing, and rollback plans
- Maintain release checklists and readiness decisions
- Coordinate release announcements and post-release verification

### Goals
- Make releases predictable, observable, and low risk
- Ensure unresolved risks have an explicit owner and mitigation
- Give stakeholders a clear view of release readiness

### Typical Communication
- Release readiness reviews with Developers and QA/Testing
- Schedule and risk updates with Project Managers
- Scope and timing decisions with Product Managers
- Deployment and support handoffs with Customer Support Leads

### Interactions with Existing Personas
Release Managers turn Product Manager scope into a release plan, use evidence from Developers and QA/Testing, and work with Project Managers to manage timing and dependencies. They escalate readiness risks to the Project Manager and Product Manager rather than changing scope independently.

---

## Security Leads

### Role Summary
Security Leads ensure that security requirements, risks, and response plans are addressed throughout the project lifecycle.

### Responsibilities
- Define security requirements and review threat or risk assessments
- Advise Developers on secure design and implementation
- Coordinate security testing, findings, exceptions, and remediation
- Escalate material security risks and support incident response

### Goals
- Prevent avoidable security issues before release
- Make security decisions and exceptions traceable
- Ensure security risks have accountable owners and time-bound mitigations

### Typical Communication
- Design and risk reviews with Developers and Technical Leads
- Validation and finding reviews with QA/Testing
- Risk register updates with Project Managers
- Security trade-offs and escalation with Product Managers and stakeholders

### Interactions with Existing Personas
Security Leads provide constraints and evidence that inform Product Manager priorities and Project Manager risk tracking. They collaborate with Developers and QA/Testing on controls and verification, while retaining responsibility for security recommendations and escalation rather than owning delivery scope.

---

## Customer Support Leads

### Role Summary
Customer Support Leads represent operational readiness and customer impact before and after delivery.

### Responsibilities
- Identify customer-facing risks, support needs, and expected questions
- Prepare support guidance, known-issue information, and escalation paths
- Relay customer feedback and incident patterns to the project team
- Participate in release readiness and post-release reviews

### Goals
- Reduce customer disruption during releases
- Ensure support teams can explain and troubleshoot new behavior
- Turn customer feedback into actionable product and delivery insights

### Typical Communication
- Customer-impact reviews with Product Managers
- Release and incident updates with Project Managers and Release Managers
- Known-issue and acceptance discussions with QA/Testing
- Troubleshooting handoffs with Developers

### Interactions with Existing Personas
Customer Support Leads provide customer evidence to Product Managers and operational readiness input to Project Managers. They coordinate with Release Managers on announcements and support handoffs, and with Developers and QA/Testing on reproducible issues without taking ownership of engineering fixes.

---

## Data and Analytics Leads

### Role Summary
Data and Analytics Leads define how project outcomes are measured and help the team use evidence to evaluate delivery impact.

### Responsibilities
- Define instrumentation, data quality expectations, and reporting needs
- Partner with Product Managers on success metrics and decision criteria
- Validate telemetry and outcome data with Developers and QA/Testing
- Report results and identify trends after releases or milestones

### Goals
- Make project outcomes measurable and interpretable
- Detect gaps between intended and observed customer or business impact
- Support prioritization with reliable evidence

### Typical Communication
- Metric and experiment planning with Product Managers
- Instrumentation reviews with Developers and Technical Leads
- Data validation with QA/Testing
- Outcome reporting with Project Managers and stakeholders

### Interactions with Existing Personas
Data and Analytics Leads translate Product Manager goals into measurable signals and work with Developers to implement telemetry. They provide Project Managers with progress and outcome evidence, while QA/Testing helps verify that reported data is complete and accurate.

---

## Delivery Leads or Scrum Masters

### Role Summary
Delivery Leads or Scrum Masters facilitate effective team flow, remove process blockers, and help the team improve how work is delivered.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives as appropriate
- Surface blockers, dependencies, and workflow bottlenecks
- Help the team maintain delivery agreements and a sustainable pace
- Track improvement actions and follow up on commitments

### Goals
- Improve flow from ready work to completed work
- Make blockers and dependencies visible early
- Strengthen team collaboration and continuous improvement

### Typical Communication
- Daily coordination with Developers and QA/Testing
- Delivery risk and dependency discussions with Project Managers
- Backlog readiness and priority discussions with Product Managers
- Retrospective actions with all delivery participants

### Interactions with Existing Personas
Delivery Leads complement Project Managers by focusing on team flow and facilitation rather than owning the overall project schedule or stakeholder commitments. They help Product Managers and Project Managers identify delivery constraints, while Developers and QA/Testing retain ownership of implementation and quality work.

---

## Technical Leads or Architects

### Role Summary
Technical Leads or Architects provide technical direction, guide solution design, and make cross-component dependencies and trade-offs visible.

### Responsibilities
- Establish technical approaches, interfaces, and design guidelines
- Identify architecture risks, dependencies, and non-functional requirements
- Support technical estimation and sequencing
- Review implementation choices for maintainability, reliability, and operability

### Goals
- Deliver coherent and maintainable solutions
- Reduce integration surprises and avoidable technical risk
- Align technical decisions with product outcomes and delivery constraints

### Typical Communication
- Design reviews and implementation guidance with Developers
- Testability and non-functional requirement discussions with QA/Testing
- Dependency and estimate discussions with Project Managers
- Feasibility and trade-off discussions with Product Managers
- Security design reviews with Security Leads

### Interactions with Existing Personas
Technical Leads or Architects provide technical evidence for Product Manager trade-offs and Project Manager planning. They guide Developers and collaborate with QA/Testing on testability, while sharing accountability for technical decisions with the delivery team rather than replacing individual implementation ownership.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role assignments to the project size and context; one person may hold more than one persona when appropriate.
