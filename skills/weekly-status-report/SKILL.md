---
name: weekly-status-report
description: Produce the CEO's weekly status report covering all AEOS categories, KPIs, budget, and priorities. Use at the end of each week or when the CEO requests a status update.
---

# Weekly Status Report

Produce the CEO's weekly status report per the output format defined in the COO persona.

## Process
1. Run `assess-current-state`
2. Compile KPI actuals from each agent's latest report
3. Summarize current state changes from last report
4. List top gaps and what's being done about them
5. Include budget status
6. Note any decisions needed from CEO
7. State next period's top 3 priorities

## Inputs
- All agent status reports
- `docs/current-state.md`
- `docs/ledger.md`
- AEOS document

## Outputs
- Weekly status report (markdown)

## Quality Criteria
- Covers all AEOS categories
- KPIs show target vs actual
- Decisions for CEO include context and a recommendation
- Report is concise — CEO should read it in < 5 minutes
