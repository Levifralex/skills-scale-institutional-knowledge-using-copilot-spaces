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

## Tech Lead

### Role Summary
Technical owner for the feature or component; guides design and architecture decisions. Ensures technical quality, mentors developers, and coordinates with platform/infrastructure teams.

### Responsibilities
- Drive technical design and architecture decisions for the feature or component
- Review high-risk, complex, or cross-cutting pull requests and design proposals
- Mentor and guide developers on the team; support skill development
- Make tradeoff recommendations balancing delivery timelines and technical debt
- Coordinate with Platform/DevOps/Infrastructure teams on infrastructure and operational needs
- Identify and escalate technical risks and blocker resolutions

### Goals
- Ensure technical excellence and maintainability of delivered code
- Reduce technical debt while maintaining velocity
- Support team capability growth and decision-making confidence

### Typical Communication
- Code reviews and design discussions (Slack, PR comments, design docs)
- Technical sync with Developers and Architects
- Escalations to Engineering Manager on blockers or capacity constraints

### Key Interactions
- Works closely with Developers, Product Manager, Product Lead, and QA
- Escalates technical blockers, resourcing, or timeline concerns to the Engineering Manager
- Coordinates with Release/Platform Engineer on deployment and infrastructure concerns

---

## Engineering Manager

### Role Summary
People and delivery-focused manager for the engineering team. Owns staffing, capacity, career growth, and process improvements. Removes blockers to team execution.

### Responsibilities
- Own staffing, capacity planning, and team structure decisions
- Support career growth, performance feedback, and development conversations
- Resolve cross-team resource conflicts and unblock delivery constraints
- Advocate for engineering health, process improvements, and team wellbeing
- Participate in prioritization discussions balancing team capacity and product needs
- Support onboarding and knowledge transfer within the team

### Goals
- Build a healthy, high-performing, and engaged engineering team
- Enable consistent, predictable delivery while protecting team sustainability
- Create an environment of psychological safety and continuous learning

### Typical Communication
- One-on-ones with team members (bi-weekly or weekly)
- Capacity and resource planning with Product Manager and Product Lead
- Team retrospectives and process improvement discussions

### Key Interactions
- Partners with Product Manager on resourcing constraints and delivery risk
- Collaborates with Product Lead on prioritization tradeoffs affecting team capacity
- Works with Tech Leads on technical tradeoffs and team execution
- Supports career conversations and mentorship across the team

---

## UX Designer

### Role Summary
Represents user needs and designs usable experiences. Conducts research, creates prototypes, validates accessibility, and ensures user-centric decision-making throughout the project lifecycle.

### Responsibilities
- Conduct user research, usability testing, and gather user feedback
- Create prototypes, wireframes, mockups, and design assets
- Validate designs for usability, accessibility (WCAG compliance), and consistency
- Provide clear design handoffs to Developers with specifications and rationale
- Review implemented features for fidelity to design intent
- Advocate for user needs and usability in prioritization and scope decisions

### Goals
- Deliver intuitive, accessible experiences that delight users
- Reduce user errors and support burden through thoughtful design
- Ensure design decisions are grounded in user feedback and research

### Typical Communication
- Design reviews and feedback sessions (Figma, design docs, user testing sessions)
- Collaboration with Product Lead and Product Manager on requirements and acceptance criteria
- Walkthroughs and feedback sessions with Developers during implementation

### Key Interactions
- Collaborates with Product Lead/Manager to shape requirements and acceptance criteria
- Works with Developers and QA to ensure user-facing behavior matches design intent
- Partners with Data Analyst to instrument and measure design effectiveness

---

## Release / Platform Engineer

### Role Summary
Maintains deployment pipelines, production reliability, and operational infrastructure. Ensures safe, repeatable, observable deployments and supports team self-service of infrastructure needs.

### Responsibilities
- Design and maintain CI/CD pipelines and release orchestration
- Implement and manage rollout strategies, canary deployments, and rollback procedures
- Define and maintain observability: dashboards, alerts, logging, and tracing
- Create and maintain runbooks, playbooks, and disaster recovery procedures
- Support infrastructure changes needed by development teams
- Coordinate on platform changes that affect multiple teams or services

### Goals
- Enable safe, repeatable, fast deployments with high confidence
- Maintain high production availability and quick incident response
- Reduce operational overhead through automation and clear procedures

### Typical Communication
- Release planning and coordination (Slack channels, release notes, deployment windows)
- Incident response and postmortems
- Technical documentation and runbook maintenance

