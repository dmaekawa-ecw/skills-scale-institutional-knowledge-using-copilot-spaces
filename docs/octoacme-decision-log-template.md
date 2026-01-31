# OctoAcme — Decision Log Template

## Purpose
Track significant project decisions, rationale, and outcomes to maintain context and support future decision-making.

## How to Use
- Add a new entry for each significant decision
- Include context, options considered, and rationale
- Update outcomes as they become known
- Reference this log in project retrospectives

---

## Decision Entry Template

### Decision [ID]: [Brief Title]

**Date:** YYYY-MM-DD

**Status:** [Proposed | Approved | Rejected | Superseded]

**Decision Makers:**
- Name (Role)
- Name (Role)

**Context:**
Describe the situation that necessitated this decision. What problem are we solving? What are the constraints?

**Options Considered:**
1. **Option A:** Description
   - Pros:
   - Cons:
2. **Option B:** Description
   - Pros:
   - Cons:
3. **Option C:** Description
   - Pros:
   - Cons:

**Decision:**
State the chosen option clearly.

**Rationale:**
Explain why this option was selected over alternatives. Include key factors, trade-offs, and alignment with project goals.

**Implications:**
- Impact on timeline:
- Impact on resources:
- Impact on other teams/systems:
- Technical debt or future considerations:

**Action Items:**
- [ ] Action 1 (Owner, Due Date)
- [ ] Action 2 (Owner, Due Date)

**Outcome (Update Later):**
Document the actual results and lessons learned after implementation.

**Related Decisions:**
- Link to related or superseded decisions

---

## Example Decision Log Entries

### Decision 001: Adopt GitHub Projects for Project Tracking

**Date:** 2024-01-15

**Status:** Approved

**Decision Makers:**
- Jane Smith (Project Manager)
- Bob Johnson (Engineering Lead)

**Context:**
Team needed a unified project tracking tool to improve visibility and collaboration across distributed team members.

**Options Considered:**
1. **GitHub Projects:** Integrated with our workflow, native GitHub integration
   - Pros: Seamless integration, no additional cost, familiar to team
   - Cons: Limited reporting features, newer tool
2. **Jira:** Feature-rich, established tool
   - Pros: Advanced reporting, well-known
   - Cons: Additional cost, requires separate login, learning curve
3. **Trello:** Simple, visual
   - Pros: Easy to use, quick setup
   - Cons: Limited automation, separate system

**Decision:**
Adopt GitHub Projects as our primary project tracking tool.

**Rationale:**
GitHub Projects provides sufficient functionality for our needs while maintaining integration with our existing development workflow. The team is already familiar with GitHub, reducing onboarding time. Cost savings are significant given our budget constraints.

**Implications:**
- Timeline: 1 week for setup and team training
- Resources: PM will configure boards and create templates
- No impact on other teams
- May need to revisit if reporting needs become more complex

**Action Items:**
- [x] Create project board templates (PM, 2024-01-20)
- [x] Conduct team training session (PM, 2024-01-22)
- [x] Migrate existing backlog items (Team, 2024-01-25)

**Outcome:**
Successfully implemented. Team adoption was smooth. Reporting limitations noted but acceptable for current needs.

**Related Decisions:**
- None

---

## Tips for Effective Decision Logging

1. **Log decisions promptly** while context is fresh
2. **Be concise but complete** — capture enough detail for future reference
3. **Update outcomes** to close the feedback loop
4. **Link related decisions** to maintain decision context over time
5. **Review regularly** in retrospectives to learn from past decisions
