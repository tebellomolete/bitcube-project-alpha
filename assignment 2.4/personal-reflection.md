# Sprint 1 Personal Reflection

## Key Learning

The most important lesson I learned about sprint workflows is that software execution is heavily tethered to upstream alignment and environment stability. I realized that progress isn't just about putting hours into writing lines of code; if the baseline environment, database connections, or structural schemas aren't solidified beforehand, technical debt accrues immediately. A single configuration hurdle on Day 1 can create a cascading delay that risks downstream deliverables at the end of the week.

## Assumptions That Failed

My planning and execution assumptions broke down the most when it came to database preparedness. I assumed that a simple, initial database schema mapping would naturally stretch to cover every edge case of a feature. This broke down entirely when attempting to execute the cancellation feature, where I realized too late that handling a change in booking state required specific field properties and data mutations that I hadn't properly designed or accounted for during planning.

## Behavioural Change

In Sprint 2, I will change my approach by making sure the database is 100% ready before I start building any frontend features. Instead of jumping straight into designing user interfaces or writing API logic, I will first check that the database tables and columns are fully set up to handle all the statuses and rules required by the user story. This simple change will prevent me from getting stuck halfway through a feature due to missing database fields.

## Professional Growth

To perform effectively within a production-ready Scrum team, I need to strengthen my systematic estimation and forecasting skills. I need to grow more comfortable accounting for technical unknowns, integration overheads, and environment anomalies rather than estimating tasks based solely on ideal coding conditions. This balanced mindset will ensure I communicate highly realistic delivery expectations to stakeholders and team members alike.
