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

## Product Owner

### Role Summary
Product Owners are responsible for prioritizing the team's backlog, conveying stakeholder needs, accepting completed work, and ensuring project deliverables align with business objectives. They serve as the voice of the customer and bridge between business requirements and technical implementation.

### Responsibilities
- Prioritize and maintain the product backlog based on business value
- Define and communicate product vision and strategy
- Accept or reject completed work based on acceptance criteria
- Convey stakeholder needs and business requirements to the team
- Ensure deliverables align with business objectives and customer needs
- Make trade-off decisions on scope, timeline, and features
- Collaborate with Project Manager on release planning and scheduling

### Goals
- Maximize business value delivered in each iteration
- Ensure clear, well-defined acceptance criteria for all work items
- Maintain stakeholder satisfaction and alignment
- Balance competing priorities effectively

### Typical Communication
- Daily collaboration with development team on clarifications
- Weekly sync with Project Manager and Product Manager
- Regular stakeholder reviews and feedback sessions
- Backlog refinement and sprint planning meetings

### Interactions with Other Roles
- **Product Managers**: Aligns on product vision and strategic priorities
- **Project Managers**: Coordinates on delivery timelines and resource constraints
- **Developers**: Clarifies requirements and acceptance criteria
- **Business Analyst**: Works together on requirements gathering and refinement
- **UX/UI Designer**: Collaborates on user experience and design decisions

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads own and coordinate all testing efforts across the project lifecycle. They ensure deliverables meet quality standards through comprehensive test planning, execution, and validation.

### Responsibilities
- Define overall test strategy and quality standards
- Coordinate testing efforts across all project phases
- Define and validate acceptance criteria with stakeholders
- Oversee test case creation, execution, and defect tracking
- Ensure adequate test coverage for functional and non-functional requirements
- Lead quality reviews and sign-off processes
- Identify quality risks and propose mitigation strategies
- Mentor team members on quality best practices

### Goals
- Ensure all deliverables meet defined quality standards
- Minimize defects reaching production
- Establish and maintain effective testing processes
- Foster a quality-first culture within the team

### Typical Communication
- Daily standup participation and test status updates
- Weekly quality metrics reviews with Project Manager
- Regular collaboration with Developers on defect resolution
- Test plan reviews with stakeholders and Business Analyst

### Interactions with Other Roles
- **Developers**: Collaborates on test automation, defect resolution, and quality standards
- **Product Owner**: Validates acceptance criteria and participates in work acceptance
- **Business Analyst**: Works together to define testable requirements
- **DevOps Engineer**: Coordinates on test environment setup and CI/CD integration
- **Project Manager**: Reports quality metrics and risks

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, implement, and maintain CI/CD pipelines, manage deployment environments, and advise on operational reliability. They enable rapid, reliable software delivery through automation and infrastructure excellence.

### Responsibilities
- Design and maintain CI/CD pipelines for automated builds and deployments
- Manage development, staging, and production environments
- Implement infrastructure as code and configuration management
- Monitor system health, performance, and availability
- Advise on operational reliability and scalability concerns
- Automate repetitive operational tasks
- Ensure security best practices in deployment processes
- Support incident response and troubleshooting

### Goals
- Minimize deployment time and manual effort
- Maximize system reliability and uptime
- Enable rapid feedback through automated testing and monitoring
- Reduce time from code commit to production deployment

### Typical Communication
- Participation in sprint planning for infrastructure work
- Daily coordination with Developers on build and deployment issues
- Regular sync with QA Lead on test environment needs
- Incident post-mortems and operational reviews

### Interactions with Other Roles
- **Developers**: Supports with build issues, deployment automation, and environment access
- **QA Lead**: Provides and maintains test environments
- **Project Manager**: Coordinates on infrastructure timelines and risks
- **Product Manager**: Aligns on product infrastructure needs and operational requirements

---

## UX/UI Designer

### Role Summary
UX/UI Designers are responsible for user experience and interface design. They ensure solutions are user-centric, accessible, and visually consistent while meeting business objectives.

### Responsibilities
- Design user interfaces and interaction patterns
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Establish and maintain design systems and style guides
- Ensure accessibility standards are met
- Validate designs with users and stakeholders
- Collaborate on feature specifications and acceptance criteria
- Provide design guidance throughout implementation

### Goals
- Deliver intuitive, user-friendly interfaces
- Ensure consistent user experience across the product
- Meet accessibility and usability standards
- Balance user needs with technical constraints and business goals

### Typical Communication
- Design reviews with Product Owner and stakeholders
- Regular collaboration sessions with Developers
- User research findings and usability test results
- Weekly design critiques and feedback sessions

### Interactions with Other Roles
- **Product Owner**: Collaborates on feature priorities and user needs
- **Developers**: Works closely on implementation feasibility and design handoff
- **Business Analyst**: Aligns on user requirements and use cases
- **QA Lead**: Coordinates on usability testing and acceptance criteria

---

## Business Analyst

### Role Summary
Business Analysts gather and refine requirements, interpret business needs, and translate them into actionable tasks for team members. They bridge communication between the business, stakeholders, and technical teams.

### Responsibilities
- Gather and document business requirements from stakeholders
- Analyze and refine requirements for clarity and completeness
- Translate business needs into user stories and acceptance criteria
- Facilitate requirements workshops and stakeholder interviews
- Create process flows, use cases, and business rules documentation
- Validate that delivered solutions meet business requirements
- Identify gaps and opportunities for process improvement
- Support data analysis and reporting needs

### Goals
- Ensure requirements are clear, complete, and actionable
- Maintain alignment between business needs and technical solutions
- Minimize rework through thorough requirements analysis
- Facilitate effective communication across business and technical teams

### Typical Communication
- Regular stakeholder meetings for requirements gathering
- Collaboration sessions with Product Owner and UX/UI Designer
- Daily interaction with Developers for clarifications
- Requirements review meetings with QA Lead

### Interactions with Other Roles
- **Product Owner**: Collaborates on backlog prioritization and requirements refinement
- **Stakeholders**: Primary liaison for gathering business needs and feedback
- **Developers**: Clarifies requirements and answers technical questions
- **QA Lead**: Works together to define testable acceptance criteria
- **UX/UI Designer**: Aligns on user flows and experience requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

