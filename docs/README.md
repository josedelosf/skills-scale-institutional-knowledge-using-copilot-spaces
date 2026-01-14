# OctoAcme Project Management Docs

Welcome! This space centralizes all core project management process documentation for the OctoAcme program. Use this README as your launch point for understanding how projects are initiated, planned, executed, tracked, and improved.

## Overview

OctoAcme follows a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decisions. Every cross-functional project—whether delivering product features, services, or integrations—operates within a consistent framework designed to maximize customer value while maintaining psychological safety and encouraging continuous learning. Our processes are built on the principle that small, testable increments delivered frequently create better outcomes than large, infrequent releases.

At the heart of our approach are clearly defined roles and responsibilities. Each project has a named Project Manager (PM) who coordinates delivery, schedules, risks, and communications, alongside a Product Manager (PdM) who defines outcomes, prioritizes the backlog, and measures success. Developers implement features and collaborate on design and testability, while QA/Testing validates quality and acceptance criteria. This clear ownership model ensures accountability and enables teams to move quickly without confusion about decision-making authority.

Communication and transparency are fundamental to how we work. Teams maintain a regular cadence with weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates. We use simple, standardized communication templates for status updates and incident management, ensuring everyone has access to the same information. Risk management is proactive rather than reactive, with teams maintaining risk registers that are reviewed weekly and updated continuously as projects evolve.

Quality assurance is embedded throughout our lifecycle rather than treated as a final gate. Teams define acceptance criteria and Definition of Done upfront, write tests alongside implementation, and conduct retrospectives after each milestone to capture learnings and drive ongoing improvement. This integrated approach to quality, combined with our emphasis on measurable outcomes and evidence-based iteration, helps us deliver reliable, maintainable solutions that truly serve our customers' needs.

## Key Workflows

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation**: Frame the business case, align with stakeholders, and set success criteria
2. **Planning**: Break work into deliverable increments, estimate effort, map timelines, and define risks
3. **Execution**: Build, test, review, and iterate following an agile rhythm
4. **Release & Deployment**: Deploy using standardized release types, verify functionality, and communicate changes
5. **Close & Retrospective**: Capture learnings, assign action items, and identify improvements for future projects

## Personas and Roles

Our teams include the following key roles:

- **Project Manager (PM)**: Coordinates delivery activities, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines what should be built, prioritizes the backlog, and measures outcomes
- **Developers**: Design, build, test, and deliver software components that meet acceptance criteria
- **QA/Testing**: Validate quality standards and ensure acceptance criteria are met
- **Stakeholders**: Provide inputs, feedback, and approvals throughout the project lifecycle

Each role has clear responsibilities and communication patterns that support effective collaboration.

## Communication Strategies

OctoAcme maintains consistent communication through:

- **Weekly syncs** between PM and PdM to align on priorities and progress
- **Twice-weekly standups** for delivery teams (or as agreed by the team)
- **Monthly stakeholder updates** to maintain visibility and alignment
- **Ad-hoc escalations** when needed, following clear escalation paths
- **Standardized templates** for weekly status updates and incident communication
- **Single source of truth** using project READMEs or release docs for status

Risk and dependency communication is integrated into regular updates, with a simple risk register maintained and reviewed weekly.

## Quality Assurance Practices

Quality is maintained through:

- **Clear acceptance criteria** defined upfront for every feature
- **Definition of Done** established and upheld by the team
- **Test coverage** as a core deliverable, written alongside implementation
- **Code reviews** and design reviews to ensure maintainability
- **Retrospectives** after each milestone to capture learnings
- **Metrics and measurement** to validate impact and guide iteration
- **Incident response** with blameless post-mortems and documented learnings

## Documentation Index

### Core Process Guides

- [Project Management Overview](octoacme-project-management-overview.md) - High-level principles, artifacts, and lifecycle
- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities
- [Project Initiation Guide](octoacme-project-initiation.md) - How to frame business case and align stakeholders
- [Project Planning Guide](octoacme-project-planning.md) - Breaking down work, estimating, and mapping timelines
- [Execution & Tracking Guide](octoacme-execution-and-tracking.md) - Agile rhythm, project boards, and progress reporting
- [Risks & Communication](octoacme-risks-and-communication.md) - Risk management and stakeholder communication
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Standardized release types and deployment steps
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capturing learnings and driving improvement

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md) to understand the big picture
- **Starting a new project**: Follow the guides in order from Initiation through Planning and Execution
- **During execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risks & Communication](octoacme-risks-and-communication.md) regularly
- **Preparing for release**: Use the [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **After milestones**: Conduct retrospectives using the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide

Keep project-specific documentation in your project repository, and add process-specific docs into `.copilot/` if you want GitHub Copilot Spaces to use them as context.

---

**Questions or suggestions?** These docs are living documents. Submit an issue or PR to help improve our processes!
