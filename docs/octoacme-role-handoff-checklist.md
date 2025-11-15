# OctoAcme — Role Handoff & Communication Checklist

## Purpose
Ensure smooth handoffs and clear communication between roles throughout the project lifecycle. This checklist reduces dependency risks and improves accountability. Created to address process gaps identified in [issue #4](https://github.com/kohkimakimoto/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).

## Key Handoff Scenarios

### Product Ideation → Requirements Definition

**From: Product Manager**
- [ ] Problem statement documented
- [ ] User needs and success metrics defined
- [ ] Initial stakeholder alignment obtained
- [ ] Business case and priorities established

**To: Business Analyst**
- [ ] Gather detailed business requirements
- [ ] Create process flows and data models
- [ ] Validate requirements with stakeholders
- [ ] Document acceptance criteria

**Communication**: Schedule requirements workshop with PM, BA, and key stakeholders.

---

### Requirements → Design

**From: Business Analyst**
- [ ] Detailed requirements documented
- [ ] User stories with acceptance criteria
- [ ] Process flows and business rules
- [ ] Data requirements specified

**To: UX/UI Designer**
- [ ] Translate requirements into user flows
- [ ] Create wireframes and prototypes
- [ ] Conduct usability testing
- [ ] Ensure accessibility compliance

**Communication**: Design review meeting with PM, BA, Designer, and Tech Lead.

---

### Design → Development

**From: UX/UI Designer**
- [ ] Design mockups and specifications complete
- [ ] Design system components documented
- [ ] Interaction patterns defined
- [ ] Accessibility requirements specified
- [ ] Assets and design files provided

**To: Developers**
- [ ] Review design feasibility
- [ ] Clarify technical constraints
- [ ] Implement features per specs
- [ ] Validate implementation against designs

**Communication**: Design handoff meeting with Designer, Developers, and Scrum Master.

---

### Development → Quality Assurance

**From: Developers**
- [ ] Feature implemented and unit tested
- [ ] PR merged to main/develop branch
- [ ] Test environment deployed
- [ ] Known issues or limitations documented

**To: QA/Testing**
- [ ] Execute test cases against acceptance criteria
- [ ] Perform regression testing
- [ ] Document defects and edge cases
- [ ] Sign off on feature quality

**Communication**: Demo session and QA walkthrough facilitated by Scrum Master.

---

### Pre-Release Coordination

**From: Development Team + QA**
- [ ] All features tested and approved
- [ ] Security scans passed
- [ ] Performance benchmarks met
- [ ] Code freeze communicated

**To: Release Manager**
- [ ] Verify release readiness checklist
- [ ] Coordinate release schedule
- [ ] Prepare rollback plan
- [ ] Monitor quality gates

**Coordination**: Release planning meeting with Release Manager, PM, Tech Lead, and QA.

---

### Release Documentation

**From: Release Manager**
- [ ] Release scope and timeline finalized
- [ ] Deployment plan documented
- [ ] Stakeholder communication drafted

**To: Technical Writer**
- [ ] Draft release notes
- [ ] Update user documentation
- [ ] Create migration guides (if needed)
- [ ] Publish customer-facing announcements

**Communication**: Collaborate via shared document with review cycle.

---

### Post-Release → Monitoring & Feedback

**From: Release Manager**
- [ ] Deployment completed successfully
- [ ] Post-deployment checks passed
- [ ] Release metrics tracked
- [ ] Stakeholders notified

**To: Product Manager + Team**
- [ ] Monitor user feedback and metrics
- [ ] Track success metrics from one-pager
- [ ] Identify follow-up improvements
- [ ] Plan next iteration

**Communication**: Post-release retrospective facilitated by Scrum Master.

---

## Ongoing Communication Patterns

### Daily (for active projects)
- **Standup (15 min)**: Facilitated by Scrum Master
  - Attendees: Developers, QA, UX Designer, Scrum Master, PM (optional)
  - Focus: Progress, blockers, daily commitments
  - Output: Updated task board, identified blockers

### Weekly
- **PM + PdM Sync**: Project status, priorities, risks
- **Delivery Sync**: Cross-functional progress review
  - Attendees: PM, PdM, Tech Lead, Scrum Master, Release Manager
  - Focus: Milestone progress, dependencies, risks
  - Output: Status report, updated timeline

### Per Sprint/Iteration
- **Sprint Planning**: Facilitated by Scrum Master
  - Attendees: Full team
  - Output: Sprint backlog, task assignments
  
- **Sprint Review/Demo**: Product demonstration
  - Attendees: Team + stakeholders
  - Output: Feedback, acceptance decisions

- **Retrospective**: Facilitated by Scrum Master
  - Attendees: Team members
  - Output: Action items for improvement

### As Needed
- **Design Reviews**: Designer presents to team
- **Architecture Reviews**: Technical decisions
- **Requirements Workshops**: BA facilitates with stakeholders
- **Release Planning**: Coordinated by Release Manager

---

## Handoff Best Practices

### For All Handoffs
1. **Schedule dedicated handoff meeting** — don't rely on async-only communication
2. **Document and share artifacts** — ensure receiving party has all materials
3. **Allow for questions** — provide contact for follow-up clarifications
4. **Confirm understanding** — receiving party summarizes their understanding
5. **Set next checkpoints** — agree on when to sync again
6. **Update tracking systems** — move items to correct status in project board

### When Blockers Occur
1. **Identify early** — raise in standup or immediately if critical
2. **Escalate appropriately**:
   - Team-level: Scrum Master facilitates resolution
   - Cross-team: PM coordinates with dependencies
   - Business decision: Product Manager engages stakeholders
   - Technical architecture: Tech Lead convenes review
3. **Document resolution** — capture in issue tracker or decision log
4. **Follow up** — verify blocker is actually resolved

### Knowledge Transfer
- **Document decisions**: Use ADRs (Architecture Decision Records) for significant choices
- **Record meetings**: Keep notes in shared docs with action items
- **Maintain artifacts**: Store in repo or wiki for discoverability
- **Update regularly**: Keep documentation current with implementation

---

## Accountability Matrix (RACI)

For major project activities, use RACI to clarify roles:
- **R**esponsible: Does the work
- **A**ccountable: Approves and owns outcome
- **C**onsulted: Provides input
- **I**nformed: Kept in the loop

### Example: Feature Implementation

| Activity | PM | PdM | Dev | QA | Scrum Master | Designer | BA | Tech Writer | Release Mgr |
|----------|----|----|-----|----|--------------|---------|----|-------------|-------------|
| Requirements | I | A | C | C | C | C | R | I | I |
| Design | I | C | C | I | I | A/R | C | I | I |
| Development | I | C | A/R | C | C | C | I | I | I |
| Testing | I | C | C | A/R | C | I | I | I | I |
| Release | C | C | C | C | I | I | I | R | A |
| Documentation | I | C | C | I | I | C | C | A/R | C |

Customize this matrix for your project and document in the project charter.

---

## Escalation & Decision Authority

When handoffs stall or conflicts arise:

1. **Team-level resolution** (1-2 days)
   - Facilitated by Scrum Master
   - Team discusses and agrees on path forward

2. **Project Manager escalation** (2-3 days)
   - PM coordinates with dependent teams
   - Adjusts timeline or scope if needed

3. **Product Manager / Tech Lead escalation** (3-5 days)
   - PdM makes priority calls
   - Tech Lead makes technical architecture decisions

4. **Executive sponsor escalation** (5+ days or critical impact)
   - Business-impacting decisions
   - Resource allocation conflicts

---

## Continuous Improvement

This handoff checklist should be:
- Reviewed in sprint retrospectives
- Updated based on team feedback
- Simplified when steps prove unnecessary
- Enhanced when gaps cause issues

For detailed role responsibilities and interaction patterns, refer to [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).

Related documentation:
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
