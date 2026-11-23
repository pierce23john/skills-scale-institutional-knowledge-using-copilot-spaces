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
Release Managers plan and coordinate releases, verify that a change is ready for deployment, and manage rollout and rollback decisions.

### Responsibilities
- Define release scope, timing, and deployment dependencies
- Confirm that acceptance criteria, tests, security checks, and release notes are complete
- Coordinate staged rollouts and post-deployment verification
- Prepare rollback or mitigation plans and lead release communications

### Goals
- Reduce deployment risk and service disruption
- Make release readiness and ownership explicit
- Coordinate reliable, observable rollouts

### Typical Communication
- Release planning and go/no-go reviews
- Deployment schedules and stakeholder announcements
- Rollback decisions and post-release verification reports

### Key Interactions
- Developers provide build and deployment readiness evidence and execute technical changes.
- Project Managers align release timing with milestones and coordinate stakeholder communication.
- QA Leads provide acceptance and quality evidence.
- Support and Operations Leads prepare for rollout, incident handling, and customer impact.

---

## Quality Assurance Leads

### Role Summary
Quality Assurance (QA) Leads define and coordinate the test strategy, quality evidence, and verification needed before delivery.

### Responsibilities
- Define test scope and test levels for product changes
- Establish acceptance and regression criteria with Product Managers
- Coordinate manual and automated testing
- Track defects, quality risks, and verification status

### Goals
- Prevent defects and validate behavior against acceptance criteria
- Improve test coverage and feedback speed
- Make quality status visible at release gates

### Typical Communication
- Test planning and defect triage
- Quality status updates and release readiness reviews
- Acceptance and regression results

### Key Interactions
- Product Managers define intended outcomes and acceptance criteria.
- Developers address testability concerns, defect fixes, and test automation.
- Project Managers track QA dependencies and escalate schedule risks.
- Release Managers use QA evidence as part of go/no-go decisions.
- Security and Compliance Leads collaborate on required control validation.

---

## UX/Design Leads

### Role Summary
UX/Design Leads represent user needs, lead experience design, and validate usability across the product lifecycle.

### Responsibilities
- Research and synthesize user needs and workflows
- Create interaction designs, prototypes, and experience standards
- Review proposed solutions for usability and accessibility
- Validate designs through testing and incorporate feedback

### Goals
- Improve usability and accessibility
- Ensure consistent product experiences
- Reduce rework caused by unclear or unvalidated experience decisions

### Typical Communication
- Design reviews and user research readouts
- Collaboration sessions with product and engineering teams
- Usability findings and design acceptance updates

### Key Interactions
- Product Managers align experience decisions with customer and business outcomes.
- Developers collaborate on feasible implementation and interaction details.
- QA Leads include usability and accessibility checks in verification plans.
- Support and Operations Leads share recurring customer experience issues.

---

## Data/Analytics Leads

### Role Summary
Data/Analytics Leads define success metrics, instrumentation, reporting, and experimentation needed to make project decisions evidence-based.

### Responsibilities
- Translate product goals into measurable success metrics
- Define event instrumentation and data quality requirements
- Plan experiments and establish evaluation criteria
- Produce findings and recommendations for project stakeholders

### Goals
- Make outcomes measurable and visible
- Improve the quality and reliability of product decisions
- Identify user, adoption, and operational trends

### Typical Communication
- Metric and instrumentation reviews
- Experiment plans and evaluation reports
- Data findings and stakeholder decision summaries

### Key Interactions
- Product Managers use metrics to prioritize work and validate outcomes.
- Developers implement telemetry and resolve data availability issues.
- Project Managers include reporting needs and analysis timelines in plans.
- UX/Design Leads share research findings and user behavior questions.

---

## Support and Operations Leads

### Role Summary
Support and Operations Leads provide operational readiness, customer feedback, incident coordination, and ongoing support perspective.

### Responsibilities
- Prepare support documentation and operational runbooks
- Forecast support impact and staffing needs
- Triage customer reports and recurring issues
- Coordinate incident response and communicate customer impact

### Goals
- Improve supportability and operational resilience
- Accelerate resolution of customer-impacting issues
- Feed real operational and customer evidence back into the backlog

### Typical Communication
- Operational readiness reviews
- Incident updates and handoffs
- Support trend reports and customer feedback summaries

### Key Interactions
- Developers and QA Leads address supportability, reproducibility, and defect resolution.
- Product Managers prioritize recurring customer and operational needs.
- Project Managers include rollout risk, communications, and dependency planning.
- Release Managers coordinate rollout readiness and rollback communications.

---

## Security and Compliance Leads

### Role Summary
Security and Compliance Leads advise on security requirements, threat exposure, controls, regulatory obligations, and compliance evidence.

### Responsibilities
- Identify applicable security and compliance requirements
- Review designs and implementation for control and threat risks
- Coordinate remediation and risk acceptance decisions
- Maintain evidence needed for audits and release approvals

### Goals
- Reduce security and compliance risk
- Make control ownership and evidence requirements visible
- Enable informed, timely risk decisions

### Typical Communication
- Security and compliance reviews
- Threat and risk assessments
- Remediation status and release gate updates

### Key Interactions
- Developers implement controls and resolve security findings.
- QA Leads validate security requirements and incorporate required testing.
- Project Managers track compliance dependencies and escalation decisions.
- Release Managers verify required evidence before go/no-go decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

