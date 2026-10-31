# Luna Transport Group — Trucking Company Scaling System

A practical, evidence-driven operating system for growing a trucking company from a small fleet into a profitable, professionally managed transportation business.

This repository turns day-to-day trucking operations into repeatable, measurable systems. It is designed to be implemented incrementally: document the current operation, establish reliable records, standardize critical workflows, measure unit economics, and automate only after the underlying process is understood and controlled.

## Operating architecture

```text
TRUCKING COMPANY
       |
       v
Operational Intelligence
       |
       +-- Fleet Management
       +-- Load Acquisition
       +-- Dispatch Operations
       +-- Driver Management
       +-- Maintenance
       +-- Safety & Compliance
       +-- Financial Management
       +-- Customer Relationships
       |
       v
Standard Operating Procedures
       |
       v
Structured Workflows
       |
       v
Automation (with human authority and exception handling)
       |
       v
Performance Measurement
       |
       v
Profitable, controlled growth
```

## The five operating questions

1. How do we acquire more profitable business?
2. How do we increase productive fleet utilization?
3. How do we reduce controllable operating costs without creating safety or service failures?
4. How do we scale people and operations without losing control?
5. How do we grow without sacrificing cash flow or profitability?

## Repository map

| Area | Purpose |
|---|---|
| [01-business-model](01-business-model/) | Company structure, revenue model, and growth strategy |
| [02-fleet-operations](02-fleet-operations/) | Utilization, dispatch, driver management, and maintenance |
| [03-load-management](03-load-management/) | Freight acquisition, load selection, and load-level profitability |
| [04-financial-systems](04-financial-systems/) | Cost per mile, cash flow, truck economics, and dashboard definitions |
| [05-safety-compliance](05-safety-compliance/) | Compliance controls, qualification files, and safety management |
| [06-workforce](06-workforce/) | Hiring, onboarding, role clarity, and management structure |
| [07-automation](07-automation/) | Workflow design, AI boundaries, and operational intelligence |
| [08-scaling](08-scaling/) | Stage gates for 1–5, 5–20, 20–50, and 50–100 trucks |
| [research](research/) | Experiments, datasets, and evidence-based findings |

## Implementation sequence

1. **Establish the baseline.** Inventory trucks, trailers, drivers, customers, lanes, costs, obligations, systems, and current responsibilities.
2. **Make the numbers trustworthy.** Define common data fields and reconcile dispatch, settlement, fuel, maintenance, payroll, insurance, and accounting records.
3. **Standardize high-risk workflows.** Start with load acceptance, dispatch handoff, hours-of-service feasibility, maintenance defects, incident response, and invoice collection.
4. **Install a management cadence.** Review daily exceptions, weekly operating metrics, and monthly financial performance.
5. **Improve before automating.** Automate stable, bounded steps; preserve human approval for consequential decisions and explicit paths for exceptions.
6. **Scale only when stage gates are met.** Add trucks when demand, drivers, cash, maintenance capacity, safety controls, and management bandwidth support them.

## Core management principle

**A truck added to the fleet is not automatically growth.** Growth is the addition of dependable, profitable capacity that the organization can safely dispatch, maintain, finance, and manage.

Use contribution margin and cash conversion—not gross revenue or truck count alone—to evaluate growth.

## Evidence and operating discipline

- Distinguish recorded facts, estimates, assumptions, and decisions.
- Record the source, owner, date, and confidence of important operating data.
- Define each KPI with a formula, unit, time window, inclusion rules, and accountable owner.
- Do not treat missing data as zero.
- Preserve exceptions and unfavorable outcomes; do not silently discard them.
- Compare actual results with the plan and document corrective actions.
- Test process changes on a bounded scope before making them company-wide.

## Important scope note

This repository is an operating framework, not legal, tax, accounting, insurance, or safety advice. Requirements depend on the carrier's operations, authority, equipment, locations, contracts, and current regulations. Confirm applicable requirements with qualified professionals and authoritative federal, state, and local sources before relying on a procedure. Never use automation to bypass required human judgment, safety controls, or regulatory obligations.

## First practical deliverable

Complete a one-page baseline for every power unit and the business as a whole:

- Equipment status and availability
- Assigned driver and qualification status
- Current dispatch / load status
- Revenue and loaded / empty miles
- Fuel, driver, maintenance, insurance, toll, and other attributable costs
- Outstanding receivables and payables
- Safety, compliance, and maintenance exceptions
- Data source and last verified date

Then use the relevant SOP and KPI definitions in this repository to close the largest operational control gaps first.

## Status

This repository begins as a structured operating-system specification. Company-specific policies, targets, workflows, and conclusions must be populated from verified Luna Transport Group records—not assumed defaults.
