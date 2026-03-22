# AEOS — Puzzleverse, LLC (puzzlemonthly.com)

*Version: 1.0*
*Last updated: 2026-03-20 by CEO*

---

## Mission

Deliver curated jigsaw puzzles to subscribers monthly, keeping minds sharp and engaged — then sell the business at a premium multiple.

## Vision

A streamlined, profitable subscription box business with clean financials, automated fulfillment, and 750+ subscribers — ready for acquisition.

---

## Ideal State

### Product / Service

| # | Criterion | Verified By |
|---|-----------|-------------|
| P1 | Three subscription tiers live and purchasable: Kids, Classic, Pro+ | Shopify + Cratejoy storefront check |
| P2 | No subscriber receives a duplicate puzzle | CRM/order management system history check |
| P3 | Monthly puzzle ships within defined window (by the 15th) | Sweetwater/Extensiv shipping records |
| P4 | Subscription options simplified: fewer SKUs, fewer customizations | Product catalog audit |
| P5 | Puzzle selection partially automated via customer history | Order management system feature |

### Customers / Growth

| # | Criterion | Verified By |
|---|-----------|-------------|
| G1 | 750 active subscribers | Shopify + Cratejoy subscriber count |
| G2 | 30-day retention > 85% | Cohort analysis across platforms |
| G3 | Paid acquisition channels active (Meta, Google, etc.) | Ad platform dashboards |
| G4 | Customer acquisition cost < 3-month subscription value | CAC/LTV calculation |
| G5 | Churn rate < 8% per month | Subscription analytics |

### Revenue / Finance

| # | Criterion | Verified By |
|---|-----------|-------------|
| R1 | Annual revenue > $333,000 (supports 3x exit multiple) | P&L statement |
| R2 | Gross margins > 25% | P&L statement |
| R3 | Clean P&L available: 90-day, LTM, trailing | QuickBooks / accounting system |
| R4 | Unit economics documented: COGS per box, shipping cost, platform fees | Cost spreadsheet |
| R5 | Monthly financial close completed within 5 business days | Accounting calendar |

### Operations / Fulfillment

| # | Criterion | Verified By |
|---|-----------|-------------|
| O1 | Single UI for end-to-end fulfillment: sync subscribers → assign puzzles → submit to 3PL → tracking writeback | Order management app |
| O2 | Fulfillment cycle completable in < 2 hours per month | Process timing |
| O3 | All fulfillment data consolidated (no manual spreadsheet juggling) | System inspection |
| O4 | Paused/canceled subscriptions automatically excluded from fulfillment | System logic |
| O5 | Tracking numbers auto-synced to Shopify + Cratejoy | Storefront verification |
| O6 | Inventory reorder alerts when stock < 2 months supply | Extensiv/order management system |

### Exit Readiness

| # | Criterion | Verified By |
|---|-----------|-------------|
| X1 | 12+ months of clean P&L statements available | Accounting records |
| X2 | All business operations documented as SOPs | SOP document review |
| X3 | Business can run without founder for 30 days | Operational test |
| X4 | Subscriber growth trajectory is positive (3+ consecutive months) | Analytics |
| X5 | Business valued at $350K–$1M by broker or comparable analysis | Broker valuation / multiple calc |

---

## Current State

*Last snapshot: 2026-03-20*

| Area | Status | Notes |
|------|--------|-------|
| Product | Live, needs simplification | 3 tiers active on Shopify + Cratejoy. Too many SKUs and customization options. |
| Growth | Stalled at ~80-90 subscribers | No active ad spend. Fulfillment must be solved before scaling. |
| Revenue | ~$2,700–3,400/mo estimated | Based on ~90 subs × $30–38 avg. Margins ~10-20%. No clean P&L. |
| Fulfillment | Painful, manual, fragmented | Spreadsheets + manual processes across Shopify, Cratejoy, Sweetwater. Order management system in development. |
| Finance | No system of record | No QuickBooks. No formal P&L. Revenue/cost data scattered. |
| Exit readiness | Not ready | No documented SOPs, no clean financials, too founder-dependent. |

