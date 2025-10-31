# Contains Studio Feature Pod Agents

A lean, Sidetool-inspired roster of AI agents designed to operate as a Marty Cagan-style, cross-functional product squad. Instead of dozens of departmental specialists, this repo now centers on a single, high-leverage feature pod that can take a request from problem framing through launch and measurement in six-day sprints.

## 🚀 Why a Feature Pod?

Traditional departmental agents created heavy handoffs and diluted accountability. The new structure:

- **Empowers outcomes** – one pod owns discovery, delivery, and commercial impact end-to-end.
- **Stays lightweight** – five core agents plus an orchestrator cover the full product trio + business + delivery loop.
- **Moves fast** – rituals, templates, and tooling keep focus on the smallest lovable solution each sprint.

This repository now focuses exclusively on that pod so you can spin up a compact agency without wading through legacy rosters.

## 🧠 Core Feature Pod

```
pods/core-feature-team/
├── business-partner.md
├── delivery-partner.md
├── feature-pod-orchestrator.md
├── product-designer.md
├── product-strategist.md
└── tech-lead.md
```

| Agent | What they own |
| --- | --- |
| `feature-pod-orchestrator` | Spins up the squad, manages rituals, keeps context flowing |
| `product-strategist` | Frames opportunities, defines outcomes, and leads discovery synthesis |
| `product-designer` | Translates insights into lovable experiences and validates solutions |
| `tech-lead` | Shapes feasibility, guides implementation, and safeguards quality |
| `delivery-partner` | Orchestrates flow, sequencing, and continuous improvement |
| `business-partner` | Ensures commercial viability, go-to-market alignment, and metric rigor |

Start every engagement with the **feature-pod-orchestrator**. It will pull in the other agents as needed and reference the shared playbook.

## 📘 Feature Pod Playbook

The shared workflow, rituals, and checklists live in [`docs/feature-pod-playbook.md`](docs/feature-pod-playbook.md). It covers:

- Six-day lifecycle from intake ➜ discovery ➜ solution ➜ build ➜ launch ➜ measurement.
- Role-by-role responsibilities and collaboration cues.
- Intake, launch, and measurement checklists to keep the squad aligned on outcomes.
- Artifact templates (intake brief, experiment log, outcome report) for lightweight documentation.

## 📥 Installation

1. **Download this repository:**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```
2. **Copy to your Claude Code agents directory:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   Or manually copy all the agent files to your `~/.claude/agents/` directory.
3. **Restart Claude Code** to load the new agents.

## 🛠️ How to Use the Pod

1. **Kick off with the orchestrator** – share the feature goal, target user, and success metric. It will fan out tasks to the other agents.
2. **Stay outcome-focused** – request support from product-strategist, designer, tech-lead, delivery-partner, or business-partner as the sprint progresses.
3. **Follow the playbook** – use the documented rituals and checklists to keep discovery and delivery tightly coupled.
4. **Review & iterate** – after launch, let the orchestrator drive the outcome review and feed learnings into the next sprint.

## 🤝 Contributing

- Keep new agents lightweight and outcome-oriented.
- Update the feature pod playbook when you introduce new rituals or improvements.
- Prefer expanding the existing pod before adding new departments.

Empowered teams ship better products. This repo gives you a compact, AI-native squad that can own the entire feature journey—just add your product idea.
