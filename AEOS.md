# AEOS — Agentic Enterprise Operating System

## What It Is

AEOS is the business's constitution. It defines **what the business is trying to achieve** (ideal state), **where it is right now** (current state), and **how to close the gap** (the algorithm). The CEO and COO Agent co-develop the AEOS. The COO works continuously to move current state toward ideal state.

This is not a project plan. It is a living system for **ideal state management** — the continuous, measurable migration from where we are to where we want to be.

> "You can't hill-climb if you don't have a thing to hill-climb against."
> — Andrej Karpathy

The ideal state criteria ARE the verification criteria. Every initiative, every sprint, every agent action should be traceable to closing a specific gap between current and ideal.

---

## The Algorithm

```
┌──────────────────────────────────────────────────────┐
│                   THE ALGORITHM                      │
│                                                      │
│   1. DEFINE IDEAL STATE                              │
│      What does "done" look like?                     │
│      Discrete, verifiable yes/no criteria.           │
│                                                      │
│   2. ASSESS CURRENT STATE                            │
│      Honest snapshot of reality right now            │
│      Updated by the COO continuously.                │
│                                                      │
│   3. CONTINUOUS MIGRATION                            │
│      Identify the largest gaps.                      │
│      Spawn initiatives to close them.                │
│      Verify progress against ideal state criteria.   │
│      Repeat.                                         │
│                                                      │
│   This works at every scale:                         │
│   a solo business, a team, a family, a civilization. │
└──────────────────────────────────────────────────────┘
```

This algorithm is the COO Agent's core loop. It runs continuously. It is the heartbeat of the enterprise.

---

## The Stack

```
CEO (Human)
│
│  Sets vision, approves strategy, handles/delegates human-required tasks.
│  Intervenes when the system escalates or when strategic pivots are needed.
│
▼
AEOS (System — this document)
│
│  The business's constitution. Encodes:
│    • Ideal state — discrete, verifiable criteria
│    • Current state — honest snapshot, updated continuously
│    • Gap analysis — derived from ideal vs current
│    • Operating rules — constraints on how gaps get closed
│    • Escalation triggers — when to alert the CEO
│
│  Co-authored by CEO and COO. Updated when strategy changes.
│  Read by everything below.
│
▼
COO Agent (Persistent)
│
│  The always-on operator. Core loop:
│    1. Read AEOS ideal state
│    2. Assess current state
│    3. Identify largest gaps
│    4. Spawn Archie (ARCH) sessions to close them
│    5. Monitor KPIs to verify progress
│    6. Report to CEO at defined intervals
│    7. Escalate decisions that exceed authority
│    8. Repeat
│
│  The COO does NOT execute tasks. It orchestrates.
│  It is persistent — it maintains state across sessions.
│
▼
Archie Sessions (Ephemeral)
│
│  Scrum master / project manager for a specific initiative.
│  Each session has:
│    • BRIEF.md — scope, deliverables, definition of done
│    • A team of specialist agents
│    • A start and an end
│    • Traceability to a specific ideal-state gap it is closing
│
│  Archie decomposes the brief, spawns agents, coordinates,
│  and reports completion back to the COO.
│
▼
Specialist Agents (Task Workers)
│
│  Execute specific work within an Archie session.
|  Execute SOPs.
│  Each has a persona (CLAUDE.md|AGENT.md) and skills (SKILLS.md).
│  Work in isolated git worktrees. Communicate via MCP.
│  Report to Archie. Do not persist beyond the session.
```

## Key Distinctions

| Layer | Lifespan | Scope | Analogy |
|-------|----------|-------|---------|
| CEO | Permanent | The business | Founder |
| AEOS | Permanent | The business | Company charter + OKRs |
| COO Agent | Persistent | All operations | Chief of Staff |
| Archie | Ephemeral | One project/sprint | Scrum Master |
| Specialist Agent | Ephemeral | One task | Individual contributor |

**Persistent** means the agent maintains context, memory, and state across sessions. It doesn't start fresh each time — it knows what happened yesterday.

**Ephemeral** means the agent is spawned for a purpose and terminates when that purpose is complete. It may save artifacts, but it does not carry forward.

---

## How It Works in Practice

1. **CEO and COO co-author the AEOS document** — defining ideal state criteria, current state, operating rules, and escalation triggers.

2. **COO reads AEOS** and runs The Algorithm: assess current state, identify the largest gaps between current and ideal, determine what to do about them.

3. **COO writes a BRIEF.md** for each initiative and spawns an Archie session via ARCH to execute it. Multiple Archie sessions can run concurrently across different business functions.

4. **Archie decomposes the brief**, spawns specialist agents, coordinates their work, and delivers the output.

5. **COO monitors progress** across all active Archie sessions. When one finishes, it evaluates the result against AEOS ideal state criteria and decides what's next.

6. **COO escalates to CEO** when a decision exceeds its authority (per the escalation triggers defined in the AEOS).

7. **AEOS document is updated** when the CEO and COO agree on strategic changes — new criteria, revised targets, expanded scope, lessons learned.

---

## What AEOS Is Not

- **Not a codebase.** It's a living document (or small set of documents) that defines business intent.
- **Not ARCH.** ARCH is the execution engine. AEOS is the strategic layer that tells ARCH what to execute.
- **Not static.** It evolves as the business learns. Ideal state criteria get refined, priorities shift, new criteria are added.
- **Not a replacement for the CEO.** The CEO sets vision and makes final calls. AEOS encodes those decisions so the system can act on them without asking every time.
- **Not a static org chart.** The business is a dynamic graph of operations, not a fixed hierarchy. The people and agents doing the work change; the work itself — the SOPs, workflows, decision points — is what AEOS governs.
- **Not aspirational.** Current state must be an honest snapshot of reality, not an optimistic one. The system can only hill-climb if it knows where it actually is. Inflated current state assessments break the algorithm.

---

## ARCH — The Execution Engine

AEOS defines what the business is trying to achieve and how to close the gap. **ARCH executes it.**

[ARCH (Agent Runtime & Coordination Harness)](https://github.com/levinebw/arch) is the multi-agent system that brings the AEOS stack to life. When the COO identifies a gap and writes a BRIEF.md, ARCH is what spawns the Archie session to execute it. Archie (the Lead Agent) reads the brief, proposes a team of specialist agents, and coordinates their work across isolated git worktrees via a local MCP message bus.

```
AEOS        →    defines the gap and the brief
ARCH        →    spawns Archie and the agent team to close it
Archie      →    decomposes the brief, coordinates agents, reports back
Specialists →    execute the work in parallel, isolated worktrees
```

ARCH handles: dynamic team planning, user approval gates, agent-to-agent messaging, token/cost tracking, sandboxed execution, and a live terminal dashboard.

AEOS is the strategy. ARCH is the runtime.

---

## Open Problems / Future Development

These topics are central to a complete implementation of AEOS and require further definition.

**The Operational Graph.** The COO doesn't run The Algorithm in the abstract — it operates against a living map of all the company's work: every SOP, workflow, tool, decision point, and agent role. This graph is the substrate that makes gap analysis concrete and auditable. How this graph is represented, maintained, and traversed is an open design question.

**Current State Data Sources.** The COO's current state assessment is only as good as the data feeding it. What constitutes "unified entity context"? What inputs — financial ledger, KPI dashboards, agent output logs, customer signals, SOP health — are required, and how are they kept current? This is the infrastructure layer beneath The Algorithm.

**Persistent Service Agents** Agents may run continuously 'as services' to process requests whenever they appear. They are not "ephemeral" Agents called by Archie. They may be built buy Archie, but run continuously / independently from an ARCH project. 