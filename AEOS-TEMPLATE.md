# AEOS — [Enterprise Name]

*Version: 1.0*
*Last updated: [Date] by [CEO/COO]*

---

## Mission

[One sentence: why does this enterprise exist? What problem does it solve, and for whom?]

## Vision

[One sentence: what does the world look like when this enterprise succeeds at scale?]

---

## Ideal State

Each criterion is **discrete and verifiable** (yes/no). These are both the goals AND the verification criteria. The COO uses them to hill-climb — every initiative should trace back to closing a gap against one or more of these criteria.

Write criteria that are specific enough to verify, but stable enough that they don't change every week. Good criteria describe outcomes, not activities.

### Product / Service

*What you deliver to customers. Quality, completeness, reliability.*

| # | Criterion | Verified By |
|---|-----------|-------------|
| P1 | [e.g., "Core product is live and accessible to users"] | [How you verify: site check, test, audit] |
| P2 | [e.g., "User satisfaction score > X%"] | [Survey data, NPS] |
| P3 | [e.g., "Product meets defined quality standard"] | [QA pass, user testing sign-off] |
| P4 | [e.g., "New features ship within X days of spec approval"] | [Cycle time tracking] |
| P5 | | |

### Customers / Growth

*Who uses it and how you reach them. Acquisition, retention, referral.*

| # | Criterion | Verified By |
|---|-----------|-------------|
| G1 | [e.g., "X active users by [date]"] | [Analytics] |
| G2 | [e.g., "30-day retention > X%"] | [Cohort analysis] |
| G3 | [e.g., "Organic referral rate > X%"] | [Referral tracking] |
| G4 | [e.g., "At least N active acquisition channels"] | [Channel attribution] |
| G5 | | |

### Revenue / Finance

*How you make money and manage resources. Revenue, costs, profitability.*

| # | Criterion | Verified By |
|---|-----------|-------------|
| R1 | [e.g., "Monthly revenue > monthly costs (self-sustaining)"] | [Ledger] |
| R2 | [e.g., "At least N revenue streams active"] | [Revenue report] |
| R3 | [e.g., "Customer acquisition cost < lifetime value"] | [CAC/LTV calculation] |
| R4 | [e.g., "Total spend within budget cap of $X"] | [Ledger] |
| R5 | | |

### Engagement / Experience

*How deeply customers interact with your product. Usage depth, satisfaction, loyalty.*

| # | Criterion | Verified By |
|---|-----------|-------------|
| E1 | [e.g., "Average session length X-Y minutes"] | [Analytics] |
| E2 | [e.g., "Daily/weekly engagement rate > X%"] | [Analytics] |
| E3 | [e.g., "Customer satisfaction (NPS/CSAT) > X"] | [Survey] |
| E4 | [e.g., "Churn rate < X% per month"] | [Subscription data] |
| E5 | | |

### Operations / Team

*How the business runs. Agent performance, process efficiency, reliability.*

| # | Criterion | Verified By |
|---|-----------|-------------|
| O1 | [e.g., "All agent roles defined and operational"] | [File/system inspection] |
| O2 | [e.g., "Key process cycle time < X hours"] | [Process log] |
| O3 | [e.g., "System uptime > X%"] | [Monitoring] |
| O4 | [e.g., "Support response time < X hours"] | [Support log] |
| O5 | [e.g., "COO produces weekly status report"] | [Report log] |
| O6 | | |

### [Custom Category]

*Add categories specific to your enterprise. Examples: Compliance, Partnerships, Content, Community, Security.*

| # | Criterion | Verified By |
|---|-----------|-------------|
| C1 | | |
| C2 | | |

---

## Current State

*Updated by the COO Agent continuously. This is an honest snapshot — not aspirational, not optimistic. What is true right now?*

*Last snapshot: [Date]*

