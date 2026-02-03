# Agile Metrics and Flow (Enterprise Standard)

This document defines the enterprise-standard Agile metrics and flow practices used to measure delivery health, improve predictability, and enable data-driven decision-making without incentivizing unhealthy behaviors.

---

## Purpose

To provide clear, actionable metrics that:
- Improve delivery predictability
- Optimize flow of work
- Increase transparency for teams and leadership
- Enable continuous improvement without micromanagement

Metrics exist to **inform decisions**, not to evaluate individual performance.

---

## Core Principles

- **Flow over utilization**: Optimize how work moves, not how busy people are
- **Outcome over output**: Measure value delivered, not activity
- **Trends over snapshots**: Direction matters more than a single data point
- **System metrics, not people metrics**
- **Few metrics, used consistently**

---

## Flow Metrics (Primary)

Flow metrics focus on how efficiently work moves through the system.

### 1. Cycle Time
**Definition:**  
Time from work start to work completion.

**Why it matters:**  
Measures delivery speed and system efficiency.

**Healthy signals:**
- Stable or decreasing trend
- Predictable ranges

**Anti-patterns:**
- Large variance sprint to sprint
- Long-tail outliers ignored

---

### 2. Throughput
**Definition:**  
Number of work items completed per time period.

**Why it matters:**  
Indicates delivery capacity and consistency.

**Healthy signals:**
- Stable throughput over time
- Alignment with team capacity

**Anti-patterns:**
- Chasing higher numbers at the cost of quality
- Comparing teams directly

---

### 3. Work in Progress (WIP)
**Definition:**  
Number of items actively in progress.

**Why it matters:**  
High WIP increases delays and context switching.

**Healthy signals:**
- Explicit WIP limits
- Low carryover between sprints

**Anti-patterns:**
- Too many items started, few finished
- Hidden or untracked work

---

### 4. Flow Efficiency
**Definition:**  
Active work time ÷ total elapsed time.

**Why it matters:**  
Reveals wait states, dependencies, and bottlenecks.

**Healthy signals:**
- Improving efficiency trend
- Reduced waiting on approvals or dependencies

**Anti-patterns:**
- Long idle states
- Work blocked outside the team’s control

---

## Predictability Metrics (Secondary)

Used to understand reliability, not to enforce commitments.

### 5. Planned vs Completed
**Definition:**  
Work planned at sprint start vs work completed.

**Use:**  
Inspect planning quality and external disruptions.

**Anti-patterns:**
- Using as a performance score
- Forcing teams to “commit harder”

---

### 6. Carryover Rate
**Definition:**  
Percentage of work moved to the next sprint.

**Healthy signals:**
- Low and consistent carryover
- Root causes discussed in retrospectives

---

## Quality Metrics (Guardrails)

Quality metrics ensure flow improvements do not erode stability.

### 7. Defect Escape Rate
**Definition:**  
Defects found after release.

**Signal:**  
Rising rates indicate rushed delivery or weak DoD.

---

### 8. Rework Rate
**Definition:**  
Work reopened or reworked after completion.

**Signal:**  
Indicates unclear requirements or weak acceptance criteria.

---

## Flow Visualization

Recommended visual tools:
- Cumulative Flow Diagram (CFD)
- Control Charts (Cycle Time)
- Sprint Flow Dashboard
- Blocker Aging Reports

Visuals should be **visible to the team first**, leadership second.

---

## Metrics by Audience

### Team Level
- Cycle Time
- WIP
- Blockers
- Flow Efficiency

**Used in:** Daily Scrum, Retrospectives

---

### Product / Delivery Leadership
- Throughput trends
- Predictability trends
- Dependency impact

**Used in:** Sprint Reviews, Delivery Reviews

---

### Executive / Portfolio Level
- Flow stability
- Delivery confidence
- Risk trends

**Used in:** Quarterly reviews, PI execution

---

## Common Anti-Patterns

- Using metrics to rank teams
- Individual-level metrics
- Velocity as a target
- Measuring everything, acting on nothing
- Ignoring trends in favor of single data points

---

## Guiding Statement

> Metrics do not drive behavior — how leaders respond to metrics does.

Healthy Agile organizations use metrics to **learn, adapt, and improve the system**, not to control people.
