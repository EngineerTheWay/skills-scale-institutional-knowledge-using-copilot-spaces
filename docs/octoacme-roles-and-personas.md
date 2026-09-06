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

## Delivery Managers

### Role Summary
Delivery Managers turn the plan into a predictable delivery rhythm. They focus on flow, dependencies, and removing impediments while the Project Manager remains accountable for the overall project plan.

### Responsibilities
- Track delivery progress, team capacity, milestones, and cross-team dependencies
- Facilitate delivery syncs and escalate blockers that the team cannot resolve
- Keep status, risks, and decisions current with the Project Manager
- Coordinate handoffs between planning, execution, QA, and release

### Typical Interactions
- Partner with the Project Manager on timelines, risks, and stakeholder updates
- Work with the Product Manager to sequence increments without losing product priorities
- Help Developers and QA/Testing resolve blockers and maintain a clear Definition of Done
- Surface delivery trade-offs and escalations to Stakeholders with clear options

### Ownership and Decision-Making
The Delivery Manager owns delivery flow and escalation follow-through. The Project Manager owns the project baseline; the Product Manager owns priority and outcome decisions.

---

## Technical Leads

### Role Summary
Technical Leads guide the technical approach and make implementation trade-offs visible. They provide technical direction without replacing Developers' ownership of implementation.

### Responsibilities
- Lead technical discovery, estimates, design decisions, and technical risk mitigation
- Define or review architecture, integration points, observability, and non-functional requirements
- Break technically complex work into implementable increments
- Support code reviews and document decisions that affect scope or maintainability

### Typical Interactions
- Partner with the Project Manager on feasibility, estimates, dependencies, and technical risks
- Work with the Product Manager to explain technical trade-offs and impact on outcomes
- Guide Developers while inviting their estimates, reviews, and implementation feedback
- Collaborate with QA/Testing on testability and with Stakeholders when technical constraints affect commitments

### Ownership and Decision-Making
The Technical Lead owns the recommended technical approach and technical escalation path. Developers own implementation details within that approach; the Product Manager and Stakeholders decide business and scope trade-offs.

---

## Design/UX Leads

### Role Summary
Design/UX Leads represent user needs and ensure that proposed solutions are usable, accessible, and coherent.

### Responsibilities
- Lead discovery, user flows, prototypes, and usability or accessibility considerations
- Maintain design decisions and acceptance guidance for user-facing work
- Validate solutions with users or representative feedback before and during delivery
- Identify experience risks and propose measurable usability outcomes

### Typical Interactions
- Partner with the Product Manager on user problems, research, and success metrics
- Work with the Project Manager on design milestones, dependencies, and stakeholder reviews
- Collaborate with Developers and QA/Testing to clarify behavior, accessibility, and visual acceptance criteria
- Present options and evidence to Stakeholders when experience decisions require alignment

### Ownership and Decision-Making
The Design/UX Lead owns the user experience recommendation and design handoff. The Product Manager owns product prioritization, while Developers confirm feasibility and QA/Testing validates agreed behavior.

---

## Business Analysts

### Role Summary
Business Analysts translate business needs into shared, testable requirements and make assumptions and gaps explicit.

### Responsibilities
- Elicit, document, and trace requirements, rules, workflows, and dependencies
- Refine backlog items with acceptance criteria and examples
- Identify impacted processes, users, systems, and data
- Support scope clarification and verify that delivered behavior matches the agreed need

### Typical Interactions
- Work with the Product Manager and Stakeholders to clarify outcomes and resolve competing requirements
- Coordinate with the Project Manager on scope, decisions, risks, and requirements readiness
- Pair with Developers and QA/Testing to make requirements implementable and testable
- Record open questions and escalate unresolved business decisions to the appropriate Stakeholder

### Ownership and Decision-Making
The Business Analyst owns requirements clarity and traceability, not priority or implementation. The Product Manager approves product intent; Stakeholders make decisions about business policy and scope.

---

## Release Managers

