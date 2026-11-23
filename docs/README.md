# OctoAcme Project Management Docs

## Purpose

This README is the entry point to OctoAcme's project management process documentation. Use these documents to understand how projects move from an approved idea to a tested release and a continuous improvement cycle.

## Project management process overview

OctoAcme follows a lightweight, iterative project lifecycle. **Initiation** validates the business need, measurable success criteria, stakeholders, timeline, risks, and resource needs in a Project One-pager. **Planning** converts approved work into a prioritized backlog with estimates, owners, acceptance criteria, dependencies, a Definition of Done, milestones, and a release plan.

During **Execution and Tracking**, delivery teams use a project board, daily standups, weekly delivery syncs, demos or reviews, and project metrics to keep work visible and manageable. Pull requests are kept small where practical, linked to issues and acceptance criteria, and reviewed through CI and team approval before merge. PM and Product Lead ownership remains distinct: the **Project Manager** coordinates delivery, schedules, risks, dependencies, and communications, while the **Product Manager** defines outcomes, prioritizes the backlog, and measures success. Developers implement and test features, QA validates quality and acceptance, and stakeholders provide input and approvals.

Communication is based on consistent, visible artifacts and escalation. Teams maintain plans, risk registers, status updates, and decision logs, using a project README or release document as the source of truth. Risks are assessed by impact and likelihood, assigned owners, mitigated, and reviewed in weekly syncs. Blockers are escalated from team triage to the Project Manager, Product Lead or dependent teams, and the Sponsor when business impact warrants it. Security incidents and other critical events follow dedicated incident and on-call paths.

Quality is built into each stage rather than left until release. The process uses unit, integration, smoke, security, and manual acceptance testing as appropriate; CI runs tests, linting, and security scans; and dashboards track progress and operational signals. Before deployment, teams confirm acceptance criteria, passing checks, release notes, rollback plans, and smoke tests. After release, retrospectives capture what went well and what can improve, with action items assigned owners and due dates and reviewed until closure.

## Process documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risk Management and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