### Infrastructure Status

| System | Status | Notes |
|--------|--------|-------|
| Shopify | Active | Primary storefront. Appstle for subscription management. |
| Cratejoy | Active | Secondary storefront. No API for subscriber sync (manual CSV). |
| Sweetwater / Extensiv | Active | 3PL fulfillment. API integration in progress. |
| Order Management App | In development | PocketBase + React. Shopify sync done. Extensiv tracking done. |
| Accounting (QuickBooks) | Not set up | Identified as priority. |
| Ad platforms | Not set up | Blocked by fulfillment. |
| Analytics | Not set up | No centralized subscriber/revenue dashboard. |

---

## Gap Analysis

| Gap | Ideal Criterion | Current Reality | Priority | Closes Via |
|-----|----------------|-----------------|----------|------------|
| Fulfillment is manual and fragmented | O1, O2, O3 | Spreadsheets, multiple systems, hours of manual work | **Critical** | Order management system (puzzle-monthly-order-manager) |
| No clean financials | R3, R4, R5, X1 | No P&L, no QuickBooks, costs scattered | **High** | QuickBooks setup, monthly close process |
| Subscriber count far from target | G1 | ~90 vs. 750 target | **High** | Blocked by fulfillment + ad spend |
| No ad spend / growth engine | G3, G4 | Zero paid acquisition | **High** | Blocked by fulfillment fix, then creative + campaign setup |
| Pricing not optimized | R2 | Shopify Classic 30-34% margin, Cratejoy Pro as low as 10%. Pricing sheet stale since Dec 2022. | **High** | Pricing review, raise prices, migrate subscribers to Shopify |
| Product too complex | P4 | Too many SKUs, customizations | **Medium** | Simplify tiers and options |
| No duplicate-puzzle tracking | P2 | Manual tracking via spreadsheet | **Medium** | CRM feature in order management system |
| Business too founder-dependent | X3 | Founder runs everything | **Medium** | SOPs, automation, documented processes |
| Cratejoy sync is manual | O1 | CSV export/import, no API | **Medium** | Cratejoy API spike (TASK-006) or migration to Shopify-only |

---

## Operating Rules

1. **Fulfillment before growth.** Do not spend on ads or marketing until the fulfillment system can handle increased volume without manual intervention.
   *Why: Scaling a broken process just makes it more broken. Fix the foundation first.*

2. **No PII exposure.** Customer data stays in PocketBase, never sent to external APIs or AI services.
   *Why: Trust and compliance. Subscription businesses live on customer trust.*

3. **Simplify the offering.** Fewer SKUs, fewer customization options. Complexity kills margins and fulfillment speed.
   *Why: Team meeting consensus — current system is "too complex, not streamlined, tedious, frustrating."*

4. **Prod system caution.** All writes to Extensiv, Shopify, or Cratejoy require dry-run mode and owner monitoring.
   *Why: Shipping the wrong puzzle or double-charging a customer is unrecoverable.*

5. **Build for the exit.** Every operational decision should make the business easier to understand, value, and transfer.
   *Why: The goal is a $350K–$1M exit within 6-12 months. Messy operations kill deal flow.*

6. **Skew pricing to incentivize Shopify.** Shopify has better margins and better integrations than Cratejoy.
   *Why: Consolidating on one platform simplifies operations and improves unit economics.*

---

## Escalation Triggers

- [ ] A decision requires spending > $500 in a single action
- [ ] A new supplier or vendor relationship needs to be established
- [ ] A customer reports a serious issue (wrong puzzle, billing error, data concern)
- [ ] Any system write to Shopify/Cratejoy/Extensiv in production (non-dry-run)
- [ ] A pricing change is proposed
- [ ] A decision affects exit timeline or valuation
- [ ] Inventory drops below 1 month supply for any tier

