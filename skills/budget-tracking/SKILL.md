---
name: budget-tracking
description: Maintain the financial ledger and flag budget risks. Use when recording expenditures or checking budget status. Does NOT include agent token costs tracked by ARCH.
---

# Budget Tracking

Maintain the financial ledger and flag budget risks. Tracks real-dollar business expenditures only (domain, services, ads, inventory, etc.). Agent token costs are tracked separately by ARCH.

## Process
1. Record every expenditure in `docs/ledger.md` with date, amount, category, description
2. Calculate remaining budget
3. Project burn rate and runway
4. Flag if projected spend will exceed budget cap (defined in AEOS)
5. Include in weekly status report

## Inputs
- Receipts, invoices, account statements
- Agent reports of spend (ad spend, inventory orders, service costs, etc.)

## Outputs
- Updated `docs/ledger.md`
- Budget status in weekly report

## Quality Criteria
- Every dollar is accounted for
- Projections are based on actual data, not assumptions
- CEO is alerted before any single expenditure exceeds the threshold defined in AEOS escalation triggers
