# OctoAcme — Communication Plan Template

## Purpose
Define how project information flows to stakeholders, ensuring timely, relevant, and appropriate communication throughout the project lifecycle.

## Project Information

**Project Name:**

**Project Manager:**

**Communication Plan Owner:**

**Last Updated:**

---

## Stakeholder Communication Matrix

| Stakeholder/Group | Role/Interest | Communication Type | Frequency | Channel/Method | Owner | Notes |
|-------------------|---------------|-------------------|-----------|----------------|-------|-------|
| Executive Sponsor | Decision authority | Status summary | Monthly | Email report | PM | Focus on ROI and risks |
| Product Manager | Product direction | Detailed status | Weekly | Sync meeting | PM | Include backlog health |
| Development Team | Implementation | Daily updates | Daily | Standup | Scrum Master | Blockers and progress |
| UX Designer | Design validation | Design reviews | Bi-weekly | Design critique | UX Lead | Include user feedback |
| Data Analyst | Metrics tracking | KPI dashboard | Weekly | Dashboard + sync | Data Analyst | Automated where possible |
| Technical Writer | Documentation | Content reviews | As needed | PR reviews | Tech Writer | Tag on doc changes |
| Release Manager | Release coordination | Deployment status | Per release | Release meeting | Release Manager | Include rollback plans |
| End Users | Product usage | Release notes | Per release | Email/in-app | PM + Tech Writer | User-friendly language |
| Support Team | Issue resolution | Impact briefing | Pre-release | Email + Q&A | PM | Include known issues |

---

## Communication Types & Templates

### Status Update (Weekly)
**Audience:** Project stakeholders
**Format:** Email or shared document
**Content:**
- Accomplishments this week
- Planned work for next week
- Risks and blockers
- Metrics snapshot
- Decisions needed

### Stakeholder Report (Monthly)
**Audience:** Executive sponsors and senior leadership
**Format:** Executive summary (1-page)
**Content:**
- Project health (on track / at risk / off track)
- Key milestones achieved and upcoming
- Budget and resource status
- Top 3 risks and mitigations
- Key decisions or escalations needed

### Release Communication
**Audience:** End users and stakeholders
**Format:** Release notes and announcement
**Content:**
- What's new or changed
- Benefits to users
- Migration steps (if applicable)
- Known issues and workarounds
- Support contact information

### Incident Communication
**Audience:** Affected stakeholders and leadership
**Format:** Incident update (during) and post-mortem (after)
**Content:**
- Impact and affected systems
- Current status and estimated resolution
- Workarounds available
- Root cause and action items (post-mortem)

---

## Meeting Cadence

### Regular Meetings

| Meeting | Purpose | Attendees | Frequency | Duration | Owner |
|---------|---------|-----------|-----------|----------|-------|
| Daily Standup | Sync on progress and blockers | Development team, Scrum Master | Daily | 15 min | Scrum Master |
| Sprint Planning | Plan iteration work | Team, PM, PO | Start of sprint | 2 hours | Scrum Master |
| Sprint Review/Demo | Show completed work | Team, stakeholders | End of sprint | 1 hour | PM/Scrum Master |
| Retrospective | Continuous improvement | Team | End of sprint | 1 hour | Scrum Master |
| Weekly PM Sync | Align on status and risks | PM, Tech Lead, PO | Weekly | 30 min | PM |
| Stakeholder Sync | Update key stakeholders | PM, stakeholders | Bi-weekly | 30 min | PM |
| Release Planning | Plan upcoming releases | PM, Release Manager, Tech Lead | Monthly | 1 hour | Release Manager |

### Ad-Hoc Meetings

- **Design Reviews:** As needed when new designs are ready
- **Technical Spike Reviews:** When exploring new approaches
- **Incident Response:** Immediate when incidents occur
- **Decision Meetings:** When key decisions require discussion

---

## Communication Channels

### Primary Channels

**Slack/Teams Channels:**
- `#project-[name]` — General project discussion
- `#project-[name]-dev` — Development team coordination
- `#project-[name]-alerts` — Automated notifications and alerts

**Email Lists:**
- `project-[name]-team@company.com` — Core team
- `project-[name]-stakeholders@company.com` — Broader stakeholder group

**Documentation:**
- GitHub repository: `/docs` folder for all project documentation
- Project board: GitHub Projects for backlog and progress tracking
- Decision log: Track significant decisions in `decision-log.md`

**Dashboards:**
- Project metrics dashboard (link)
- CI/CD pipeline status (link)
- User analytics (link)

---

## Escalation Path

### Level 1: Team Level
- **Issue:** Day-to-day blockers and technical issues
- **Escalated to:** Scrum Master or Tech Lead
- **Response time:** Same day

### Level 2: Project Management
- **Issue:** Cross-team dependencies, resource constraints
- **Escalated to:** Project Manager or Product Manager
- **Response time:** 1-2 business days

### Level 3: Leadership
- **Issue:** Business-impacting issues, major scope changes
- **Escalated to:** Executive Sponsor or Department Lead
- **Response time:** 2-3 business days

### Critical/Emergency
- **Issue:** Production outages, security incidents
- **Escalated to:** On-call engineer and Release Manager (immediate), then Leadership
- **Response time:** Immediate

---

## Communication Principles

1. **Be Transparent:** Share both good news and challenges openly
2. **Be Timely:** Communicate issues as soon as they're known
3. **Be Concise:** Respect stakeholder time with focused updates
4. **Be Consistent:** Maintain regular cadence to build trust
5. **Tailor the Message:** Adjust content and detail level for audience
6. **Two-Way Communication:** Encourage feedback and questions
7. **Document Decisions:** Capture important decisions for future reference

---

## Success Metrics

- Stakeholder satisfaction with communication (survey)
- Meeting attendance and engagement
- Time to resolve blockers
- Number of surprises or misalignments (aim to minimize)
- Action item completion rate from meetings
