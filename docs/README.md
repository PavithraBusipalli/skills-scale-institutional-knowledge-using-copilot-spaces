# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process library. This folder centralizes guidance for running projects using the OctoAcme methodology and links to the full set of process documents.

## Overview
OctoAcme runs projects with an iterative, customer-first mindset: projects begin with a lightweight initiation (a Project One‑pager that captures problem, goal, success metrics, stakeholders and a high‑level timeline) and move through planning, execution, release, and retrospective gates. Planning translates approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release plan; teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) to visualize flow and enforce ready/DoD checks before work is pulled into an iteration.

Execution emphasizes a predictable team rhythm and disciplined pull-request practices. Teams hold short daily standups (15 minutes), a weekly delivery sync, and end-of-sprint demos. PRs are kept small when possible, include linked issues and acceptance criteria, run CI and security scans before review, and require at least one approval prior to merge. Quality gates (unit/integration tests, smoke tests, and security scanning) plus CI/linting help keep the mainline stable.

Roles and responsibilities are explicit: Product Managers set the vision and success metrics, Project Managers coordinate delivery and communication, Developers implement and test features, and QA validates acceptance and quality. Risks and dependencies are tracked in a Risk Register with escalation paths from team triage up to sponsor involvement. Retrospectives convert learnings into tracked action items to drive continuous improvement.

## Documentation (quick links)
- Getting Started
  - [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- Project Lifecycle
  1. [Initiation Guide](octoacme-project-initiation.md)
  2. [Project Planning](octoacme-project-planning.md)
  3. [Execution & Tracking](octoacme-execution-and-tracking.md)
  4. [Release & Deployment Guide](octoacme-release-and-deployment.md)
  5. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- Cross-functional Guidance
  - [Risk Management & Communication](octoacme-risks-and-communication.md)
  - [OctoAcme Personas (roles & responsibilities)](octoacme-roles-and-personas.md)

## How to navigate (quick answers)
- New to OctoAcme? → Start with the Project Management Overview.
- Starting a new project? → Follow the Initiation Guide and use the Project One-pager template.
- Preparing a release? → See the Release & Deployment Guide and deployment checklist.
- Need to escalate a blocker? → See Risk Management & Communication for escalation paths.
- Wrapping up a sprint or release? → Run a Retrospective and convert action items into issues.

## Additional resources
- Issue template for process doc updates: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
- Keep the Project Charter updated in your project repo.
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context.

## How this README will be used
- Serves as a single entry point for OctoAcme process docs.
- Improves discoverability and onboarding for new team members.
- Links to templates and checklists in each process doc for consistent execution.
