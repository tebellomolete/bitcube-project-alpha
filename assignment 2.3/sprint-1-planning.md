# Sprint 1 Planning Session

**Date:** 2026-05-11
**Sprint Goal:** Implement core booking functionality and basic room discovery to allow users to book and filter rooms by capacity.

## Attendees
- **Product Owner:** Tebello Molete
- **Scrum Master:** Skye (Tutor)
- **Development Team:** Tebello Molete

## Velocity Target
**Target Velocity:** 7 Story Points
*Rationale: As this is the first sprint in the Bitcube environment, velocity is set conservatively to account for environment setup and initial API integration.*

## Selected User Stories
| Story # | Title | Story Points | Priority |
| :--- | :--- | :--- | :--- |
| 1 | Basic Room Booking | 3 | High |
| 3 | Room Capacity Filtering | 2 | High |
| 4 | Booking Cancellation | 2 | High |

**Total Points:** 7

## Dependencies
- Successful connection to the PostgreSQL database via the PERN stack.
- Baseline API routes for Room entities must be established before Story #3 can be completed.

## Risks
| Risk | Probability | Impact | Mitigation |
| :--- | :--- | :--- | :--- |
| Database Connection Issues | Medium | High | Early spike on DB configuration and Sequelize/PostgreSQL logs. |
| Scope Creep on Calendar UI | High | Medium | Stick to a basic grid view; avoid complex drag-and-drop until Sprint 2. |
| Logic Errors in Availability | Medium | High | Implement unit tests specifically for time-slot overlap logic. |

## Standup Cadence
**Time:** 09:00 AM Daily
**Format:** Yesterday / Today / Blockers