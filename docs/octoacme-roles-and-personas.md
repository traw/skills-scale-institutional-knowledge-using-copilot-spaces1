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

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master or Delivery Facilitator helps the delivery team use iterative practices effectively, maintain a sustainable flow, and remove obstacles to progress.

### Responsibilities
- Facilitate agreed ceremonies, such as planning, standups, reviews, and retrospectives
- Identify and help remove team-level impediments
- Coach the team on backlog readiness, flow, and continuous improvement
- Promote psychological safety and predictable delivery practices

### Goals
- Improve team effectiveness and delivery flow
- Reduce recurring blockers and wasted handoffs
- Build a culture of learning and continuous improvement

### Typical Communication
- Daily facilitation of delivery-team coordination
- Impediment and dependency updates with the Project Manager
- Backlog-readiness discussions with the Product Manager
- Review of delivery health and action items with Developers and QA/Testing

### Interactions with Existing Roles
The facilitator works with the Project Manager to surface risks and cross-team dependencies, with the Product Manager to improve backlog readiness and planning trade-offs, and with Developers and QA/Testing to resolve blockers. The facilitator supports stakeholders by keeping ceremonies and decision-making focused, while the Product Manager retains ownership of priority and the Project Manager retains ownership of delivery coordination and reporting.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect provides technical direction, makes or facilitates architecture decisions, and helps the team deliver a coherent, maintainable solution.

### Responsibilities
- Establish implementation patterns and technical standards
- Lead design discussions and document important decisions
- Identify architectural, scalability, security, and operability risks
- Support estimation and technical planning
- Review significant implementation approaches and technical debt

### Goals
- Deliver maintainable, secure, and observable solutions
- Reduce avoidable technical risk and rework
- Improve design consistency across components

### Typical Communication
- Technical design and architecture reviews
- Estimation and planning sessions
- Design and code-review discussions
- Technical-risk updates through the Project Manager

### Interactions with Existing Roles
The Technical Lead collaborates with Developers on design, implementation quality, and technical debt; with QA/Testing on testability and critical quality risks; with the Product Manager on the technical implications of product trade-offs; and with the Project Manager on estimates, dependencies, and technical risks. Stakeholders receive concise summaries of major technical decisions and constraints when they affect scope, schedule, or outcomes.

---

## UX / Design Lead

### Role Summary
The UX / Design Lead defines usable, accessible experiences and translates customer and business needs into clear interaction designs.

### Responsibilities
- Understand user needs, workflows, and accessibility requirements
- Create prototypes, interaction specifications, and design guidance
- Validate designs with users and stakeholders
- Maintain design consistency and review implementation against approved designs

### Goals
- Improve usability, accessibility, and customer satisfaction
- Minimize late-stage design changes
- Ensure delivered experiences match validated intent

### Typical Communication
- User research and design critiques
- Story and acceptance-criteria discussions
- Design reviews with Developers and QA/Testing
- Stakeholder and roadmap reviews with the Product Manager

### Interactions with Existing Roles
The UX / Design Lead partners with the Product Manager to turn customer needs into prioritized outcomes, with Developers to assess feasibility and resolve implementation details, and with QA/Testing to define usability and accessibility acceptance expectations. The Project Manager tracks design dependencies and decisions, while stakeholders provide context and approvals for key experience choices.

---

## Release Manager / Delivery Lead

### Role Summary
The Release Manager or Delivery Lead coordinates release readiness and manages the operational process for moving approved changes into production.

### Responsibilities
- Coordinate release windows, approvals, and deployment sequencing
- Maintain the release checklist and rollback plan
- Verify that acceptance criteria, CI, security checks, smoke tests, and communications are complete
- Coordinate release verification and post-deployment follow-up

### Goals
- Reduce release risk and operational surprises
- Make release readiness transparent and repeatable
- Improve recovery from failed or degraded deployments

### Typical Communication
- Release-readiness reviews
- Deployment and rollback coordination
- Post-deployment verification updates
- Status and incident notifications to stakeholders

### Interactions with Existing Roles
The Release Manager works with Developers and QA/Testing to confirm the release candidate and verification results, with the Technical Lead and Security/Compliance Lead on technical and control readiness, and with the Project Manager on scheduling and stakeholder communications. The Product Manager confirms that release scope and customer communications align with product priorities. Support and operational stakeholders are informed before and after release.

---

## Support Lead

### Role Summary
The Support Lead represents customer-impact considerations and operational support needs before, during, and after release.

### Responsibilities
- Prepare support teams for new features and known issues
- Triage customer reports and coordinate escalation
- Summarize recurring support themes and customer impact
- Feed operational feedback into backlog prioritization and incident reviews

### Goals
- Improve customer readiness and support response
- Reduce recurring production and support issues
- Accelerate the flow of customer feedback into product decisions

### Typical Communication
- Pre-release enablement and known-issue briefings
- Production triage and incident updates
- Customer-impact summaries for Product Managers and stakeholders
- Handoff updates with Developers and QA/Testing

### Interactions with Existing Roles
The Support Lead partners with the Product Manager on customer impact and backlog priorities, with Developers and QA/Testing on defect analysis and verification, and with the Release Manager on rollout readiness and customer communications. The Project Manager includes support dependencies and operational risks in plans and escalation tracking, while stakeholders receive relevant impact and recovery updates.

---

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead identifies applicable requirements and verifies that project decisions and releases meet security and compliance obligations.

### Responsibilities
- Define security and compliance requirements and review points
- Identify relevant threats, controls, evidence, and exceptions
- Review designs and releases for required controls
- Coordinate required security reviews and incident response support

### Goals
- Prevent avoidable security and compliance gaps
- Make control status and exceptions visible
- Improve safe and auditable delivery

### Typical Communication
- Threat, design, and compliance reviews
- Security-scan and exception-status updates
- Release-gate and risk discussions
- Incident-response coordination

### Interactions with Existing Roles
The Security / Compliance Lead advises Developers and the Technical Lead on secure implementation and design controls, coordinates validation with QA/Testing, and provides the Project Manager and Release Manager with gate status and unresolved exceptions. The Product Manager and stakeholders are informed when requirements affect scope, priorities, schedule, or customer commitments.

---

## Business Analyst / Program Coordinator

### Role Summary
The Business Analyst or Program Coordinator clarifies requirements, maps process and system dependencies, and helps maintain traceability across decisions and delivery work.

### Responsibilities
- Clarify and document requirements and process changes
- Trace requirements to backlog items, decisions, and acceptance criteria
- Coordinate cross-team inputs and dependency details
- Maintain decision logs and follow up on open questions

### Goals
- Improve requirement completeness and traceability
- Reduce ambiguity and cross-team rework
- Make cross-team coordination and decisions visible

### Typical Communication
- Requirements and process workshops
- Backlog-refinement and acceptance-criteria reviews
- Dependency and decision tracking
- Stakeholder working sessions

### Interactions with Existing Roles
The Business Analyst or Program Coordinator works with the Product Manager to clarify outcomes and scope, with Developers and QA/Testing to make requirements testable, and with the Project Manager to track dependencies and open decisions. They coordinate stakeholder inputs and approvals while preserving the Product Manager's priority authority and the Project Manager's delivery-accountability role.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Projects may adopt the subset of personas that matches their size and operating model; a role may be shared by one person or split across team members without changing the accountability described here.