---

## Financial Ledger Reference

*To be maintained in QuickBooks once set up. Summary targets:*

| | Target | Current |
|---|--------|---------|
| Monthly revenue target | $27,750 ($333K/12) | ~$2,700–3,400 |
| Monthly subscribers | 750 | ~80-90 |
| Avg subscription price | $30-38 | $30-38 |
| Gross margin target | > 25% | 10-34% (varies by platform/tier) |
| Total budget (monthly ops) | TBD | TBD |

### Pricing & Margins by Product (as of Dec 2022 pricing — stale, review needed)

**Shopify — Classic**

| Term | Price/mo | Net Profit/mo | Margin |
|------|----------|---------------|--------|
| 1 month | $31.87 | — (#REF errors) | ~34% est. |
| 3 month | $30.89 | $10.51 | 34.0% |
| 6 month | $29.53 | $9.19 | 31.1% |
| 12 month | $28.87 | $8.55 | 29.6% |

**Cratejoy — Classic**

| Term | Price/mo | Net Profit/mo | Margin |
|------|----------|---------------|--------|
| 1 month | $35.99 | $7.44 | 20.7% |
| 3 month | $34.99 | $6.95 | 19.9% |
| 6 month | $33.99 | $6.26 | 18.4% |
| 12 month | $32.91 | $5.48 | 16.6% |

**Cratejoy — Pro**

| Term | Price/mo | Net Profit/mo | Margin |
|------|----------|---------------|--------|
| 1 month | $38.99 | $5.51 | 14.1% |
| 3 month | $37.99 | $5.03 | 13.2% |
| 6 month | $36.99 | $4.34 | 11.7% |
| 12 month | $35.99 | $3.61 | 10.0% |

**Kids and Pro+ (Shopify):** Pricing data present but incomplete in source sheet.

### Unit Costs (per box)

| Cost | Classic | Pro |
|------|---------|-----|
| Puzzle wholesale | $8.50 | $12.00 |
| Shipping to customer | $8.30 | $9.00 |
| Box | $1.83 | $1.83 |
| Label | $0.05 | $0.05 |
| Stickers | $0.50 | $0.50 |
| Insert (postcard) | $0.22 | $0.22 |
| Tape | $0.05 | $0.05 |
| **Total COGS/box** | **$19.45** | **$23.65** |

### Platform Fee Impact

Cratejoy takes ~24% off the top (15% referral + 1.25% transaction + 2.9% Stripe + 5% ads). Shopify has no marketplace fees — only standard payment processing. This is why Shopify margins are nearly 2x Cratejoy margins on the same product.

**Action needed:** Pricing sheet dates to Dec 2022. Team meeting notes (Oct 2025) called for price raises. Current actual pricing vs. this sheet needs verification.

---

## Agent Team

| Role | Scope | Model | Active? |
|------|-------|-------|---------|
| COO | Orchestration, KPI monitoring, initiative planning | TBD | No |
| Fulfillment Ops | Order management system development | Claude via ARCH | Yes (in development) |
| Revenue / Pricing | Unit cost analysis, pricing optimization | TBD | No |
| Growth / Marketing | Ad creative, campaign management, acquisition | TBD | No |
| Finance | QuickBooks setup, P&L, monthly close | TBD | No |

---

## Customer Profile

**Primary persona: "The Brainy Boomers"**
- 65+, Baby Boomer generation, retired
- Suburban/rural, middle to upper-middle class
- Value mental stimulation, quality of life, lifelong learning
- Pain: maintaining mental agility, finding engaging non-digital activities
- Purchase drivers: mentally stimulating, age-appropriate, manageable, enjoyable

See: `Perfect Customer Profile - Brainy Boomers (1).md`

---

## Changelog

| Date | Change | Reason |
|------|--------|--------|
| 2026-03-20 | Initial AEOS created | Formalizing business operations for scale and exit |
