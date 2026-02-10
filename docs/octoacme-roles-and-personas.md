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
The Product Owner defines and communicates the product vision, manages the product backlog, and ensures that the team delivers maximum value to customers and stakeholders. They serve as the primary voice of the customer and make key decisions about features and priorities.

### Responsibilities
- Define and communicate product vision and strategy
- Prioritize and maintain the product backlog
- Communicate stakeholder needs and requirements to the development team
- Approve major changes and scope adjustments
- Make trade-off decisions between features, time, and quality
- Validate that delivered features meet business objectives
- Define and measure product success metrics

### Goals
- Maximize product value and return on investment
- Ensure clear product direction and priorities
- Balance stakeholder needs with technical feasibility
- Deliver features that meet customer expectations

### Typical Communication
- Daily collaboration with development team on backlog items
- Regular stakeholder updates on product roadmap and decisions
- Sprint planning and backlog refinement sessions
- Feature acceptance and validation reviews

### Example Scenario
During sprint planning, the Product Owner reviews the prioritized backlog with the team. A critical customer request comes in requiring a scope change. The Product Owner assesses the business impact, consults with stakeholders, and makes a decision to reprioritize the backlog, moving the urgent item to the current sprint while deferring lower-priority work to the next sprint.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams by eliciting, analyzing, and documenting requirements. They ensure that solutions address actual business needs and meet defined acceptance criteria.

### Responsibilities
- Elicit and document business requirements through stakeholder workshops and interviews
- Analyze business processes and identify improvement opportunities
- Define clear acceptance criteria for user stories and features
- Create process flows, use cases, and requirement specifications
- Support Product Owner in backlog refinement and prioritization
- Validate that delivered solutions meet business requirements
- Facilitate communication between business and technical teams

### Goals
- Ensure requirements are clear, complete, and testable
- Reduce ambiguity and rework through thorough analysis
- Enable smooth handoffs between stakeholders and developers
- Support data-driven decision making

### Typical Communication
- Requirements gathering workshops with stakeholders
- User story refinement sessions with development team
- Documentation of business rules and acceptance criteria
- Regular status updates on requirements analysis progress

### Example Scenario
The Business Analyst facilitates a requirements workshop with key stakeholders to gather input for a new customer portal feature. They document functional requirements, create user journey maps, write detailed user stories with acceptance criteria, and work with the UX/UI Designer to ensure the proposed solution addresses user needs. The BA then presents the requirements to the development team during backlog refinement.

---

## UX/UI Designer

### Role Summary
UX/UI Designers create intuitive, accessible, and visually appealing user interfaces that enhance user experience and drive product adoption. They ensure designs meet usability standards and accessibility requirements.

### Responsibilities
- Design user interfaces and interaction patterns
- Create wireframes, mockups, and prototypes
- Conduct user research and usability testing
- Ensure compliance with accessibility standards (e.g., WCAG)
- Maintain design systems and UI component libraries
- Collaborate with developers on design implementation
- Validate designs with end users and stakeholders

### Goals
- Deliver exceptional user experiences
- Ensure accessibility and inclusivity in all designs
- Maintain design consistency across products
- Reduce user friction and increase adoption

### Typical Communication
- Design review sessions with Product Owner and stakeholders
- Collaboration with Business Analysts on user requirements
- Design handoff meetings with developers
- User testing sessions and feedback reviews

### Example Scenario
The UX/UI Designer receives a new feature request for a dashboard redesign. They conduct user interviews to understand pain points, create wireframes showing the proposed layout, develop high-fidelity mockups with the updated visual design, and test the prototype with five end users. Based on feedback, they refine the design and work closely with developers during implementation to ensure the final product matches the approved design and meets accessibility standards.

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and execute software releases across all environments. They ensure quality gates are met, coordinate cross-team activities, and manage deployment schedules to minimize risk and ensure smooth releases.

### Responsibilities
- Plan and schedule release activities across teams
- Coordinate release windows and deployment schedules
- Ensure all quality gates and approval checkpoints are met
- Manage release artifacts, documentation, and communication
- Facilitate go/no-go decision meetings before deployments
- Coordinate rollback procedures if issues arise
- Communicate deployment plans and release status to stakeholders
- Track release metrics and improve release processes

### Goals
- Execute zero-downtime, reliable releases
- Minimize deployment risks and production incidents
- Ensure clear communication about release status
- Continuously improve release processes and automation

### Typical Communication
- Release planning meetings with development and QA teams
- Go/no-go decision meetings with stakeholders
- Deployment status updates and release notes
- Post-release debriefs and improvement discussions

### Example Scenario
The Release Manager coordinates a major product release scheduled for the end of the quarter. They create a detailed release plan, schedule the deployment window, coordinate testing across QA teams, and prepare rollback procedures. On release day, they facilitate a go/no-go meeting where the team reviews test results, security scans, and readiness criteria. After receiving approval, they oversee the deployment, monitor production metrics, and communicate release completion to all stakeholders.

---

## Change Control Coordinator

### Role Summary
Change Control Coordinators oversee the change management process, ensuring that all changes to production systems are properly reviewed, approved, and documented. They manage the change advisory board process and ensure changes follow established procedures.

### Responsibilities
- Review and triage change requests
- Ensure proper impact and risk assessments are completed
- Coordinate Change Advisory Board (CAB) meetings
- Track change requests through approval workflows
- Document change decisions and rationale
- Manage expedited/emergency change procedures
- Monitor change success rates and trends
- Ensure compliance with change management policies

### Goals
- Minimize production disruptions from changes
- Ensure proper oversight and approval of changes
- Maintain audit trail for all production changes
- Balance speed with risk management

### Typical Communication
- Change Advisory Board meetings with cross-functional stakeholders
- Change request reviews with requesters and technical teams
- Risk assessment discussions with Project Manager and technical leads
- Post-implementation reviews and lessons learned sessions

### Example Scenario
A critical security vulnerability is discovered in production requiring an urgent hotfix. The Change Control Coordinator receives an emergency change request, quickly assembles the relevant stakeholders, facilitates a rapid risk assessment, and ensures the change follows expedited approval procedures. They document the justification for the emergency change, coordinate with the Release Manager for immediate deployment, and schedule a post-implementation review to capture lessons learned and ensure proper documentation is completed.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

