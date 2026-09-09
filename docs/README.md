# OctoAcme Project Management Process Docs

## Overview

Welcome to the OctoAcme project management documentation. These guides standardize how we run projects across the organization, from initial concept through retrospectives. Whether you're a Project Manager, Product Manager, Developer, or stakeholder, you'll find guidance on processes, roles, and best practices for successful project delivery.

## Core Principles

OctoAcme projects are built on five core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments rather than big-bang releases
- **Clear ownership**: Each project has named roles with clear responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning from all team members

## Documentation Map

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core roles, lifecycle stages, and communication cadence
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of key roles (Project Manager, Product Manager, Developer) and their responsibilities

### Project Lifecycle

Follow these guides in sequence as you move through a project:

1. **[Project Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and create a lightweight plan. Start here with a new project idea.
   - _Key deliverable_: Project One-pager with problem statement, objectives, and success metrics

2. **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, and create a release plan.
   - _Key activities_: Kickoff meeting, backlog creation, estimation, Definition of Done
   - _Key deliverable_: Prioritized backlog with acceptance criteria and timeline

3. **[Execution and Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution and track progress toward milestones.
   - _Key practices_: Daily standups, team rhythm, pull request workflows, quality gates
   - _Key artifacts_: Project board, CI/CD pipeline, demo reviews

4. **[Release and Deployment](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production.
   - _Key steps_: Pre-release requirements, deployment checklist, smoke tests, rollback planning
   - _Key artifact_: Release notes and post-deploy verifications

5. **[Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements for future projects.
   - _Key practices_: Structured retros, action item tracking, measuring impact

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies throughout the project lifecycle.
  - _Key tools_: Risk Register, stakeholder communication templates, escalation paths

## Quick Navigation by Role

### Project Managers
- Start with: [Project Management Overview](./octoacme-project-management-overview.md)
- Then read: [Project Initiation](./octoacme-project-initiation.md) → [Project Planning](./octoacme-project-planning.md)
- Keep handy: [Risk Management & Communication](./octoacme-risks-and-communication.md)
- Essential: [Roles and Personas](./octoacme-roles-and-personas.md) (understand your team)

### Product Managers
- Start with: [Project Management Overview](./octoacme-project-management-overview.md)
- Then read: [Project Initiation](./octoacme-project-initiation.md) → [Project Planning](./octoacme-project-planning.md)
- Keep handy: [Execution and Tracking](./octoacme-execution-and-tracking.md)
- Reference: [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

### Developers
- Start with: [Roles and Personas](./octoacme-roles-and-personas.md)
- Then read: [Project Planning](./octoacme-project-planning.md) (understand acceptance criteria and DoD)
- Keep handy: [Execution and Tracking](./octoacme-execution-and-tracking.md) (PR workflows, quality standards)
- Reference: [Release and Deployment](./octoacme-release-and-deployment.md)

### All Roles
- Reference: [Roles and Personas](./octoacme-roles-and-personas.md) (clarify responsibilities)
- Reference: [Risk Management & Communication](./octoacme-risks-and-communication.md) (understand escalation and status updates)

## How to Use These Documents

1. **For new projects**: Start with [Project Initiation](./octoacme-project-initiation.md) to validate the business case and align stakeholders.

2. **For ongoing execution**: Use [Execution and Tracking](./octoacme-execution-and-tracking.md) as your day-to-day playbook. Reference [Project Planning](./octoacme-project-planning.md) for backlog and estimation guidance.

3. **For addressing risks**: Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) to identify risks, escalate issues, and communicate status.

4. **For releases**: Follow [Release and Deployment](./octoacme-release-and-deployment.md) to ensure quality, observability, and safe production deployments.

5. **For learning and improvement**: Run a retrospective using [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) and track action items.

## Key Artifacts at a Glance

| Artifact | Purpose | Owner | When |
|----------|---------|-------|------|
| Project One-pager | Validate business case | Product Lead + PM | Initiation |
| Backlog | Track and prioritize work | Product Manager | Planning & Execution |
| Risk Register | Identify and mitigate risks | Project Manager | Planning through Close |
| Definition of Done | Quality and acceptance standards | Team | Planning |
| Project Board | Track execution progress | Project Manager | Execution |
| Release Notes | Communicate changes to stakeholders | Product Manager | Release |
| Retrospective Notes | Capture learnings and action items | Project Manager | After milestone or release |

## Support & Questions

If you have questions about OctoAcme processes:
- Check the specific process document for your activity
- Refer to [Roles and Personas](./octoacme-roles-and-personas.md) to clarify who to ask
- Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation guidance

## Contributing to These Docs

If you identify gaps, improvements, or new best practices:
- Create an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
- Include the specific section and rationale for the update
- Team members and stakeholders will review and provide feedback

---

**Last updated**: September 2026  
**Maintained by**: OctoAcme Project Management Community
