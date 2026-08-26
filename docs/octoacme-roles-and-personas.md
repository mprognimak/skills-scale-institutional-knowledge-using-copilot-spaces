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
The Technical Lead provides architectural direction and technical decision-making for a project or product area. They bridge the gap between product requirements and engineering execution, ensuring solutions are sound, scalable, and aligned with organizational standards.

### Responsibilities
- Define and communicate technical architecture and approach
- Review and approve major design and implementation decisions
- Identify technical risks and drive mitigation strategies
- Mentor developers and ensure engineering best practices
- Collaborate with Product Managers on feasibility and trade-offs

### Goals
- Deliver technically sound solutions that meet long-term maintainability needs
- Reduce rework through early identification of design issues
- Keep the team aligned on standards and conventions

### Typical Communication
- Architecture design docs and ADRs (Architecture Decision Records)
- Technical reviews in sprint planning and refinement
- Pairing sessions and code review guidance

### Interactions with Existing Roles
- **Developers**: Provides architectural guidance, mentorship, and review. Acts as the final decision-maker on major technical choices.
- **Product Managers**: Advises on technical feasibility, complexity, and trade-offs to inform prioritization.
- **Project Managers**: Surfaces technical risks and dependencies to support scheduling and planning.

---

## Delivery Lead

### Role Summary
The Delivery Lead is accountable for end-to-end delivery of a project or workstream. They focus on flow, removing blockers, and ensuring the team is set up to meet commitments. This role often spans engineering and delivery disciplines.

### Responsibilities
- Own delivery sequencing and milestone tracking
- Identify and escalate blockers and dependencies
- Coordinate handoffs across teams and workstreams
- Maintain delivery health metrics (velocity, cycle time, predictability)
- Drive retrospective action items through to completion

### Goals
- Predictable, on-time delivery with minimal disruption
- Clear accountability and escalation paths
- Continuous improvement in team flow and throughput

### Typical Communication
- Delivery health dashboards and status summaries
- Cross-team coordination meetings
- Risk and dependency registers

### Interactions with Existing Roles
- **Project Managers**: Partners closely to align on plans, timelines, and risk escalation. The Delivery Lead focuses on execution flow while the Project Manager manages the broader project scope.
- **Product Managers**: Coordinates delivery sequencing with product priorities; flags scope or timeline risks.
- **Developers**: Removes delivery blockers and helps the team maintain momentum between planning and release.

---

## UX/Design Lead

### Role Summary
The UX/Design Lead is responsible for user experience design, ensuring that solutions are intuitive, accessible, and aligned with user needs. They advocate for the user throughout the product lifecycle.

### Responsibilities
- Lead user research, usability testing, and design iterations
- Produce wireframes, prototypes, and design specifications
- Define and maintain design systems and standards
- Collaborate with Product Managers to shape requirements from a user perspective
- Review implementations for design fidelity and accessibility

### Goals
- Deliver experiences that are usable, accessible, and delightful
- Reduce user friction and support adoption
- Ensure consistency across the product

### Typical Communication
- Design reviews and prototype walkthroughs
- Research findings and usability reports
- Shared design files and annotated specs

### Interactions with Existing Roles
- **Product Managers**: Partners on problem framing, user research, and acceptance criteria to ensure user-centricity in feature definition.
- **Developers**: Provides design specifications and is available for implementation questions; conducts design QA before release.
- **Project Managers**: Flags design dependencies and timeline requirements for research and iteration cycles.

---

## Release Manager

### Role Summary
The Release Manager coordinates and controls the release process, ensuring that software is deployed safely, reliably, and according to defined standards. They are the gatekeeper for release readiness.

### Responsibilities
- Define and maintain release processes and runbooks
- Coordinate release timing with development, QA, and operations
- Confirm release readiness criteria are met before deployment
- Manage release communications to stakeholders
- Track post-release health and coordinate rollbacks if necessary

### Goals
- Zero-defect, low-risk deployments
- Clear and repeatable release processes
- Rapid response to post-release issues

### Typical Communication
- Release readiness checklists and go/no-go decisions
- Deployment calendars and change windows
- Post-release status updates and incident summaries

### Interactions with Existing Roles
- **Developers**: Confirms that code is reviewed, tested, and ready for deployment; coordinates hotfix procedures.
- **Product Managers**: Aligns on release scope and communicates what is or is not included in each release.
- **Project Managers**: Integrates release milestones into project plans and coordinates any cross-team dependencies around deployment windows.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

