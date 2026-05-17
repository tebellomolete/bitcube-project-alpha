# Sprint 1 Summary

### Executive Summary

Sprint 1 successfully delivered the core engine of the Conference Room Booking System by operationalizing real-time space reservations and capacity-based discovery filters. While initial environment setup friction limited complete delivery of the cancellation workflow, the foundational architecture was validated and stabilized. The team concludes the sprint with a highly functional demo-ready artifact and refined technical processes tailored to the Bitcube development environment.

### Key Accomplishments

- Implemented **Story #1 (Basic Room Booking)**, enabling authenticated users to complete real-time room bookings via an intuitive calendar grid view and view details on a dedicated dashboard.
- Implemented **Story #3 (Room Capacity Filtering)**, enabling dynamic frontend filtering against a database-driven `max_capacity` integer field to optimize room discovery.
- Resolved configuration bottlenecks to establish a stable, reusable PERN stack foundation integrated with PostgreSQL and Express.js.

### Challenges Faced

- Lost critical development velocity on Day 1 resolving Node.js package version conflicts and database connection string variables.
- Encountered schema design oversights on Day 4 when implementing **Story #4 (Booking Cancellation)**, realizing that tracking a cancelled state required database properties not mapped out during initial sprint planning.

### Process Improvements Identified

- Transitioning to a strict "Schema-First" workflow where data persistence requirements are completely mapped and reviewed prior to frontend layout implementation.
- Factoring an explicit "Environment/Infrastructure Setup" buffer into estimates for initial sprints to protect core development cycles from configuration overruns.

### Velocity and Burndown Chart

- **Planned Velocity:** 7 Story Points
- **Actual Velocity:** 5 Story Points
- **Value Delivered:** 71% of planned scope completed; core "Search and Book" loop fully functional.

### Sprint 1 Burndown Chart (Story Points vs. Time)

7 |_ 6 | _
5 | _ [Checkpoint: Story #1 Backend Done]
4 | | _
3 | |

2 | | \* [Story #3 Done]
1 | |

0 |----+----+---+----+----
Day 1 Day 2 Day 3 Day 4 Day 5
(Planned: 7 pts -> Actual: 5 pts delivered)
