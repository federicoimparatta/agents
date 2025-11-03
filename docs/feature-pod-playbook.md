# Agency Pod Workflow Playbook

This playbook explains how the Contains Studio AI agency operates as a lean
five-agent pod. Instead of marching through rigid day-by-day schedules, the team
moves through a repeatable workflow that adapts to each engagement's context.
Every step clarifies who leads, what good output looks like, and when to loop in
other craft partners.

## Roles at a Glance

| Agent | Focus | Primary Responsibilities |
| --- | --- | --- |
| strategy-partner | Direction | Frame opportunities, define outcomes, narrate decisions |
| design-partner | Experience | Visualise journeys, validate solutions, steward product feel |
| technology-partner | Delivery | Shape architecture, manage technical risk, ensure quality |
| operations-partner | Flow | Orchestrate rhythm, maintain visibility, drive continuous improvement |
| devil-advocate | Challenge | Stress-test assumptions, expose risks, surface edge cases |

Each agent can be invoked independently, yet the pod performs best when
strategic framing, challenge, experience definition, technical planning, and
operations coordination progress as a single flow.

## Workflow Overview

```
Intake → Insight Loop → Solution Shaping → Build & Integrate → Launch Readiness → Measure & Adapt
```

Every phase has an explicit trigger, a primary owner, and lightweight
artifacts that keep the rest of the pod informed. Phases can overlap when the
work benefits from parallel exploration—as long as ownership remains clear.

**Devil-advocate touchpoints:**
- Intake & Orientation — sanity-check the brief, surface hidden constraints, and
  list the riskiest assumptions to validate first.
- Insight Loop & Solution Shaping — probe edge cases, security/privacy gaps, and
  competing explanations before commitments harden.
- Build through Launch — stress-test readiness plans, failure scenarios, and
  rollback coverage so go/no-go calls are grounded.
- Measure & Adapt — review what failed or nearly failed to update future risk
  checklists.

## Phase Details

### 1. Intake & Orientation
- **Trigger:** A new brief, opportunity, or escalation reaches the agency.
- **Lead:** strategy-partner, supported by operations-partner.
- **Objectives:** Clarify the problem, desired outcome, guardrails, and decision
  makers. Decide which craft partners are needed immediately.
- **Key outputs:** Opportunity outline, success measures, constraints log,
  engagement channel setup, risk/assumption log.
- **Hand-off signal:** All partners understand the problem statement and have a
  single source of truth to reference.

### 2. Insight Loop
- **Trigger:** Problem framing is validated and there are open assumptions to test.
- **Lead:** strategy-partner and design-partner pair.
- **Objectives:** Gather qualitative and quantitative insight, map hypotheses,
  and tag confidence levels.
- **Key outputs:** Insight digest, opportunity map, evidence tracker, list of
  decisions awaiting proof, updated risk likelihood/impact notes.
- **Hand-off signal:** Highest-leverage opportunities are prioritised with
  supporting evidence or an explicit plan to validate further.

### 3. Solution Shaping
- **Trigger:** Top opportunities and success measures are agreed.
- **Lead:** design-partner with technology-partner and strategy-partner.
- **Objectives:** Co-create the recommended experience, sequence delivery
  slices, and articulate how the solution meets business outcomes.
- **Key outputs:** Prototype or narrative walkthrough, technical approach,
  measurement plan, updated decision log, devil-advocate edge-case rundown.
- **Hand-off signal:** Pod shares a clear solution story and knows what must be
  built, tested, and communicated.

### 4. Build & Integrate
- **Trigger:** Solution story approved and slices defined.
- **Lead:** technology-partner with operations-partner maintaining flow.
- **Objectives:** Implement the agreed slices, keep work-in-progress healthy,
  and safeguard quality, security, and observability.
- **Key outputs:** Working increments, technical runbook, QA checklist, status
  digest, failure-mode mitigation list.
- **Hand-off signal:** Increment meets acceptance criteria and is ready for
  launch rehearsal.

### 5. Launch Readiness
- **Trigger:** Increment passes technical validation and user acceptance.
- **Lead:** operations-partner coordinating all agents.
- **Objectives:** Confirm go-to-market narrative, enablement, support,
  analytics, and risk mitigations. Secure stakeholder confidence for launch.
- **Key outputs:** Launch kit, enablement briefing, monitoring dashboards,
  support playbook, go/no-go decision record, rollback scenario validation.
- **Hand-off signal:** Leadership signs off, launch timetable is confirmed, and
  contingency plans are documented.

### 6. Measure & Adapt
- **Trigger:** Outcome data and qualitative feedback begin to arrive post-launch.
- **Lead:** strategy-partner synthesising input from all agents.
- **Objectives:** Evaluate performance against success measures, capture
  learnings, and prioritise follow-up experiments or iterations.
- **Key outputs:** Outcome report, improvement backlog, updated hypothesis
  tracker, retro summary, refreshed risk playbook for future cycles.
- **Reset signal:** Decision made on whether to double-down, iterate, or sunset,
  which restarts the intake flow as needed.

## Agent Collaboration Patterns

- **Strategy ↔ Design:** Pair early to ensure insights translate into experience
  decisions. Share short Loom or FigJam walkthroughs instead of heavy decks.
- **Design ↔ Technology:** Review prototypes alongside delivery slices so
  trade-offs are surfaced before build begins.
- **Technology ↔ Operations:** Maintain a shared implementation board with
  quality gates and risk flags; automate status snapshots wherever possible.
- **Operations ↔ Strategy:** Keep the decision log current so new context is
  reflected in future framing and stakeholder updates.

## Communication & Visibility

- **Kickoff note (Intake):** Links to brief, success measures, and owners.
- **Insight digests (Insight Loop):** Async updates summarising evidence, open
  questions, and decisions needed.
- **Solution reviews (Solution Shaping):** Short sessions or recordings showing
  prototypes, delivery plan, and measurement approach.
- **Build pulses (Build & Integrate):** Twice-weekly async updates covering
  progress, blockers, and release confidence.
- **Launch rehearsal (Launch Readiness):** Structured walk-through of readiness
  checklists and rollback plans.
- **Outcome readout (Measure & Adapt):** Narrative summarising metrics, signal,
  and proposed next bets.

## Lightweight Checklists

| Phase | Critical Checks |
| --- | --- |
| Intake & Orientation | Problem, audience, outcome, and constraints captured. Stakeholders and cadence confirmed. |
| Insight Loop | Hypotheses tagged with confidence, evidence stored in a shared tracker, open questions logged with owners. |
| Solution Shaping | Prototype/story approved, delivery slices defined, measurement plan agreed, decision log updated. |
| Build & Integrate | Acceptance criteria met, QA + monitoring in place, dependencies cleared, deployment plan reviewed. |
| Launch Readiness | Enablement assets ready, support teams briefed, analytics validated, go/no-go recorded with mitigations. |
| Measure & Adapt | Metrics analysed, qualitative feedback synthesised, improvement backlog prioritised, next checkpoint scheduled. |

## Continuous Improvement

After each cycle, the operations-partner runs a lightweight retrospective with
input from every agent. Capture what increased clarity, where delays happened,
and which tooling tweaks paid off. Update this playbook whenever a new practice
improves speed, quality, or client confidence.

Stay lean, stay outcome-focused, and keep the workflow flexible enough to meet
any engagement with confidence.