### Key Interactions
- Works with Product Manager and Release Manager on release scheduling and risk
- Supports Developers and QA with deployment troubleshooting and pipeline improvements
- Coordinates with Security/Compliance Owner on infrastructure security reviews

---

## Support / Customer Success Representative

### Role Summary
Voice of customers and post-release support lead. Captures customer impact, triages incidents, and feeds feedback into prioritization and product decisions.

### Responsibilities
- Capture customer impact and run triage for customer-reported issues
- Feed qualitative customer feedback and bug reports to Product Lead and Product Manager
- Provide input on prioritization based on customer impact and business criticality
- Coordinate customer-facing communications for incidents and releases
- Support troubleshooting and escalations for customer-reported issues
- Maintain post-incident communication and resolution tracking

### Goals
- Minimize customer impact and resolve issues quickly
- Bridge customer voice into product decisions and prioritization
- Maintain trust and transparency with customers during incidents

### Typical Communication
- Slack channels for customer escalations and incident response
- Weekly or on-demand feedback sessions with Product Lead and Product Manager
- Customer communications and status updates during incidents

### Key Interactions
- Coordinates with Product Lead, Product Manager, and Engineering for fixes and priorities
- Owns stakeholder communication for customer-facing incidents and follow-ups
- Works with Release/Platform Engineer on incident severity and rollback decisions

---

## Security / Compliance Owner

### Role Summary
Ensures security and compliance requirements are met across all changes. Performs threat modeling, validates compliance, and approves security-critical or sensitive releases.

### Responsibilities
- Perform threat modeling and security reviews for architecture and design decisions
- Specify compliance checks and required approvals for sensitive or high-risk changes
- Validate that releases meet security and regulatory standards before sign-off
- Review code and infrastructure changes for security best practices
- Maintain security runbooks and incident response procedures
- Support security incident investigation and remediation

### Goals
- Prevent security vulnerabilities and compliance violations
- Enable secure, compliant delivery while minimizing friction
- Support incident response and forensics when needed

### Typical Communication
- Security reviews and threat modeling sessions (design docs, PR comments)
- Compliance and policy discussions with Product Lead and Legal
- Security incident response and postmortems

### Key Interactions
- Reviews designs and code with Developers and Tech Leads
- Escalates compliance or policy issues to Product Lead or Legal when necessary
- Coordinates with Release/Platform Engineer on infrastructure security
- Participates in security incident response with Support and Release teams

---

## Data Analyst

### Role Summary
Defines measurement and analytics needed to evaluate success. Instruments telemetry, creates dashboards, and provides data-driven insights to guide product decisions.

### Responsibilities
- Define success metrics and key performance indicators (KPIs) aligned with project goals
- Design instrumentation and telemetry events needed to measure success
- Create and maintain dashboards and reporting for stakeholder visibility
- Validate data quality and correctness of metrics
- Perform post-release analysis and impact assessment
- Provide data-driven recommendations to Product Lead and Product Manager

### Goals
- Enable data-driven decision-making across the organization
- Measure and demonstrate product impact and customer value
- Reduce guesswork and enable fast iteration based on evidence

### Typical Communication
- Metrics and instrumentation planning (design docs, data specs)
- Weekly or milestone-based reporting and insight sharing
- Post-release analysis and impact reviews

### Key Interactions
- Partners with Product Lead/Manager to define success metrics and experiments
- Works with Developers to implement telemetry and ensure data capture
- Collaborates with UX Designer to measure design effectiveness
- Provides insights to Support team on customer behavior and usage patterns

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- In planning and execution, refer to these personas to ensure all critical perspectives are represented in decisions.
- Use the responsibilities and interactions to understand handoffs and dependencies in your project workflows.

---

## Integration with Project Lifecycle

These personas work together across the OctoAcme project lifecycle:
- **Initiation**: Product Manager and Project Manager define the opportunity; Tech Lead and Engineering Manager provide resource and technical feasibility input
- **Planning**: Product Manager, Tech Lead, UX Designer, and Data Analyst collaborate on requirements; Project Manager and Engineering Manager finalize timeline and resources
- **Execution**: Developers, Tech Lead, UX Designer, QA, and Data Analyst work daily; Project Manager tracks progress; Security/Compliance reviews high-risk changes
- **Release**: Release/Platform Engineer, Product Manager, and Support/Customer Success coordinate; Security Owner approves; Data Analyst prepares success measurement
- **Retrospective**: Project Manager, Product Manager, Tech Lead, and Engineering Manager review outcomes; all personas contribute learnings for continuous improvement