# OctoAcme — Responsibility Matrix (RACI)

## Purpose
Define clear accountability for key project activities using the RACI model (Responsible, Accountable, Consulted, Informed) to reduce confusion and ensure smooth execution.

## RACI Definitions

- **R - Responsible**: Person(s) who perform the work
- **A - Accountable**: Person ultimately answerable for the activity (only one per activity)
- **C - Consulted**: People whose opinions are sought (two-way communication)
- **I - Informed**: People who are kept up-to-date (one-way communication)

## Project Lifecycle RACI Matrix

| Activity | Product Owner | Business Analyst | UX/UI Designer | Release Manager | Change Control Coordinator | Developer | Product Manager | Project Manager | QA/Testing | Stakeholders |
|----------|---------------|------------------|----------------|-----------------|----------------------------|-----------|-----------------|-----------------|------------|--------------|
| **Initiation Phase** |
| Define problem statement | C | C | - | - | - | - | R/A | C | - | C |
| Approve project charter | A | - | - | - | - | - | C | R | - | I |
| Identify stakeholders | C | C | - | - | - | - | C | R/A | - | I |
| Define success metrics | R/A | C | - | - | - | - | C | C | - | C |
| **Planning Phase** |
| Create product backlog | R/A | C | C | - | - | C | C | C | - | I |
| Define acceptance criteria | C | R | C | - | - | C | - | C | C | I |
| Estimate effort | C | C | C | - | - | R/A | - | C | C | - |
| Create project plan | C | - | - | C | - | C | - | R/A | C | I |
| Identify risks | C | C | - | C | C | C | C | R/A | C | C |
| Define test strategy | C | C | C | - | - | C | - | C | R/A | - |
| **Design Phase** |
| Gather requirements | C | R/A | C | - | - | C | C | C | C | C |
| Create wireframes/mockups | C | C | R/A | - | - | C | C | - | - | C |
| Conduct usability testing | C | C | R/A | - | - | - | C | - | - | C |
| Review and approve designs | A | C | R | - | - | C | C | C | - | C |
| **Development Phase** |
| Implement features | C | C | C | - | - | R/A | - | C | C | - |
| Write unit tests | - | - | - | - | - | R/A | - | C | C | - |
| Code review | - | - | - | - | - | R/A | - | C | - | - |
| Update documentation | C | C | C | - | - | R/A | - | C | C | - |
| **Testing Phase** |
| Create test cases | C | C | C | - | - | C | - | C | R/A | - |
| Execute testing | C | C | - | C | - | C | - | C | R/A | - |
| Report defects | I | I | I | I | - | I | I | I | R/A | - |
| Accept feature completion | R/A | C | C | - | - | C | - | C | C | I |
| **Release Phase** |
| Plan release | C | - | - | R/A | C | C | C | C | C | I |
| Approve release | A | - | - | C | C | - | C | C | C | I |
| Execute deployment | I | - | - | R/A | C | C | - | C | C | I |
| Verify deployment | C | - | C | R | - | C | - | C | R/A | - |
| Communicate release | C | - | - | R | - | - | C | C | - | R/A |
| **Change Management** |
| Submit change request | C | C | C | C | C | R | C | C | C | C |
| Assess change impact | C | C | C | R | R | C | C | C | C | C |
| Approve change | C | - | - | C | R/A | - | C | C | - | C |
| Implement change | C | C | C | R | - | R/A | - | C | C | - |
| **Ongoing Operations** |
| Prioritize backlog | R/A | C | C | - | - | C | C | C | - | C |
| Manage risks | C | C | - | C | C | C | C | R/A | C | I |
| Status reporting | I | I | I | I | I | I | I | R/A | I | R |
| Stakeholder communication | R/A | C | - | C | - | - | C | R | - | I |
| Escalate blockers | C | C | C | C | C | C | C | R/A | C | I |
| Conduct retrospectives | C | C | C | C | C | R | C | R/A | C | - |

## Handoff Points Between Roles

### Product Owner → Business Analyst
- **When**: After high-level requirements are defined
- **What**: Product vision, business goals, and stakeholder priorities
- **Approval**: Product Owner approves detailed requirements from Business Analyst

### Business Analyst → UX/UI Designer
- **When**: After requirements are documented
- **What**: User stories, acceptance criteria, and process flows
- **Approval**: Business Analyst reviews and provides feedback on designs

### UX/UI Designer → Developer
- **When**: After design approval
- **What**: Design specifications, mockups, and style guides
- **Approval**: UX/UI Designer reviews implementation for design fidelity

### Developer → QA/Testing
- **When**: After code implementation and unit tests complete
- **What**: Feature implementation, test plans, and deployment instructions
- **Approval**: QA approves feature after successful testing

