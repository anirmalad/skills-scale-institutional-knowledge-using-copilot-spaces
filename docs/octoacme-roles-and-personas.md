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

## UX Designer

### Role Summary
UX Designers guide product usability and design direction, working with Product Managers and Developers to ensure features address user needs and incorporate design best practices. They bridge user research and technical feasibility.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and detailed design specifications
- Collaborate with Product and Engineering to validate feasibility and design implementation
- Ensure accessibility standards and brand consistency
- Iterate on designs based on feedback and testing results
- Document design decisions and design systems

### Goals
- Deliver intuitive, user-centric product experiences
- Reduce usability issues and support burden
- Enable faster feature adoption and user satisfaction

### Interaction with Existing Roles
- **Product Managers**: Align on user problems, research findings, and success metrics
- **Developers**: Collaborate on technical constraints, implementation details, and design specifications
- **Project Managers**: Provide design timelines and blockers to planning
- **QA Leads**: Share design specs and acceptance criteria for visual/interaction testing

### Typical Communication
- Design critique sessions with PM and engineering leads
- Sprint planning and standups (visual/design updates)
- User testing reports and design iteration notes
- Design system documentation and specifications

---

## QA Lead

### Role Summary
QA Leads own the overall test strategy, ensure coverage and quality standards, and coordinate manual and automated testing efforts across the team. They are responsible for defining what "done" means from a quality perspective.

### Responsibilities
- Define and maintain test plans and test strategies
- Oversee automated testing pipelines (unit, integration, end-to-end)
- Coordinate manual QA and acceptance testing efforts
- Collaborate on acceptance criteria with Product and Development teams
- Identify quality risks and bottlenecks
- Document test cases and maintain test coverage metrics
- Facilitate quality improvements and post-release verification

### Goals
- Ensure quality standards are met before release
- Reduce bugs and regressions in production
- Enable faster, more confident delivery

### Interaction with Existing Roles
- **Developers**: Define acceptance criteria, collaborate on test strategies, review automated test coverage
- **Product Managers**: Align on quality expectations and acceptance criteria
- **Project Managers**: Flag quality risks and blockers to timeline
- **SREs**: Share monitoring and observability requirements
- **UX Designers**: Validate visual and interaction requirements in testing

### Typical Communication
- Sprint planning and standups (test coverage updates)
- PR reviews and code quality discussions
- Test result reports and quality dashboards
- Release readiness assessments

---

## Site Reliability Engineer (SRE)

### Role Summary
Site Reliability Engineers ensure system reliability, availability, and performance throughout the project lifecycle. They design and implement infrastructure, monitoring, and incident response capabilities.

### Responsibilities
- Design and implement monitoring, alerting, and observability infrastructure
- Plan for incident response, disaster recovery, and failover scenarios
- Collaborate with Developers on scalable and reliable deployments
- Optimize system performance and resource utilization
- Define and track SLOs (Service Level Objectives) and error budgets
- Automate operational tasks and reduce manual toil
- Participate in post-incident reviews and continuous improvement

### Goals
- Maintain high system availability and reliability
- Enable rapid, safe deployments with confidence
- Reduce mean time to recovery (MTTR) during incidents

### Interaction with Existing Roles
- **Developers**: Partner on deployment strategies, performance optimization, and observability instrumentation
- **Project Managers**: Communicate reliability risks and deployment readiness
- **QA Leads**: Collaborate on performance testing and chaos engineering
- **Product Managers**: Align on performance expectations and SLOs

### Typical Communication
- Release planning and deployment coordination
- On-call escalations and incident response
- Performance and reliability metrics dashboards
- Infrastructure and operations documentation

---

## Business Analyst

### Role Summary
Business Analysts bridge business requirements and technical execution, working with Product, Project Managers, and Developers to shape deliverables and minimize ambiguity. They clarify stakeholder needs and translate them into actionable specifications.

### Responsibilities
- Elicit, document, and prioritize functional and non-functional requirements
- Translate stakeholder needs into clear, testable user stories and acceptance criteria
- Identify process gaps, inefficiencies, and opportunities for improvement
- Support backlog refinement and requirements clarification sessions
- Maintain requirements traceability and change logs
- Validate that delivered solutions meet business objectives
- Facilitate communication between business stakeholders and technical teams

### Goals
- Reduce ambiguity and rework by clearly defining requirements upfront
- Ensure solutions deliver measurable business value
- Accelerate onboarding and reduce knowledge silos

### Interaction with Existing Roles
- **Product Managers**: Collaborate on requirements prioritization and user story refinement
- **Project Managers**: Support planning and risk identification
- **Developers**: Clarify acceptance criteria and technical feasibility
- **QA Leads**: Define testable requirements and acceptance criteria
- **Stakeholders**: Gather business needs and validate delivery against objectives

### Typical Communication
- Requirements workshops and discovery sessions
- User story and acceptance criteria documentation
- Stakeholder updates and validation meetings
- Process documentation and decision logs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific personas when clarifying responsibilities in project planning, execution, and retrospectives.
