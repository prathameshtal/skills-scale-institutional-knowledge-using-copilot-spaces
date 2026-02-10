# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This collection of documents serves as your comprehensive guide to how we plan, execute, and deliver projects at OctoAcme. Whether you're onboarding to a new project, looking for a specific process reference, or sharing knowledge with teammates, these docs provide the foundation for consistent, high-quality project delivery.

## Overview

OctoAcme follows a structured, iterative project lifecycle designed to deliver customer value through clear ownership, data-informed decisions, and continuous improvement. Our approach emphasizes customer-first thinking, iterative delivery of small testable increments, and psychological safety that encourages feedback and learning.

The project lifecycle consists of distinct phases: **Initiation** (validating the problem and aligning stakeholders), **Planning** (defining scope, resources, and milestones), **Execution & Tracking** (building, testing, and iterating), **Release & Deployment** (safely delivering to production), **Risk Management & Communication** (proactively managing uncertainties), and **Retrospective & Continuous Improvement** (capturing learnings for future work).

Key roles drive these processes: **Product Managers** own outcomes, prioritize the backlog, and measure success; **Project Managers** coordinate delivery, manage risks and schedules, and facilitate team communications; **Developers** implement features, write tests, and collaborate on design; and **QA/Testing** validates quality and acceptance criteria. Clear ownership ensures accountability while cross-functional collaboration enables teams to deliver effectively.

Communication happens on a regular cadence: daily or twice-weekly standups keep the team aligned, weekly syncs between PM and Product Manager maintain strategic alignment, monthly stakeholder updates ensure transparency, and risk or incident communications address urgent issues as they arise. Quality assurance is built into every phase through layered testing (unit, integration, and end-to-end smoke tests), CI checks (linting, security scans), manual QA validation when needed, comprehensive release checklists, and post-release retrospectives to capture learnings.

## Process Documents

The following guides provide detailed information about each phase and aspect of our project management approach:

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to principles, roles, lifecycle, and communication cadence
- [Project Initiation Guide](octoacme-project-initiation.md) — How to validate, authorize, and kickoff new projects
- [Project Planning](octoacme-project-planning.md) — Defining scope, resources, milestones, and dependencies
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Building, testing, reviewing, and iterating during active development
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identifying, assessing, and communicating risks and dependencies
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized release processes, deployment checklists, and rollback procedures
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and improving team practices
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities for all team members

## How to Use These Docs

**For new team members:** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and approach, then review [Roles & Personas](octoacme-roles-and-personas.md) to understand your role and how you'll interact with others.

**During active projects:** Follow the lifecycle documents in order (Initiation → Planning → Execution → Release → Retrospective) as you progress through each phase. Refer to the Risk Management and Communication guide throughout to maintain transparency and proactively address challenges.

**As a reference:** Keep these docs handy when you need specific templates, checklists, or guidance. Each document includes practical artifacts and decision frameworks you can use directly in your work.

**For institutional knowledge:** Consider adding project-specific documentation to your repository's `.copilot/` directory so that Copilot Spaces can use them as context when assisting with project-related questions and tasks.
