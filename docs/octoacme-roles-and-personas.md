# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Cross-Functional Support Roles

### UX/UI Designers

#### Role Summary
UX/UI Designers craft user experience flows and visual designs that ensure products are intuitive, accessible, and aligned with user needs. They collaborate throughout the project lifecycle to validate requirements and maintain usability standards.

#### Responsibilities
- Design user experience flows and interface prototypes aligned with product requirements
- Collaborate with Product Managers to understand user needs and validate design concepts
- Work with Developers to ensure designs are feasible and performant
- Maintain design consistency and usability standards throughout delivery
- Participate in user research, testing, and iteration cycles
- Provide design rationale and accessibility considerations to support decision-making

#### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by validating designs early with stakeholders and engineering
- Maintain design consistency across features and releases

#### Key Interactions
- **With Product Managers**: Collaborate on understanding user needs, validating design direction, and aligning with product goals
- **With Developers**: Ensure design feasibility, performance considerations, and implementation details
- **With QA/Testing Leads**: Participate in acceptance criteria definition and usability validation
- **With Technical Architects**: Discuss scalability and technical constraints affecting design

#### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Participation in kickoff and planning meetings
- Design handoffs and feedback during execution
- Demos and usability testing sessions
- Accessibility and design consistency guidelines

---

### QA/Testing Leads

#### Role Summary
QA/Testing Leads own quality assurance processes, define test strategies, coordinate testing execution, and validate that features meet acceptance criteria before release. They partner closely with Developers and Product/Project Managers throughout execution and release phases.

#### Responsibilities
- Define test strategies and quality standards for each feature and release
- Develop test plans, acceptance criteria, and testing checklists
- Coordinate test execution and track test results
- Work with Developers to ensure quality requirements are built in
- Sign off on feature acceptance and release readiness
- Identify and document defects; prioritize resolution with the team
- Support post-release verification and monitor for production issues

#### Goals
- Deliver high-quality, reliable features that meet customer expectations
- Catch defects early and reduce rework in later phases
- Maintain consistent quality standards across releases

#### Key Interactions
- **With Developers**: Define acceptance criteria, coordinate testing, and work through defect resolution
- **With Product Managers**: Validate feature acceptance criteria and quality expectations
- **With Project Managers**: Track test progress, report blockers, and coordinate release readiness
- **With UX/UI Designers**: Validate usability and accessibility during testing

#### Typical Communication
- Weekly syncs with Developers and Product/Project Managers
- Test plan and acceptance criteria definition during planning
- Defect and issue tracking during execution
- Pre-release checklists and sign-off
- Post-release verification reports

---

### Business Analysts

#### Role Summary
Business Analysts bridge business objectives and technical delivery by gathering requirements, translating business needs into actionable features, and facilitating alignment across stakeholders and teams. They ensure that what is built delivers the intended business value.

#### Responsibilities
- Gather and document business requirements from stakeholders
- Translate business needs into clear, actionable requirements and user stories
- Refine backlog items and ensure acceptance criteria are well-defined
- Facilitate communication between stakeholders and the delivery team
- Validate that features meet business objectives
- Support roadmap development and prioritization
- Document processes and decisions for knowledge retention

#### Goals
- Ensure delivery aligns with business objectives and user needs
- Reduce miscommunication and rework due to unclear requirements
- Accelerate decision-making through clear documentation and stakeholder alignment

#### Key Interactions
- **With Product Managers**: Refine requirements, support backlog prioritization, and validate business objectives
- **With Developers**: Ensure requirements are clear and implementable; support detailed acceptance criteria
- **With Stakeholders**: Gather input, validate assumptions, and communicate progress
- **With Project Managers**: Support planning and risk identification based on business context

#### Typical Communication
- Requirements gathering workshops with stakeholders
- Backlog refinement sessions with Product Managers and Developers
- Weekly syncs with Project/Product Managers
- Stakeholder updates on delivery progress and outcomes
- Documentation of requirements, decisions, and business context

---

### Technical Architects

#### Role Summary
Technical Architects guide technical direction, establish architectural standards, and ensure that solutions are feasible, scalable, and aligned with long-term technical strategy. They partner with Developers, Product Managers, and Project Managers to de-risk major features and integrations.

#### Responsibilities
- Define and communicate technical vision and architectural standards
- Review major feature proposals for technical risk, feasibility, and scalability
- Provide guidance on technology choices and integration approaches
- Identify and mitigate technical dependencies and risks
- Support Developers with architecture decisions and design patterns
- Ensure compliance with security, performance, and maintainability standards
- Participate in planning to estimate technical effort and identify risks

#### Goals
- Build scalable, maintainable, secure technical systems
- Reduce technical risk and rework through early review and guidance
- Enable Developers to make informed technical decisions

#### Key Interactions
- **With Developers**: Provide architectural guidance, review designs, and support technical decision-making
- **With Product Managers**: Assess feasibility of features, identify technical trade-offs, and estimate effort
- **With Project Managers**: Identify technical risks and dependencies; contribute to risk registers
- **With UX/UI Designers**: Discuss technical constraints affecting design and performance

#### Typical Communication
- Technical design reviews and architecture discussions
- Risk assessment and mitigation during planning
- Guidance during execution on implementation decisions
- Escalation of technical risks to Project/Product leadership
- Architecture documentation and standards updates

---

## Interaction Matrix

The following table summarizes typical interactions between roles:

| Role | Interacts With | Primary Communication |
|------|----------------|----------------------|
| **Developers** | PMs, PdMs, QA Leads, Architects | Daily standups, PR reviews, planning |
| **Product Managers** | PMs, Developers, Designers, Analysts, Stakeholders | Weekly syncs, requirements, roadmap |
| **Project Managers** | All roles | Status reports, planning, risk management |
| **UX/UI Designers** | PdMs, Developers, QA Leads, Architects | Design reviews, kickoff, demos |
| **QA/Testing Leads** | Developers, PdMs, PMs, Designers | Test planning, acceptance criteria, release |
| **Business Analysts** | Stakeholders, PdMs, Developers, PMs | Requirements workshops, backlog refinement |
| **Technical Architects** | Developers, PdMs, PMs, Designers | Design reviews, planning, risk assessment |

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in OctoAcme projects
- Reference specific responsibilities and communication patterns when clarifying roles
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- When onboarding new team members, share the persona definition that matches their role
- When facing communication breakdowns, refer to the interaction matrix to ensure all necessary parties are engaged

---

**Last Updated**: May 2026  
**Version**: 2.0 — Expanded with cross-functional support roles