### QA/Testing → Release Manager
- **When**: After testing is complete and approved
- **What**: Test results, known issues, and release artifacts
- **Approval**: Release Manager ensures quality gates met before release

### Release Manager → Change Control Coordinator
- **When**: Before production deployment
- **What**: Release plan, risk assessment, and rollback procedures
- **Approval**: Change Control Coordinator approves change for production

### Any Role → Project Manager
- **When**: Risks, blockers, or issues arise
- **What**: Issue details, impact assessment, and recommended actions
- **Approval**: Project Manager escalates and coordinates resolution

## Role-Specific Approval Authority

### Product Owner
- **Approves**: Product backlog priorities, scope changes, feature acceptance, go/no-go for releases
- **Decision Scope**: Product direction, feature priorities, customer-facing changes

### Project Manager
- **Approves**: Project plans, schedule changes, resource allocation, escalations
- **Decision Scope**: Project execution, timeline adjustments, team coordination

### Release Manager
- **Approves**: Deployment schedules, release readiness, go/no-go for deployments
- **Decision Scope**: Release timing, deployment procedures, rollback decisions

### Change Control Coordinator
- **Approves**: Production changes, emergency changes, change request classification
- **Decision Scope**: Change management compliance, risk acceptance for changes

### Business Analyst
- **Approves**: Requirements completeness, acceptance criteria, documentation quality
- **Decision Scope**: Requirements accuracy, business process alignment

### UX/UI Designer
- **Approves**: Design implementation, accessibility compliance, visual design standards
- **Decision Scope**: User experience quality, design system consistency

## Escalation Matrix

### Level 1: Team-Level Resolution
- **Scope**: Technical issues, minor scope clarifications, day-to-day coordination
- **Owner**: Developer lead, BA, or Designer resolves with peer discussion
- **Timeline**: Resolved within 1-2 days

### Level 2: Project Management Escalation
- **Scope**: Cross-team dependencies, timeline risks, resource conflicts
- **Owner**: Project Manager coordinates with relevant roles
- **Timeline**: Resolved within 3-5 days

### Level 3: Product/Executive Escalation
- **Scope**: Major scope changes, budget issues, strategic decisions
- **Owner**: Product Owner/Manager with executive stakeholders
- **Timeline**: Resolved within 1-2 weeks

### Emergency Escalation
- **Scope**: Production incidents, critical security issues, business-impacting outages
- **Owner**: Change Control Coordinator and Release Manager activate incident response
- **Timeline**: Immediate response, resolution varies by severity

## Risk and Issue Escalation Scenarios

### Scenario 1: Scope Creep Identified
1. **Developer or BA** identifies scope expansion beyond original plan
2. **Project Manager** documents impact on timeline and resources
3. **Product Owner** evaluates business value vs. cost
4. **Decision**: Product Owner approves/rejects with Project Manager updating plan

### Scenario 2: Technical Blocker Impacting Timeline
1. **Developer** identifies critical technical issue
2. **Project Manager** assesses impact on milestones
3. **Product Owner** consulted on priority and trade-offs
4. **Decision**: Team agrees on mitigation (additional resources, timeline adjustment, or scope reduction)

### Scenario 3: Failed Deployment Requiring Rollback
1. **Release Manager** identifies deployment issue in production
2. **Change Control Coordinator** activates emergency change process
3. **Product Owner and Project Manager** informed immediately
4. **Decision**: Release Manager executes rollback, team coordinates root cause analysis

### Scenario 4: Requirements Ambiguity During Development
1. **Developer** flags unclear acceptance criteria
2. **Business Analyst** clarifies with stakeholders
3. **Product Owner** approves any scope adjustments
4. **Decision**: BA updates requirements, development continues

### Scenario 5: User Testing Reveals Major Design Issues
1. **UX/UI Designer** documents usability problems
2. **Product Owner** evaluates impact on release timeline
3. **Project Manager** assesses options (delay release, iterate post-launch, or fast-follow)
4. **Decision**: Product Owner decides path forward with input from stakeholders

## Using This Matrix

1. **At Project Kickoff**: Review RACI matrix with team to ensure clarity
2. **During Planning**: Customize matrix based on project-specific needs
3. **Ongoing**: Reference matrix when questions arise about accountability
4. **Retrospectives**: Update matrix based on lessons learned

## Notes
- Only one person should be **Accountable (A)** for each activity
- Multiple people can be **Responsible (R)** but they share execution
- **Consulted (C)** involves two-way communication (input and feedback)
- **Informed (I)** involves one-way communication (status updates)
- Blank cells (-) indicate the role is not involved in that activity
