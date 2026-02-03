# Capacity Planning (Enterprise Standard)

## Purpose
Capacity Planning ensures that sprint and program commitments are realistic, sustainable, and aligned with actual team availability. It protects teams from overcommitment while enabling predictable delivery.

## Definition
Capacity represents the **actual available effort** a team can apply to delivery during a sprint, after accounting for all non-delivery activities.

Capacity planning is **not estimation**. It is a constraint-setting activity.

## Capacity Inputs
Capacity planning must consider the following inputs before Sprint Planning:

- Team size and role distribution
- Planned PTO and holidays
- On-call, support, and operational duties
- Training, ceremonies, and mandatory meetings
- Historical throughput and velocity trends
- Known dependencies and risk buffers

## Capacity Calculation (Team-Level)
Recommended approach:

1. Start with total working days in the sprint
2. Subtract non-working days (holidays, PTO)
3. Subtract recurring non-delivery time:
   - Support/on-call
   - Meetings and ceremonies
   - Production support
4. Convert remaining time to:
   - Story points (preferred), or
   - Ideal hours (only if points are unavailable)

> Capacity must be calculated **before** selecting backlog items.

## Capacity Guardrails
- Never plan at 100% capacity
- Maintain a 10–20% buffer for unplanned work
- Reduce planned scope when:
  - Dependencies are unresolved
  - Team composition has changed
  - Prior sprint spillover exists

## Role Responsibilities

### Scrum Master
- Facilitates capacity discussion
- Protects the team from overcommitment
- Makes constraints visible to stakeholders
- Ensures capacity is respected during planning

### Product Owner
- Prioritizes within capacity limits
- Makes trade-off decisions when capacity is constrained
- Avoids pressuring the team beyond sustainable limits

### Developers
- Provide honest availability inputs
- Identify risks and constraints early
- Commit only to work they believe is achievable

## Common Mistakes
- Ignoring PTO or support work
- Using aspirational capacity instead of actual availability
- Treating velocity as a target rather than a signal
- Allowing scope pressure to override constraints

## Success Indicators
- Minimal sprint spillover
- Stable or improving predictability
- Reduced mid-sprint scope changes
- Sustainable team pace over multiple sprints

## Guiding Principle
Capacity defines commitment boundaries.  
Commitments must adapt to capacity — not the other way around.
