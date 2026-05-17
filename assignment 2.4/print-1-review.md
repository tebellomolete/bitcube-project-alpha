# Sprint 1 Review

**Date:** 2026-05-15
**Sprint Goal:** Implement core booking functionality and basic room discovery to allow users to book and filter rooms by capacity.

## Sprint Goal Outcome

Partially Met

## Completed Stories

| Story # | Outcome                                                                                                  | Acceptance Criteria Met (Yes/No) |
| :------ | :------------------------------------------------------------------------------------------------------- | :------------------------------- |
| 1       | Basic Room Booking successfully implemented with real-time availability checks and dashboard visibility. | Yes                              |
| 3       | Room Capacity Filtering dynamically filters room results based on max capacity input.                    | Yes                              |

## Incomplete Stories

| Story # | Reason                                                                                                                                                                      | Decision (Carry / Split/Drop)                                                                          |
| :------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------- |
| 4       | Lost initial development time to environment setup. The confirmation UI is complete, but backend state-change logic and automated email notification hooks are outstanding. | Split (Carry core state logic and notification hook to Sprint 2; drop email logic from Sprint 1 scope) |

## Stakeholder Feedback

- **Positive feedback:**
  - The core "Search and Book" loop functions seamlessly in real-time.
  - The dynamic room capacity filter updates the UI quickly without page reloads.
- **Concerns or questions:**
  - Will the lack of an immediate cancellation feature cause database congestion if test users make booking mistakes during early trials?
- **Requests or adjustments:**
  - Prioritize finalizing the basic cancellation state change early in Sprint 2 before moving on to larger new features like recurring meetings.
