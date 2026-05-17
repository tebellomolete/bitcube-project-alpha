# Sprint 1 Retrospective

**Date:** 2026-05-15
**Participants:** Tebello Molete (Product Owner / Developer), Skye (Scrum Master / Tutor)

## Start

- **Environment Spikes:** Dedicate the first few hours of a new development cycle or tool adoption to environment smoke testing before active sprint tasks begin.
- **Incremental Database Schema Mapping:** Fully map database schema state changes (such as tracking 'Cancelled' statuses) during the design phase of a story rather than during implementation.
- **Automated Testing Hooks:** Set up testing harnesses for background tasks (like email dispatch triggers) early in the development stack setup.

## Stop

- **Over-committing without buffer:** Stop scheduling a full velocity load (7 story points) in an initial sprint when adapting to a brand-new training environment template.
- **Delayed DB validation:** Stop writing frontend components before validating that the database schema natively supports all states required by the user story's acceptance criteria.

## Continue

- **Scope control and triage:** Maintain the daily practice of aggressively triaging complex UI elements (sticking to the basic grid view and avoiding premature drag-and-drop mechanics).
- **Daily Standup Discipline:** Keep up the consistent morning cadence to surface blockers early, ensuring team alignment even as a solo developer.
- **Focusing on the 'Happy Path':** Continue prioritizing foundational loops (successful bookings and filtering) when a sprint is flagged "At Risk".

## Action Items

| Action                                                                                                 | Owner          | When            |
| :----------------------------------------------------------------------------------------------------- | :------------- | :-------------- |
| Refactor DB booking schema to include a `status` column supporting an explicit 'Cancelled' state       | Tebello Molete | Sprint 2, Day 1 |
| Build out backend API state change route and manual integration testing for cancellation functionality | Tebello Molete | Sprint 2, Day 2 |
| Coordinate with Skye to verify local mail loop configurations for future automated notifications       | Tebello Molete | Sprint 2, Day 3 |
