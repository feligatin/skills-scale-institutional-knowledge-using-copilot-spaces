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

## Technical Project Coordinator

### Role Summary
Technical Project Coordinators bridge technical teams and the project management office. They track status, assess technical risks, and manage dependencies to ensure smooth project execution.

### Responsibilities
- Track technical project status and milestones
- Identify and escalate technical risks early
- Manage technical dependencies across teams
- Facilitate communication between engineering and project management
- Maintain technical project documentation and metrics
- Support resource allocation and capacity planning for technical work

### Goals
- Prevent technical surprises and delays
- Ensure technical risks are visible to leadership
- Reduce bottlenecks caused by dependency mismanagement
- Enable engineering teams to focus on delivery

### Interactions with Existing Roles
- **Works with Project Manager**: Reports technical status, escalates issues, supports overall project planning
- **Works with Engineering Lead**: Collects technical metrics, understands risks, tracks dependencies
- **Works with Product Manager**: Communicates feasibility and impact of requirements
- **Communicates with Stakeholders**: Provides technical context for decisions and trade-offs

### Typical Communication
- Technical status dashboards and reports
- Dependency tracking and escalation logs
- Risk assessments and mitigation plans
- Cross-team coordination meetings

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons serve as the primary communication point between the project team and external stakeholders or sponsors. They gather requirements, manage expectations, and evaluate change requests.

### Responsibilities
- Gather and clarify stakeholder requirements and feedback
- Manage stakeholder expectations throughout the project lifecycle
- Communicate project status, risks, and changes to stakeholders
- Evaluate and prioritize change requests
- Facilitate stakeholder reviews and approval gates
- Maintain stakeholder satisfaction and engagement

### Goals
- Ensure stakeholder needs are understood and met
- Prevent scope creep through clear change management
- Maintain strong stakeholder relationships and trust
- Enable stakeholders to make informed decisions

### Interactions with Existing Roles
- **Reports to Project Manager**: Escalates stakeholder concerns, updates on change requests
- **Coordinates with Product Manager**: Aligns on requirements and prioritization
- **Communicates with Developers**: Conveys stakeholder feedback and acceptance criteria
- **Primary Contact for Stakeholders**: Represents the project team to external parties

### Typical Communication
- Stakeholder meeting notes and action items
- Change request evaluations and approvals
- Status updates tailored for stakeholder audiences
- Requirement clarification and validation sessions

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads oversee testing strategy and quality standards throughout the project. They ensure deliverables meet acceptance criteria and quality expectations before release.

### Responsibilities
- Define and execute comprehensive test strategies
- Prioritize and track defects based on impact and severity
- Establish and maintain quality standards and metrics
- Plan test coverage, automation, and tools
- Coordinate testing across development and deployment phases
- Report on quality metrics and trends

### Goals
- Ensure high-quality deliverables reach production
- Reduce defects and rework cycles
- Improve test efficiency through automation
- Build confidence in release readiness

### Interactions with Existing Roles
- **Works with Engineering Lead**: Understands technical architecture, coordinates testing activities
- **Works with Project Manager**: Reports quality status, escalates blockers
- **Collaborates with Developers**: Reviews code quality, validates test coverage
- **Works with Release Manager**: Confirms release readiness and quality gates

### Typical Communication
- Test plans and test case documentation
- Defect tracking and prioritization reports
- Quality metrics dashboards
- Release readiness assessments

---

## Release Manager

### Role Summary
Release Managers coordinate and execute release activities, ensuring smooth deployment to production with minimal risk and disruption.

### Responsibilities
- Plan and coordinate release schedules and activities
- Manage release checklists, prerequisites, and dependencies
- Coordinate deployment with operations and infrastructure teams
- Manage rollback procedures and contingency plans
- Track release metrics and communicate status
- Conduct post-release reviews and lessons learned

### Goals
- Execute releases smoothly with minimal downtime
- Reduce deployment risks and incidents
- Enable frequent, predictable releases
- Maintain system stability during transitions

### Interactions with Existing Roles
- **Works with Engineering Lead**: Provides deployment package, understands technical changes
- **Coordinates with QA Lead**: Confirms quality gates before release
- **Works with Product Manager**: Communicates release contents and business impact
- **Coordinates with Operations**: Manages infrastructure changes and monitoring
- **Reports to Project Manager**: Updates on release progress and status

### Typical Communication
- Release notes and deployment plans
- Release checklists and readiness tracking
- Deployment status updates
- Post-release retrospectives and metrics

---

## Knowledge Management Owner

### Role Summary
Knowledge Management Owners maintain process documentation and institutional knowledge. They capture insights from projects, update processes, and support team onboarding and continuous improvement.

### Responsibilities
- Maintain and update process documentation
- Capture lessons learned and best practices from retrospectives
- Support new team member onboarding with documentation
- Identify process gaps and improvement opportunities
- Consolidate knowledge from cross-functional teams
- Ensure documentation stays current and accessible

### Goals
- Preserve institutional knowledge and best practices
- Reduce onboarding time and ramp-up for new team members
- Enable continuous process improvement
- Build a knowledge base for organizational learning

### Interactions with Existing Roles
- **Collects input from all roles**: Gathers feedback, metrics, and lessons learned
- **Works with Project Manager**: Documents project processes and outcomes
- **Supports Developers**: Creates technical onboarding and reference materials
- **Collaborates with Product Manager**: Documents product-related processes
- **Supports team operations**: Maintains knowledge base and documentation systems

### Typical Communication
- Process documentation and playbooks
- Retrospective summaries and action items
- Onboarding guides and checklists
- Knowledge base updates and announcements

---

## Persona Interaction Map

```
                        ┌─────────────────────┐
                        │   Stakeholders      │
                        └────────────┬────────┘
                                     │
                    ┌────────────────┼────────────────┐
                    │                │                │
            ┌───────▼────────┐  ┌────▼──────────┐  ┌─▼──────────────┐
            │ Stakeholder    │  │  Product      │  │  Project       │
            │ Liaison        │  │  Manager      │  │  Manager       │
            └────────────────┘  └────┬──────────┘  └─┬──────────────┘
                                     │               │
                    ┌────────────────┼───────────────┤
                    │                │               │
         ┌──────────▼─────┐  ┌──────▼────────┐  ┌──▼──────────────────┐
         │ Engineering    │  │ Technical     │  │ Knowledge           │
         │ Lead           │  │ Project       │  │ Management Owner    │
         │                │  │ Coordinator   │  │                     │
         └────────┬───────┘  └────┬──────────┘  └─────────────────────┘
                  │               │
         ┌────────┴────────┐  ┌───┴────────────┐
         │                 │  │                │
    ┌────▼──────┐    ┌────▼───▼─────┐   ┌───▼──────────────┐
    │ Developers│    │ QA Lead      │   │ Release Manager  │
    └───────────┘    └──────────────┘   └──────────────────┘
```

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand how personas collaborate to deliver projects successfully and what accountability each role holds.
