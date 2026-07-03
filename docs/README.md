# OctoAcme Project Management Docs

This README serves as the central entry point for OctoAcme's project management documentation. Start here to understand the overall process framework and navigate to each supporting document.

## Summary

OctoAcme follows a structured, lifecycle-based approach to project management that spans five phases: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART objectives, success metrics, and stakeholder alignment. Work only advances to planning once success criteria are clear, stakeholders agree on priority, and team availability is confirmed. This deliberate gate-keeping ensures resources are never committed to poorly defined initiatives.

Three core **roles** drive delivery: the **Project Manager (PM)**, who owns coordination, scheduling, risk, and communications; the **Product Manager (PdM)**, who defines outcomes and prioritizes the backlog; and **Developers**, who implement, test, and review work. QA validates acceptance criteria, while Stakeholders provide inputs and approvals. During planning, teams break work into shippable increments with explicit acceptance criteria, T-shirt or story-point estimates, and a documented Definition of Done. A Risk Register — tracking ID, impact, likelihood, owner, and mitigation — is maintained continuously from planning through release.

**Communication** is structured and role-appropriate: daily standups (15 min) surface blockers, weekly delivery syncs track progress and risks, and monthly stakeholder updates maintain executive alignment. A three-level **escalation path** (Team → PM → Product Lead → Sponsor) ensures issues are resolved at the lowest appropriate level. During execution, teams use a GitHub Projects board with columns from *Backlog* through *Done*, keep pull requests small (≤ 400 lines), and require CI passing plus at least one approval before merging.

**Quality and continuous improvement** are built into every phase. CI pipelines enforce automated tests, linting, and security scanning. Releases require passing smoke tests, drafted release notes, and a documented rollback plan before production deployment. After each sprint, release, or incident, a timeboxed **retrospective** captures what went well, what to improve, and 2–3 prioritized action items with clear owners and due dates. Those action items feed back into the project backlog, closing the loop and embedding a culture of iterative, evidence-based improvement across the team.

## Documents

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)
- [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)
- [OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](octoacme-roles-and-personas.md)
