# OctoAcme Project Management Docs

This directory contains the shared processes, roles, and practices used to plan, deliver, release, and improve OctoAcme projects.

## Process overview

OctoAcme follows a lightweight lifecycle: initiatives begin with a project one-pager that defines the problem, SMART goal, success metrics, stakeholders, timeline, risks, and resource needs. Approved work moves into planning, where teams create a prioritized backlog, define acceptance criteria and the Definition of Done, estimate scope, identify dependencies, and agree on milestones and a release plan.

During execution, teams deliver small, testable increments using a project board with Backlog, Ready, In Progress, In Review, QA, and Done stages. Pull requests should include an issue link and acceptance criteria. Progress is coordinated through standups, delivery syncs, demos or reviews, and regular risk and dependency tracking. Releases require completed acceptance criteria, passing CI and security scans, release notes, a rollback or mitigation plan, staging smoke tests, and post-deployment verification.

Ownership is shared across clearly defined personas. Project Managers coordinate schedules, risks, resources, and communication; Product Managers define outcomes, prioritize the backlog, and measure success; developers build and test solutions; QA validates quality and acceptance criteria; and stakeholders provide input and approvals. Communication uses project boards, weekly status updates, risk registers, decision logs, and defined escalation paths.

Quality is built into the workflow through unit, integration, and end-to-end testing as appropriate, plus automated linting and security scanning in CI. Pull requests should receive at least one approval before merging. After sprints, releases, or incidents, retrospectives capture what worked, what needs improvement, and a small set of owned action items whose impact is reviewed over time.

## Documentation index

- [Project Management Overview](docs/octoacme-project-management-overview.md) — principles, lifecycle, roles, artifacts, and communication cadence.
- [Project Initiation](docs/octoacme-project-initiation.md) — validating ideas, aligning stakeholders, and deciding whether to plan.
- [Project Planning](docs/octoacme-project-planning.md) — backlog creation, estimation, dependencies, risks, and release planning.
- [Execution and Tracking](docs/octoacme-execution-and-tracking.md) — delivery workflow, project-board states, quality checks, and reporting.
- [Risks and Communication](docs/octoacme-risks-and-communication.md) — risk registers, stakeholder updates, incident communication, and escalation.
- [Release and Deployment](docs/octoacme-release-and-deployment.md) — release requirements, deployment verification, rollback, and release notes.
- [Retrospective and Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — retrospectives, action tracking, and improvement practices.
- [Roles and Personas](docs/octoacme-roles-and-personas.md) — responsibilities, goals, and communication patterns for core project roles.