| Area | Status | Notes |
|------|--------|-------|
| Product | [Not started / In progress / Live / Needs attention] | [Details] |
| Growth | [Metrics: users, DAU, retention] | [Details] |
| Revenue | [Revenue, spend, runway] | [Details] |
| Engagement | [Key engagement metrics] | [Details] |
| Operations | [Agent status, process health] | [Details] |

### Infrastructure Status

| System | Status | Notes |
|--------|--------|-------|
| [Hosting] | [Active / Not set up] | |
| [Database] | [Active / Not set up] | |
| [Email service] | [Active / Not set up] | |
| [Payment processing] | [Active / Not set up] | |
| [Analytics] | [Active / Not set up] | |
| [Domain/DNS] | [Active / Not set up] | |

---

## Gap Analysis

*Derived from Ideal State vs Current State. Updated whenever current state changes. Ordered by priority.*

Priority is scored by: **Impact** (how much does closing this gap move the business forward?) × **Urgency** (is there a deadline or dependency?) × **Feasibility** (can we close this gap with available resources?).

| Gap | Ideal Criterion | Current Reality | Priority | Closes Via |
|-----|----------------|-----------------|----------|------------|
| [Description] | [Criterion ID] | [What's true now] | [High/Med/Low] | [Initiative / Sprint / Agent action] |
| | | | | |
| | | | | |

---

## Operating Rules

*Constraints on how the system operates. These are constitutional — they don't change sprint to sprint. They encode the CEO's values, risk tolerance, and non-negotiables.*

1. **[Rule name].** [Rule statement.]
   *Why: [Reasoning — so agents can apply judgment in edge cases.]*

2. **[Rule name].** [Rule statement.]
   *Why: [Reasoning.]*

### Examples of common operating rules:
- Budget constraints ("Total spend must not exceed $X")
- Quality gates ("No feature ships without user testing")
- CEO time protection ("Minimize CEO involvement to < X hours/week after setup")
- Ethical boundaries ("No dark patterns, no misleading marketing")
- Technical constraints ("Use free tiers until scale demands otherwise")
- Iteration speed ("Ship weekly, not monthly")

---

## Escalation Triggers

*The COO escalates to the CEO when any of these conditions are met. This defines the boundary of the COO's autonomous authority.*

- [ ] A decision requires spending > $[threshold] in a single action
- [ ] A strategic pivot is needed (changing target market, killing a product, etc.)
- [ ] An external account requires human identity verification
- [ ] A legal, compliance, or ethical question arises
- [ ] Any KPI is > [X]% off target for [N]+ consecutive weeks
- [ ] An agent is blocked for > [X] hours with no resolution path
- [ ] A user/customer reports a serious issue (data loss, security, safety)
- [ ] A partnership or contract decision needs to be made
- [ ] [Custom trigger specific to this enterprise]

---

## Financial Ledger Reference

*The COO maintains a detailed ledger at `docs/ledger.md`. Summary here:*

| | Amount |
|---|--------|
| Total budget | $[amount] |
| Total spent | $[amount] |
| Total revenue | $[amount] |
| Net profit | $[amount] |
| Remaining budget | $[amount] |

---

## Agent Team

*List the specialist agent roles that operate this enterprise. Each role has a persona (CLAUDE.md) and skills (SKILLS.md) defined under `personas/[role-name]/`.*

| Role | Scope | Model | Active? |
|------|-------|-------|---------|
| COO | Orchestration, KPI monitoring, initiative planning | [opus/sonnet] | [Yes/No] |
| [Role 2] | [Scope] | [Model] | [Yes/No] |
| [Role 3] | [Scope] | [Model] | [Yes/No] |
| ... | | | |

*Not every agent runs all the time. The COO spawns agents on-demand based on what The Algorithm identifies as the highest-priority gap to close.*

---

## Changelog

*Track strategic changes to the AEOS. This is not a task log — it's a record of when the constitution changed and why.*

| Date | Change | Reason |
|------|--------|--------|
| [Date] | Initial AEOS created | Business launch |
| | | |