### Role Summary
Release Managers coordinate the transition from completed work to a safe, communicated release. They make readiness, rollback, and handoff decisions visible.

### Responsibilities
- Maintain the release plan, readiness checklist, deployment window, and go/no-go inputs
- Confirm acceptance criteria, CI, security checks, release notes, smoke tests, and rollback plans
- Coordinate staging, production deployment, post-deployment verification, and release communication
- Capture release issues and follow-up actions for the retrospective

### Typical Interactions
- Partner with the Project Manager on milestones, dependencies, risks, and stakeholder communications
- Work with the Product Manager and Stakeholders on scope, approval, and release messaging
- Coordinate with Developers and QA/Testing on defect status, verification, and rollback readiness
- Hand operational context to the Support/Operations Representative and escalate unresolved release risks

### Ownership and Decision-Making
The Release Manager owns release coordination and readiness evidence. The Product Manager or designated Stakeholder makes the business go/no-go decision; Developers and QA/Testing provide technical and quality recommendations.

---

## Support/Operations Representatives

### Role Summary
Support/Operations Representatives bring production readiness and customer-support perspectives into delivery and own the operational handoff.

### Responsibilities
- Define monitoring, alerting, runbook, support, and operational acceptance needs
- Review deployment, rollback, migration, and incident-response plans
- Prepare support communications and known-issue guidance
- Monitor early-life behavior and feed incidents and customer feedback into follow-up work

### Typical Interactions
- Work with the Release Manager on deployment windows, verification, rollback, and handoff
- Collaborate with Developers and QA/Testing on observability, failure modes, and operational tests
- Advise the Project Manager on operational risks and coordinate incident escalations
- Partner with the Product Manager and Stakeholders to prioritize customer-impacting fixes and improvements

### Ownership and Decision-Making
The Support/Operations Representative owns operational readiness and support handoff. The Release Manager coordinates the release; Developers address technical issues; the Product Manager prioritizes follow-up work.

---

## Security/Compliance Leads

### Role Summary
Security/Compliance Leads identify security, privacy, regulatory, and control requirements early and provide evidence-based risk decisions.

### Responsibilities
- Assess security and compliance risks, requirements, data handling, and threat scenarios
- Define required controls, reviews, tests, and evidence for the work
- Review designs, implementation, dependencies, and release readiness for sensitive changes
- Record exceptions, mitigations, and escalation paths for unresolved risks

### Typical Interactions
- Partner with the Project Manager on the risk register, dependencies, and escalation timing
- Work with the Product Manager and Stakeholders to balance risk, scope, and business deadlines
- Advise the Technical Lead and Developers on secure design and implementation controls
- Coordinate with QA/Testing and the Release Manager on security scans, evidence, and go/no-go recommendations

### Ownership and Decision-Making
The Security/Compliance Lead owns security and compliance recommendations and exception documentation. The accountable Stakeholder accepts residual business risk; the Release Manager ensures decisions are reflected in release readiness.

---

## Persona coverage across the project lifecycle

- **Initiation:** Product Manager, Business Analyst, Design/UX Lead, Technical Lead, and Security/Compliance Lead clarify the problem, users, feasibility, and risks; the Project Manager records the decision and initial plan.
- **Planning:** Project Manager and Delivery Manager establish milestones and dependencies, while the Product Manager, Business Analyst, Technical Lead, Design/UX Lead, and QA/Testing make the backlog and Definition of Done ready.
- **Execution:** Delivery Manager tracks flow and escalations; Technical Lead, Design/UX Lead, Business Analyst, Developers, and QA/Testing resolve implementation questions and verify increments.
- **Release:** Release Manager coordinates readiness and deployment with Developers, QA/Testing, Security/Compliance Lead, Support/Operations Representative, Project Manager, Product Manager, and Stakeholders.
- **Retrospective:** Project Manager facilitates the review; every role contributes evidence, identifies improvement actions, and accepts an owner and due date for follow-through.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
