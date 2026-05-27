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

#### Key Interactions
- **With Product Managers**: Discuss acceptance criteria, trade-offs, and feature specifications
- **With Project Managers**: Report progress, blockers, and dependencies
- **With DevOps Engineers**: Collaborate on deployment readiness and CI/CD pipeline requirements
- **With QA/Testing**: Work together on test strategy and acceptance criteria validation
- **With Security Specialists**: Review security requirements and participate in threat assessments

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Own the acceptance criteria and feature specifications

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **With Project Managers**: Align on timelines, dependencies, and risk mitigation
- **With Developers**: Define requirements, review technical solutions, and discuss feasibility
- **With Data Analysts**: Review metrics, success indicators, and data-driven insights
- **With UX Designers**: Collaborate on user research findings and design validation
- **With Customer Support Lead**: Gather customer feedback and define support readiness requirements

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
- Track progress against milestones and escalate blockers

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **With Product Managers**: Align on priorities, scope changes, and stakeholder expectations
- **With Developers**: Track progress, manage dependencies, and unblock technical issues
- **With DevOps Engineers**: Coordinate deployment windows and release readiness
- **With Security Specialists**: Schedule security reviews and manage compliance risks
- **With Customer Support Lead**: Plan for launch support and communication timelines

---

## Specialized/Supporting Roles

### UX Designer

#### Role Summary
UX Designers own the user experience definition, creating intuitive interfaces and gathering usability feedback. They translate product strategy and customer needs into actionable design solutions.

#### Responsibilities
- Conduct user research and translate insights into design requirements
- Create wireframes, prototypes, and design specifications
- Facilitate usability testing and incorporate feedback
- Ensure consistency with design system and accessibility standards
- Collaborate with developers on implementation details
- Iterate on designs based on user feedback and analytics

#### Goals
- Deliver intuitive, accessible products that delight users
- Reduce support burden through clear, usable interfaces
- Support product adoption and customer satisfaction metrics

#### Typical Communication
- Design reviews with Product Managers and Developers
- User research findings and usability test results
- Design system documentation and accessibility guidelines

#### Key Interactions
- **With Product Managers**: Validate problem statements and define design requirements
- **With Developers**: Review implementation against design specs and provide design guidance
- **With Data Analysts**: Analyze user behavior metrics and A/B test results
- **With Customer Support Lead**: Understand user pain points and support tickets
- **With QA/Testing**: Define acceptance criteria for design quality and usability

---

### DevOps Engineer

#### Role Summary
DevOps Engineers own the CI/CD infrastructure, deployment automation, and operational excellence. They enable the team to release reliably and maintain system health.

#### Responsibilities
- Design and maintain CI/CD pipelines and infrastructure
- Automate deployment processes and reduce manual toil
- Establish monitoring, logging, and alerting for production systems
- Manage infrastructure scaling and performance optimization
- Lead incident response and post-mortems for operational failures
- Document runbooks and operational procedures

#### Goals
- Enable fast, reliable releases with minimal manual effort
- Maintain high system availability and performance
- Reduce deployment risk through automation and testing

#### Typical Communication
- Deployment status and release notes
- Infrastructure and monitoring dashboards
- Incident reports and post-mortem findings

#### Key Interactions
- **With Developers**: Advise on deployable artifacts, monitoring instrumentation, and operational requirements
- **With Project Managers**: Coordinate deployment windows and manage operational risks
- **With QA/Testing**: Provide staging environments and smoke test infrastructure
- **With Security Specialists**: Implement security controls and manage credential/secret management
- **With Data Analysts**: Provide infrastructure metrics and cost analysis

---

### Data Analyst

#### Role Summary
Data Analysts develop dashboards, track product metrics, and provide insights to drive decision-making. They transform raw data into actionable intelligence for the team.

#### Responsibilities
- Define success metrics and key performance indicators (KPIs)
- Develop dashboards and reports for stakeholders
- Conduct data analysis and identify trends
- Support A/B testing and experimentation
- Provide insights during planning, execution, and retrospectives
- Help Product Managers and leadership make data-driven decisions

#### Goals
- Enable data-driven decision-making across the organization
- Identify opportunities for product and operational improvements
- Ensure transparency on project outcomes and impact

#### Typical Communication
- Weekly/monthly dashboards and metric reports
- Ad-hoc data analysis and insights
- Retrospective presentations and learnings

#### Key Interactions
- **With Product Managers**: Share success metric progress and user behavior insights
- **With Project Managers**: Provide project health metrics and forecasting data
- **With Developers**: Explain instrumentation needs and provide performance analytics
- **With UX Designers**: Analyze user behavior and A/B test results
- **With Customer Support Lead**: Share customer satisfaction and issue trend data

---

### Security Specialist

#### Role Summary
Security Specialists review architecture, conduct risk assessments, and lead security incident response. They advise teams on security controls and ensure compliance throughout the project lifecycle.

#### Responsibilities
- Conduct threat assessments and architecture reviews
- Define security requirements and controls
- Review code and dependencies for vulnerabilities
- Lead security incident response and post-incident analysis
- Maintain security compliance and policy adherence
- Advise teams on secure development practices

#### Goals
- Prevent security breaches and protect customer data
- Embed security into development from day one
- Maintain compliance with regulatory and organizational standards

#### Typical Communication
- Security reviews and threat assessments
- Vulnerability reports and remediation plans
- Incident response notifications and post-mortems

#### Key Interactions
- **With Developers**: Review code, provide secure coding guidance, and assess technical designs
- **With Product Managers**: Define security requirements based on risk and compliance needs
- **With DevOps Engineers**: Advise on infrastructure security and secret management
- **With Project Managers**: Communicate security risks and mitigation timelines
- **With QA/Testing**: Define security test coverage and penetration testing schedules

---

### Customer Support Lead

#### Role Summary
Customer Support Leads ensure support readiness for releases, document help content, and channel customer feedback back to the team. They bridge the gap between customers and the product team.

#### Responsibilities
- Develop support documentation, FAQs, and help content
- Train support team on new features and capabilities
- Prepare for release launches with support readiness plans
- Gather and prioritize customer feedback for the product team
- Monitor support tickets for recurring issues and escalations
- Plan for post-launch support and customer communication

#### Goals
- Ensure seamless customer adoption and satisfaction
- Reduce support ticket volume through clear documentation
- Provide early warning on product issues and customer needs

#### Typical Communication
- Support readiness plans and launch coordination
- Help documentation and FAQ updates
- Customer feedback summaries and trend reports

#### Key Interactions
- **With Product Managers**: Share customer pain points and feedback on feature priorities
- **With Developers**: Understand feature details and gather implementation context
- **With UX Designers**: Provide customer usability feedback and help documentation guidance
- **With Project Managers**: Coordinate launch timelines and support readiness milestones
- **With Data Analysts**: Share support metrics, ticket trends, and customer satisfaction data

---

## How These Personas Are Used in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to key interactions to understand cross-functional dependencies and communication patterns.
- Use the responsibilities and goals to define success criteria for each role's contributions.
