# Contains Studio AI Agency

A compact roster of AI agents built for a modern product agency. Each agent
covers a distinct craft area—strategy, design, technology, and operations—so you
get end-to-end support without juggling a crowded bench or outdated sprint
rituals.

## 🌐 Why this structure?

- **One agent per area** keeps the lineup memorable and easy to orchestrate.
- **Outcome-first workflows** replace rigid sprint schedules with client-ready
  phases that flex to the engagement.
- **Lightweight documentation** means you spend time solving problems, not
  maintaining process theatre.

## 🧠 Core Agency Agents

```
pods/agency/
├── strategy-partner.md
├── design-partner.md
├── technology-partner.md
├── operations-partner.md
└── devil-advocate.md
```

| Agent | What they cover |
| --- | --- |
| `strategy-partner` | Opportunity framing, commercial viability, stakeholder narrative |
| `design-partner` | Experience definition, rapid validation, design-to-build alignment |
| `technology-partner` | Architecture, delivery sequencing, quality safeguards |
| `operations-partner` | Planning, communication rhythm, launch & measurement follow-through |
| `devil-advocate` | Assumption busting, risk surfacing, edge case discovery |

Start with the **strategy-partner** to shape the engagement, then bring in the
other partners as the work progresses. Every file includes detailed prompts and
operating principles tailored to that craft.

## 📘 Agency Handbook

Shared ways of working, phase checklists, and artifact templates live in
[`docs/agency-handbook.md`](docs/agency-handbook.md). It replaces sprint-driven
rituals with a flexible, phase-based approach suited for client engagements.

For a workflow-level view of how the agency pod operates from intake to
measurement, see the [`docs/feature-pod-playbook.md`](docs/feature-pod-playbook.md).
It breaks down triggers, handoffs, and deliverables for each phase without
relying on day-by-day cadences.

## 📥 Installation

1. **Download this repository:**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```
2. **Copy to your Claude Code agents directory:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   Or manually copy the agent files to `~/.claude/agents/`.
3. **Restart Claude Code** to load the new agents.

## 🛠️ How to Engage the Agency

1. **Brief the strategy-partner** with the client goal, target user, and success
   signal.
2. **Invite craft partners as needed**—design for experience, technology for
   build planning, operations for coordination.
3. **Follow the handbook phases** to stay aligned on intake, exploration,
   solution, delivery, and measurement.
4. **Document insights lightly** so future iterations start with full context.

## 🤝 Contributing

- Keep new agents lean and oriented around distinct craft areas.
- Update the agency handbook when you introduce better rituals or templates.
- Optimise for clarity, autonomy, and outcomes over process for process' sake.

Build the right thing, communicate clearly, and let these agents keep your AI
agency sharp.
