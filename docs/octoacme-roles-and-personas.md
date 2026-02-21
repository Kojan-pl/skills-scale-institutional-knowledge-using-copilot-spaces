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

## Release Manager

### Role Summary
The Release Manager owns release coordination end-to-end, from planning release windows to post-deploy announcements. They act as the single point of accountability for release readiness, bridging Developers, QA Lead, DevOps Engineer, and Project Managers.

### Responsibilities
- Define and maintain the release calendar in coordination with Project Managers
- Gate releases on completion of the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Coordinate with Developers and DevOps Engineer to schedule deployment windows and rollback plans
- Draft or review release notes with input from Product Managers
- Communicate release outcomes and known issues to stakeholders and support teams

### Goals
- Deliver releases on schedule with minimal disruption to production
- Maintain a clear audit trail of every release decision
- Reduce mean time to detect and recover from release failures

### Typical Communication
- Pre-release readiness reviews with QA Lead, DevOps Engineer, and Security Champion
- Release announcements to stakeholders and support channels
- Post-deploy debrief with Project Managers and Developers to capture lessons learned

---

## QA Lead

### Role Summary
The QA Lead defines and owns the test strategy, ensuring quality standards are met before features reach production. They collaborate closely with Developers and Product Managers to validate acceptance criteria and coordinate both manual and automated testing efforts.

### Responsibilities
- Develop and maintain the team's test strategy (unit, integration, end-to-end, exploratory)
- Review acceptance criteria with Product Managers to ensure testability
- Coordinate with Developers to integrate automated tests into CI pipelines
- Sign off on QA readiness as a gate in the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Track defect metrics and surface quality trends to Project Managers

### Goals
- Prevent regressions from reaching production
- Increase automated test coverage sprint over sprint
- Provide clear, data-driven quality signals to the team

### Typical Communication
- Sprint planning with Product Managers and Developers to scope test effort
- Daily syncs during feature completion to track test execution progress
- QA sign-off reports shared with Release Manager before each release

---

## Security Champion

### Role Summary
The Security Champion advocates for security best practices across the team. They review designs and implementations for risks, work with Developers to prioritize vulnerability remediation, and coordinate with Project Managers to ensure security risks are tracked and communicated.

### Responsibilities
- Conduct or facilitate security reviews for significant features and architectural changes
- Partner with Developers to triage and remediate vulnerabilities found in CI security scans
- Act as the security gate in the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
- Advise Project Managers on security-related risks and escalation paths
- Promote security training and awareness within the team

### Goals
- Reduce security vulnerabilities before they reach production
- Embed security practices early in the development lifecycle (shift-left)
- Maintain a clear register of known risks and mitigations

### Typical Communication
- Security review sessions with Developers during design and implementation
- Risk entries added to the project risk register, coordinated with Project Managers
- Pre-release security sign-off shared with Release Manager

---

## UX Designer

### Role Summary
The UX Designer owns the user experience: research, wireframes, prototypes, and usability feedback. They collaborate with Product Managers to define user needs and work directly with Developers to ensure designs are implemented correctly.

### Responsibilities
- Conduct user research and synthesize findings into design requirements
- Produce wireframes, prototypes, and design specifications for features
- Collaborate with Product Managers on problem framing and success criteria
- Review implemented features with Developers to validate design fidelity
- Gather and incorporate usability feedback into iterative improvements

### Goals
- Deliver intuitive, accessible, and user-centric experiences
- Reduce rework caused by unclear or undiscovered user needs
- Create reusable design patterns and documentation

### Typical Communication
- Design reviews and critique sessions with Developers and Product Managers
- Usability testing reports shared with Product Managers and Project Managers
- Design handoff notes and annotated specs in the project wiki or design tool

---

## DevOps Engineer

### Role Summary
The DevOps Engineer maintains CI/CD pipelines, infrastructure, and deployment automation. They partner with Developers and the Release Manager to ensure reliable, repeatable delivery, and support security scanning and observability tooling.

### Responsibilities
- Build and maintain CI/CD pipelines used by Developers for automated tests, linting, and deployments
- Manage infrastructure provisioning and environment configuration
- Collaborate with the Release Manager to execute and verify production deployments
- Integrate security and quality scanning tools into the pipeline in coordination with the Security Champion and QA Lead
- Monitor system health and respond to infrastructure-related incidents

### Goals
- Maximize deployment frequency and reliability
- Minimize manual toil through automation
- Ensure infrastructure changes are auditable, reproducible, and secure

### Typical Communication
- Infrastructure change proposals reviewed with Developers and Release Manager
- Deployment runbooks and post-deploy verification results shared with Project Managers
- Incident updates and post-mortems coordinated with the broader team

---

## Stakeholder / Domain Liaison

### Role Summary
The Stakeholder / Domain Liaison represents a specific business function or domain (e.g., marketing, sales, legal, customer support). They provide ongoing requirements, feedback, and domain expertise, and participate in planning and retrospectives as needed.

### Responsibilities
- Provide domain-specific requirements and constraints to Product Managers
- Review and accept delivered features from a business perspective
- Surface business risks and priorities to Project Managers throughout the project lifecycle
- Participate in sprint reviews and retrospectives when relevant to their domain
- Act as an escalation contact for domain-specific decisions or blockers

### Goals
- Ensure delivered features serve real business and user needs
- Maintain alignment between engineering delivery and business expectations
- Reduce feedback cycles by engaging early and continuously

### Typical Communication
- Requirement and feedback sessions with Product Managers
- Sprint review attendance and sign-off for domain-relevant features
- Escalation coordination with Project Managers for business-impacting decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

