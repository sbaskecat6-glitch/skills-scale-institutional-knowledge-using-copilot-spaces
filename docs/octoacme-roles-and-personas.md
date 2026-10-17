# Roles and Personas — Additions

This section adds proposed personas to clarify ownership and handoffs for cross-functional activities (releases, incidents, compliance, accessibility, privacy).

---

## Release Manager

Summary
- Owns release planning, scheduling, coordination, and verification across teams for planned releases.

Key responsibilities
- Maintain the release calendar and coordinate release windows across teams.
- Run the release readiness checklist and verify all sign-offs are complete.
- Coordinate deployment steps with engineering, QA, and operations.
- Trigger and coordinate release communications and post-release verification.

Interactions / handoffs
- Requests sign-off from QA Owner before release.
- Works with Engineering Lead to confirm build readiness and rollback plans.
- Notifies Stakeholder Liaison and Product Manager of release schedule and outcomes.
- Escalates unresolved release blockers to the Product Manager or Process Steward.

Example scenario
- Coordinates a cross-team release: confirms QA sign-off, schedules deployment window with engineering, and publishes release notes via Stakeholder Liaison.

---

## Project Coordinator

Summary
- Supports project execution by tracking tasks, maintaining meeting notes, and keeping project trackers/cadences up to date.

Key responsibilities
- Maintain project trackers (status, risks, actions) and update owners.
- Prepare and distribute meeting agendas and notes; follow up on action items.
- Assist in schedule updates and resource coordination.

Interactions / handoffs
- Works closely with Product Manager to maintain requirements and timelines.
- Coordinates with Engineering Lead and QA Owner to surface blockers and schedule changes.
- Hands off escalations to Product Manager or Process Steward when process adjustments are required.

Example scenario
- After a sprint planning session, updates the project tracker, assigns action items, and nudges owners for overdue tasks.

---

## Stakeholder Liaison

Summary
- Acts as the single point of contact for external stakeholders and executive reporting to ensure consistent communications and approval flows.

Key responsibilities
- Coordinate stakeholder reviews, demos, and approvals.
- Consolidate stakeholder feedback and route to appropriate role owners.
- Prepare executive summaries and status reports when needed.

Interactions / handoffs
- Coordinates approvals with Product Manager (for scope) and Process Steward (for compliance or process changes).
- Notifies stakeholders about releases and major incidents alongside Release Manager and Incident Commander.

Example scenario
- Collects stakeholder feedback after a demo, prioritizes asks with the Product Manager, and schedules follow-up sessions.

---

## Process Steward

Summary
- Maintains process documentation, owns process versioning and change approvals, and drives continuous improvement initiatives.

Key responsibilities
- Maintain and curate the program process docs, including the Roles & Personas page.
- Propose process improvements, run process reviews, and approve changes in collaboration with role owners.
- Ensure process artifacts are discoverable and up to date.

Interactions / handoffs
- Works with Product Managers, Engineering Leads, QA Owners, and other role owners to validate process changes.
- Coordinates process training and onboarding materials with Project Coordinator or other educators.

Example scenario
- After identifying repeated release failures, leads a review, updates the release checklist, and publishes changes.

---

## Incident Commander

Summary
- Leads incident response for major incidents, coordinates cross-team efforts during incidents, and runs post-incident reviews.

Key responsibilities
- Triage incidents, assign roles during response (communications, mitigation, recovery).
- Ensure stakeholder communications and incident timelines are maintained.
- Lead post-incident review and ensure action items are tracked to closure.

Interactions / handoffs
- Engages Engineering Lead for technical mitigation, QA Owner for verification, and Stakeholder Liaison for external communications.
- Works with Process Steward to update incident response runbooks and retrospectives.

Example scenario
- For a production outage, becomes the central coordinator, assigns mitigation tasks to engineering owners, and later convenes a post-mortem.

---

## Accessibility Advocate

Summary
- Ensures accessibility considerations are included in design, development, and release processes.

Key responsibilities
- Review designs and acceptance criteria for accessibility requirements.
- Provide guidance and automated/manual testing recommendations.
- Sign off on accessibility checks before release when required.

Interactions / handoffs
- Partners with Designers and Engineering to incorporate accessibility into acceptance criteria.
- Coordinates with QA Owner to ensure accessibility tests are executed.
- Escalates major accessibility blockers to Product Manager and Process Steward.

Example scenario
- Reviews a feature's design and flags an accessibility gap; works with engineering to implement and with QA to validate fixes.

---

## Data Privacy Officer (project-level)

Summary
- Reviews project changes for privacy impact, ensures data-handling controls are applied, and coordinates legal/ops reviews when necessary.

Key responsibilities
- Conduct privacy impact checks for features touching personal data.
- Recommend controls, masking, retention policies, and sign-off requirements.
- Coordinate with legal or central privacy teams for compliance needs.

Interactions / handoffs
- Works with Product Manager to review requirements and acceptance criteria.
- Hands off required controls to Engineering Lead and Process Steward to ensure implementation and documentation.

Example scenario
- Evaluates a new data ingestion pipeline for privacy risks, recommends controls, and signs off prior to release.

---

## QA Owner (clarified)

Summary
- Ensures adequate test coverage, validates acceptance criteria, and provides release sign-off from a quality perspective.

Key responsibilities
- Define testing strategy and acceptance criteria for features.
- Own the QA sign-off checklist and coordinate regression testing.
- Validate post-release verification steps.

Interactions / handoffs
- Provides sign-off to Release Manager for releases.
- Works with Engineering Lead to prioritize test coverage and with Incident Commander for verification during incidents.

Example scenario
- Runs pre-release regression tests and certifies the release is ready; if blockers are found, notifies Release Manager and Product Manager.

---

# Suggested documentation structure for each persona

For each persona added to docs/octoacme-roles-and-personas.md, include:
1) Persona name
2) Summary (1–2 sentences)
3) Key responsibilities (bulleted list)
4) Interactions / handoffs (roles and expected interaction)
5) Example scenarios (optional)

---

*End of additions.*
