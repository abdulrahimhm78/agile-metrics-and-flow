# Capacity Forecasting (Enterprise Standard)

## Purpose
Capacity Forecasting provides a disciplined approach to estimating delivery capability over time so teams and programs can make realistic commitments, manage risk, and improve predictability across sprints, PIs, and quarters.

## Scope
This standard applies to:
- Single Scrum teams
- Agile Release Trains (ARTs)
- Programs operating in SAFe or enterprise Agile environments

Capacity forecasting is used for **planning and decision-making**, not for performance evaluation.

---

## Core Principles
- **Reality-based planning** over aspirational commitments  
- **Capacity is finite** and must account for non-delivery work  
- **Forecasts are probabilistic**, not guarantees  
- **Transparency over precision**  
- **Adjust continuously** based on empirical data  

---

## Inputs
Capacity forecasts are built using the following inputs:

### Team Availability
- Sprint length
- Team size
- PTO, holidays, training
- On-call or support rotations

### Historical Performance
- Average velocity (last 3–6 sprints)
- Throughput trends
- Cycle time stability
- Work spillover patterns

### Planned Work
- Backlog readiness (DoR compliance)
- Known dependencies
- Risk items
- Mandatory operational work

---

## Capacity Calculation (Team Level)

### Step 1: Establish Baseline Capacity
Baseline Capacity = Average Velocity (last 3–6 sprints)


### Step 2: Adjust for Availability
Adjusted Capacity = Baseline Capacity × Availability %

Examples of availability reductions:
- PTO (planned)
- Production support
- Platform or compliance work
- Known external dependencies

### Step 3: Apply Risk Buffer
- Typical buffer: **10–20%**
- Higher uncertainty = larger buffer
Forecasted Capacity = Adjusted Capacity – Risk Buffer


---

## Program-Level Forecasting
At scale, forecasting aggregates **team-level capacity** with additional considerations:

### Program Adjustments
- Cross-team dependencies
- Integration and system testing
- Release governance activities
- PI objectives confidence voting

### Rolling Forecasts
- Update forecasts at:
  - Sprint boundaries
  - Mid-PI checkpoints
  - Dependency resolution points

---

## Forecast Horizons
Capacity forecasts are produced at multiple horizons:

| Horizon | Usage |
|-------|------|
| Sprint | Commitment validation |
| PI | Objective planning and confidence |
| Quarter | Roadmap alignment |
| Annual | Strategic planning (high-level only) |

Longer horizons require **larger confidence bands**.

---

## Output Artifacts
Effective capacity forecasting produces:

- Sprint capacity summary
- PI capacity view by team
- Risk-adjusted delivery forecast
- Assumptions and constraints log
- Confidence ranges (best / likely / worst case)

---

## Roles and Responsibilities

### Scrum Master
- Facilitates capacity discussions
- Protects teams from overcommitment
- Ensures assumptions are explicit
- Tracks forecast vs actuals

### Product Owner
- Prioritizes work within capacity limits
- Makes scope trade-off decisions
- Ensures backlog readiness

### RTE / Program Leadership
- Aligns dependencies
- Communicates delivery confidence
- Adjusts scope at program level

---

## Good Practices
- Use **ranges**, not single numbers
- Separate **capacity** from **demand**
- Re-forecast frequently
- Make assumptions visible
- Tie forecasts to historical data

---

## Common Mistakes
- Ignoring PTO and support work
- Treating forecasts as commitments
- Using velocity targets
- Over-aggregating across unstable teams
- Planning beyond backlog readiness

---

## Guiding Principle
> Capacity forecasting exists to enable informed decisions, not to justify unrealistic commitments.

Predictability improves when teams plan within reality and adjust early.
