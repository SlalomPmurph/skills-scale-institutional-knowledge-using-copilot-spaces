# OctoAcme Project Management Process Documentation

**Welcome to OctoAcme's institutional knowledge repository!** This README serves as your starting point for understanding how we manage projects, collaborate as a team, and deliver value to our customers.

> 📋 **Related Issue**: [#2 - Create README for docs folder](https://github.com/SlalomPmurph/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2)

---

## Overview

OctoAcme follows a structured, iterative approach to project management that emphasizes **customer value**, **clear ownership**, **data-informed decisions**, and **psychological safety**. Our process is designed to help new team members quickly ramp up and understand how we work together to deliver successful projects.

### Our Core Principles

- **Customer-first**: We prioritize customer value and usability in every decision
- **Iterative delivery**: We deliver small, testable increments rather than big-bang releases
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: We measure impact and iterate based on evidence
- **Psychological safety**: We encourage feedback and learning at every stage

### Key Workflows

Our project lifecycle follows five main phases:

1. **Initiation**: Define problem statement, identify stakeholders, and establish high-level timeline
2. **Planning**: Break work into shippable increments, identify dependencies and risks
3. **Execution**: Build, test, review, and iterate with daily standups and weekly syncs
4. **Release**: Deploy, verify, and announce with proper rollback plans in place
5. **Close & Retrospective**: Capture learnings and convert them into actionable improvements

### Team Rhythm & Communication

We maintain consistent communication cadences to ensure alignment:

- **Daily standups** (15 min) — focus on progress, blockers, and dependencies
- **Twice-weekly team syncs** (or as agreed) — delivery team collaboration
- **Weekly PM + Product Lead sync** — strategic alignment and risk review
- **Monthly stakeholder updates** — keep stakeholders informed of progress
- **Sprint/milestone demos** — showcase completed work and gather feedback
- **Regular retrospectives** — continuous improvement and team learning

### Roles & Personas

Our cross-functional teams consist of:

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

### Quality Assurance Practices

Quality is built into every step of our process:

- **Unit tests** for new logic and features
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI/CD pipelines
- **Manual QA** for feature acceptance when needed
- **Code review** requirements (at least one approval before merging)
- **Automated testing and linting** in CI before PR approval

### Escalation Strategy

We have a clear three-level escalation path for blockers and issues:

- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Security incidents**: Follow security incident runbook and notify Security on-call immediately

---

## Core Process Documentation

This section provides direct links to all our key process documentation. Follow these guides to understand each phase of the project lifecycle in detail:

### Project Management Framework

- **[Project Management Overview](octoacme-project-management-overview.md)**  
  High-level introduction to OctoAcme's project management approach, core roles, key artifacts, and communication cadence

- **[Roles & Personas](octoacme-roles-and-personas.md)**  
  Detailed definitions of roles and responsibilities for Developers, Product Managers, and Project Managers

### Project Lifecycle Guides

- **[Project Initiation Guide](octoacme-project-initiation.md)**  
  How to validate and authorize work, create a project one-pager, and get stakeholder alignment

- **[Project Planning Guide](octoacme-project-planning.md)**  
  Turn approved initiatives into actionable plans with backlogs, estimates, and release timelines

- **[Execution & Tracking Guide](octoacme-execution-and-tracking.md)**  
  Day-to-day execution guidance, team rhythm, workflows, quality practices, and blocker escalation

- **[Risk Management & Communication](octoacme-risks-and-communication.md)**  
  How to identify, manage, and communicate risks and dependencies effectively

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)**  
  Standardized release process, deployment checklists, rollback procedures, and incident playbooks

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**  
  Capture learnings and convert them into actionable improvements for the team

---

## Getting Started

### For New Team Members

1. Start with the **[Project Management Overview](octoacme-project-management-overview.md)** to understand our approach
2. Review **[Roles & Personas](octoacme-roles-and-personas.md)** to understand your role and how you'll collaborate
3. Familiarize yourself with our **[Execution & Tracking Guide](octoacme-execution-and-tracking.md)** for day-to-day workflows
4. Bookmark **[Risk Management & Communication](octoacme-risks-and-communication.md)** for escalation paths

### For Project Managers

1. Use the **[Project Initiation Guide](octoacme-project-initiation.md)** to kick off new projects
2. Follow the **[Project Planning Guide](octoacme-project-planning.md)** to create actionable plans
3. Reference **[Execution & Tracking Guide](octoacme-execution-and-tracking.md)** for ongoing project management
4. Review **[Release & Deployment Guide](octoacme-release-and-deployment.md)** before any release

### For Product Managers

1. Start with **[Project Management Overview](octoacme-project-management-overview.md)** to align on process
2. Use **[Project Initiation Guide](octoacme-project-initiation.md)** to define problem statements and success metrics
3. Work with **[Project Planning Guide](octoacme-project-planning.md)** to prioritize backlogs
4. Leverage **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** for iteration

---

## Using These Docs with GitHub Copilot

These process documents are designed to work seamlessly with GitHub Copilot Spaces:

- Keep the Project Charter updated in your project repository
- Add process-specific docs to `.copilot/` directories to provide Copilot with context
- Use persona definitions from our **[Roles & Personas](octoacme-roles-and-personas.md)** guide to shape role-specific guidance
- Reference these documents when asking Copilot for project management assistance

---

## Contributing

Found an opportunity to improve our processes? We welcome your input!

- Propose changes through pull requests
- Discuss process improvements in retrospectives
- Share feedback with your Project Manager or Product Lead

---

**Questions?** Reach out to your Project Manager or consult the relevant process guide above.
