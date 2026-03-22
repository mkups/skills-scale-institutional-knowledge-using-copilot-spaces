# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers core positions as well as supporting roles that are essential to cross-functional delivery: Project Manager, Product Manager, Developer, Scrum Master, UX Designer, QA Lead, Release Manager, Customer Success Manager, and Stakeholder.

For a summary of how these roles interact, see the [Cross-Functional Interaction Matrix](#cross-functional-interaction-matrix) and [Role Involvement by Project Phase](#role-involvement-by-project-phase) sections at the end of this document.

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

## Scrum Master

### Role Summary
The Scrum Master serves as a servant-leader and Agile coach for the delivery team. They facilitate Agile ceremonies, remove impediments, and ensure the team can operate at a sustainable, predictable pace.

### Responsibilities
- Facilitate Agile ceremonies: sprint planning, daily standups, sprint reviews, and retrospectives
- Remove blockers and escalate impediments that cannot be resolved at the team level
- Coach the team on Agile principles and continuous improvement practices
- Shield the team from unplanned work and scope creep during a sprint
- Bridge communication gaps between the delivery team and stakeholders

### Goals
- Enable high team velocity and predictability
- Foster a culture of continuous improvement and psychological safety
- Ensure Agile practices are understood and consistently applied

### Typical Communication
- Daily standups and retrospective facilitation
- Impediment logs and escalation notes to PM
- Coaching conversations with individual team members

### Key Interactions
- **Project Manager:** Coordinates on schedule risk, escalations, and cross-team dependencies
- **Product Manager:** Aligns on backlog readiness and sprint goals
- **Developers:** Removes day-to-day impediments and supports team health
- **Stakeholders:** Manages expectations around scope and velocity during a sprint

---

## UX Designer

### Role Summary
UX Designers are responsible for the end-to-end user experience of the product. They translate user needs and business requirements into intuitive, accessible, and visually coherent designs that developers can implement.

### Responsibilities
- Conduct user research, interviews, and usability testing to surface insights
- Create wireframes, prototypes, and high-fidelity design assets
- Define and uphold usability and accessibility standards (e.g., WCAG compliance)
- Collaborate with Product Managers to translate requirements into design solutions
- Work closely with Developers during implementation to ensure design fidelity
- Iterate designs based on feedback from QA and user testing

### Goals
- Deliver intuitive, accessible experiences that delight users
- Reduce friction and support errors through thoughtful design
- Ensure design consistency across the product

### Typical Communication
- Design reviews and prototype walkthroughs with PM and Developers
- Usability test reports and user research summaries
- Annotated design files shared via design tooling (e.g., Figma)

### Key Interactions
- **Product Manager:** Aligns on user goals, acceptance criteria, and feature scope
- **Developers:** Hands off designs and answers implementation questions
- **QA Lead:** Validates that implemented UI matches approved designs and accessibility standards
- **Stakeholders:** Presents design rationale and gathers feedback during reviews

---

## QA Lead

### Role Summary
The QA Lead owns the overall quality strategy for the project. They ensure that features meet acceptance criteria, defects are caught early, and releases are stable before reaching production.

### Responsibilities
- Define the test strategy, including the split between manual and automated testing
- Develop and maintain test plans, test cases, and regression suites
- Coordinate test execution across the team and manage test environments
- Track defect lifecycles, ensure timely resolution, and report quality metrics
- Collaborate with Developers on testability and shift-left testing practices
- Validate that accessibility and performance requirements are met

### Goals
- Achieve high confidence in release quality before each deployment
- Reduce escaped defects reaching production
- Improve test coverage and automation over time

### Typical Communication
- Test plan reviews with PM and Developers at sprint start
- Bug reports, test results, and quality dashboards updated continuously
- Go/no-go input during release readiness reviews with Release Manager and PM

### Key Interactions
- **Developers:** Collaborates on testability, reviews acceptance criteria, and triages defects
- **Product Manager:** Aligns on acceptance criteria and definition of done
- **Release Manager:** Provides release readiness sign-off based on test results
- **UX Designer:** Validates UI implementations against design specs and accessibility standards

---

## Release Manager

### Role Summary
The Release Manager oversees the end-to-end release process. They coordinate across engineering, QA, and operations to ensure that software is deployed safely, reliably, and on schedule.

### Responsibilities
- Own the release plan, including staging, production deployment windows, and communication timelines
- Coordinate release readiness reviews with QA Lead and PM before each deployment
- Ensure rollback and mitigation plans are defined and tested for every release
- Manage release notes, change logs, and stakeholder communications around deployments
- Track post-release health metrics and coordinate hotfix processes when needed
- Maintain and improve the deployment runbook

### Goals
- Achieve zero-surprise releases with predictable schedules and clear communication
- Minimize production incidents through rigorous pre-release validation
- Reduce mean time to recovery (MTTR) when issues do occur

### Typical Communication
- Release readiness meetings with QA Lead, PM, and engineering leads
- Release announcements and change logs distributed to stakeholders
- Incident reports and post-mortems when deployments encounter issues

### Key Interactions
- **QA Lead:** Relies on test sign-off as a gate for release readiness
- **Project Manager:** Aligns on release windows, milestone dates, and stakeholder communications
- **Developers:** Coordinates deployment steps, environment configurations, and hotfix logistics
- **Customer Success Manager:** Coordinates customer-facing communications around major releases

---

## Customer Success Manager (CSM)

### Role Summary
The Customer Success Manager acts as the voice of the customer within the product team. They ensure that the product delivers ongoing value to customers and that feedback from the field is surfaced to influence prioritization and improvements.

### Responsibilities
- Advocate for customer needs and represent user feedback in product planning discussions
- Collect, synthesize, and communicate usage data, support trends, and customer satisfaction metrics
- Coordinate with Product Manager to ensure high-impact customer pain points are prioritized
- Manage customer communications around new features, changes, and known issues
- Support onboarding and adoption efforts for new releases
- Escalate at-risk accounts and track resolution of customer-impacting issues

### Goals
- Drive high customer satisfaction (CSAT) and retention
- Reduce support escalations by ensuring quality releases and clear communications
- Build a feedback loop between customers and the product team

### Typical Communication
- Regular syncs with Product Manager on customer feedback themes and priorities
- Customer-facing release notes, FAQs, and onboarding materials
- Escalation alerts and health dashboards shared with PM and leadership

### Key Interactions
- **Product Manager:** Primary collaborator on roadmap priorities driven by customer feedback
- **Release Manager:** Coordinates customer-facing communications for each release
- **Project Manager:** Flags customer-impacting risks and dependencies
- **QA Lead:** Reports customer-reported defects and usage edge cases for test coverage

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Cross-Functional Interaction Matrix

The table below summarizes the primary collaboration points between roles. An **X** indicates a strong, regular interaction; an **(x)** indicates a context-dependent or occasional interaction.

| | Project Manager | Product Manager | Developer | Scrum Master | UX Designer | QA Lead | Release Manager | CSM |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Project Manager** | — | X | X | X | (x) | X | X | (x) |
| **Product Manager** | X | — | X | X | X | X | (x) | X |
| **Developer** | X | X | — | X | X | X | X | — |
| **Scrum Master** | X | X | X | — | (x) | (x) | (x) | — |
| **UX Designer** | (x) | X | X | (x) | — | X | — | (x) |
| **QA Lead** | X | X | X | (x) | X | — | X | (x) |
| **Release Manager** | X | (x) | X | (x) | — | X | — | X |
| **CSM** | (x) | X | — | — | (x) | (x) | X | — |

---

## Role Involvement by Project Phase

The following table shows when each role is typically most active during the project lifecycle.

| Phase | Roles Most Active |
|---|---|
| **1. Initiation** | Project Manager, Product Manager, Stakeholders, CSM |
| **2. Planning** | Project Manager, Product Manager, Scrum Master, UX Designer, QA Lead, Release Manager |
| **3. Execution** | Developers, Scrum Master, UX Designer, QA Lead, Product Manager |
| **4. Release** | Release Manager, QA Lead, Project Manager, CSM, Developers |
| **5. Close & Retrospective** | All roles — PM, PdM, Developers, Scrum Master, QA Lead, Release Manager, UX Designer, CSM |

